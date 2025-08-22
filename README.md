# 🧠 Brain Tumor Classification  
**Image Classification with DenseNet121 and NASNet on a Large Dataset**  

This project contains Jupyter notebooks for training and evaluating deep learning models—**DenseNet121** and **NASNetLarge**—on a large image dataset. Both models are built using **pretrained architectures from Keras Applications** and fine-tuned for custom image classification tasks.  

---

## 📂 Contents  
- **`densenet121_large_dataset.ipynb`** → Training & evaluation using DenseNet121  
- **`nasnet_large_dataset_large.ipynb`** → Training & evaluation using NASNetLarge  

---

## ✨ Features  
- 🔗 Transfer learning with pre-trained **ImageNet weights**  
- 🔄 Data preprocessing & augmentation  
- 📉 Training with validation monitoring  
- 📊 Evaluation using accuracy, confusion matrix & classification report  
- 💾 (Optional) Model checkpointing & saving  

---

## ⚙️ Requirements  
Install dependencies using:  

```bash
pip install -r requirements.txt
```
```bash
pip install tensorflow keras matplotlib scikit-learn numpy pandas
```
## 📁 Dataset Structure
You need to provide your own dataset structured as follows:
dataset/
├── train/
│   ├── class1/
│   ├── class2/
│   └── ...
└── validation/
    ├── class1/
    ├── class2/
    └── ...
## 🚀 Usage
Clone the repository:
```bash
git clone https://github.com/Mohdumair19/brain_tumor_classification.git
cd your-repo-name
```
Open the notebook you want to run:
```bash
jupyter notebook densenet121_large_dataset.ipynb
```
or
```bash
jupyter notebook nasnet_large_dataset_large.ipynb
```
Follow the notebook cells to train & evaluate the model.

## 📊 Results
The notebooks generate and display:
- ✅ Classification accuracy
- 📉 Loss curves
- 🔎 Confusion matrix
- 📑 Classification report
