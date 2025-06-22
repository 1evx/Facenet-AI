# Face Recognition with FaceNet and MTCNN (PyTorch)

This project provides a simple and efficient pipeline for face recognition using the **FaceNet** model with **MTCNN** for face detection. It leverages pretrained models from the excellent [facenet-pytorch](https://github.com/timesler/facenet-pytorch) repository and integrates them into a streamlined, easy-to-understand workflow.

The core of this project is the custom Jupyter notebook: `facenet_test.ipynb`, which showcases face detection, embedding extraction, and face similarity measurement using PyTorch.

---

## 🚀 Quick Start

### 1. Clone this repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

### (Optional) Create a virtual environment
```bash
python3.10 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

### Install required packages
```bash
pip install -r requirements.txt
```

### File Directories
File Directories
├── facenet_test.ipynb     # Core notebook - custom face recognition pipeline
├── requirements.txt       # Python dependencies
├── data                   # Dataset folder
    ├── cropped_images     # Images cropped by MTCNN
    ├── target_images      # Images to be tested
    └── train_images       # Images to be trained by model
