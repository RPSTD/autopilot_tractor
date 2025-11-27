# 🚜 Autopilot Tractor

An experimental **vision-based autopilot system for tractors** using deep learning.  
This project focuses on **data collection, model training, evaluation, and real-time inference**, all implemented using **Python and Jupyter Notebooks** with optional **TensorRT acceleration**.

---

## 📂 Repository Structure

```
autopilot_tractor/
│
├── data_collection.ipynb              # Capture training data from camera
├── train_model.ipynb                  # Train baseline model
├── train_model_resnet18.ipynb         # Train ResNet-18 model
├── train_model_plot.ipynb             # Training metrics visualization
│
├── live_demo.ipynb                    # Real-time inference demo
├── live_demo_resnet18.ipynb           # Live demo using ResNet-18
├── live_demo_resnet18_build_trt.ipynb # Build TensorRT engine
├── live_demo_resnet18_trt.ipynb       # Run TensorRT-optimized inference
│
├── LICENSE
└── README.md
```

---

## ✨ Features

- Camera-based dataset collection  
- Deep learning autopilot control model  
- Training visualization and metrics  
- Live camera inference  
- TensorRT acceleration support  
- Fully notebook-driven workflow  

---

## 🧰 Requirements

### Software
- Python 3.8+
- Jupyter Notebook / Jupyter Lab
- PyTorch
- OpenCV
- NumPy
- Matplotlib

### Optional
- NVIDIA GPU
- CUDA
- TensorRT

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/RPSTD/autopilot_tractor.git
cd autopilot_tractor
```

Install dependencies:

```bash
pip install torch torchvision torchaudio
pip install opencv-python numpy matplotlib notebook
```

---

## 📊 Data Collection

```bash
jupyter notebook data_collection.ipynb
```

---

## 🧠 Model Training

```bash
jupyter notebook train_model.ipynb
jupyter notebook train_model_resnet18.ipynb
```

---

## 🎥 Live Demo

```bash
jupyter notebook live_demo.ipynb
```

---

## ⚡ TensorRT

```bash
jupyter notebook live_demo_resnet18_build_trt.ipynb
jupyter notebook live_demo_resnet18_trt.ipynb
```

---

## ⚠️ Disclaimer

This project is experimental and for research/education only.

---

## 📄 License

MIT License
