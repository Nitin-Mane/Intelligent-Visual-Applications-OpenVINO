# 🧠 OpenVINO™ 2025.2 Installation and Hello World Project Guide

## 📥 Step 0: Install Anaconda (Python Distribution)

Before setting up OpenVINO™, please install [Anaconda](https://www.anaconda.com/products/distribution) on your system.  
> Recommended Python Version: **3.10**

- Download the appropriate installer for your OS (Windows/macOS/Linux)
- Follow the guided setup and verify installation by running:

```bash
conda --version
````

---

## ⚙️ Step 1: OpenVINO 2025.2 Installation via Conda (Windows)

Follow the official installation instructions for the **OpenVINO Base Package (2025.2)** using **Conda**:

> 📄 Reference: [OpenVINO 2025.2 Installation Guide](https://docs.openvino.ai/2025/get-started/install-openvino.html?PACKAGE=OPENVINO_BASE&VERSION=v_2025_2_0&OP_SYSTEM=WINDOWS&DISTRIBUTION=CONDA)

### 🔧 Instructions

```bash
# Step 1: Create the Anaconda environment (Python 3.10 used as an example)
conda create --name py310 python=3.10

# Step 2: Activate the Anaconda environment
conda activate py310

# Step 3: Update the Anaconda environment to the latest version
conda update --all

# Step 4: Download and install the OpenVINO package
conda install -c conda-forge openvino=2025.2.0
```

---

## 👋 Step 2: Run a Sample Project - Hello Image Classification

To verify the installation and begin experimenting with OpenVINO’s features, try the official **Hello Image Classification** notebook from OpenVINO Notebooks:

> 📘 GitHub Link: [Hello Image Classification – OpenVINO Notebooks](https://github.com/openvinotoolkit/openvino_notebooks/tree/latest/notebooks/hello-world)

### What You'll Learn:

* Load and convert a model to OpenVINO IR format
* Perform image classification on sample images
* Run inference using OpenVINO Runtime

---

## 📌 Additional Notes

* 💡 Make sure `conda` and Python 3.10+ are properly installed before proceeding.
* 📦 You may explore additional OpenVINO components from [OpenVINO Toolkit GitHub](https://github.com/openvinotoolkit/openvino).
* ✅ Use `jupyter notebook` or `jupyter lab` to run the `.ipynb` files from the notebook repository.

---

## 🙋 Need Help?

For support and advanced use cases, visit:

* [OpenVINO Documentation](https://docs.openvino.ai/)
* [Intel Developer Forum](https://community.intel.com/t5/Intel-Distribution-of-OpenVINO/bd-p/distribution-openvino-toolkit)

---

> Prepared by **Nitin Mane**, Intel Software Innovator
> For workshop at **SSGMCE Shegaon** | **24th July 2025**
