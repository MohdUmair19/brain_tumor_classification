# brain_tumor_classification
Image Classification with DenseNet121 and NASNet on a Large Dataset
This repository contains Jupyter notebooks for training and evaluating deep learning models—DenseNet121 and NASNetLarge—on a large image dataset. These models are based on pretrained architectures from Keras Applications and fine-tuned for custom image classification tasks.

Contents
densenet121_large_dataset.ipynb: Notebook for training and evaluating a DenseNet121 model.

nasnet_large_dataset_large.ipynb: Notebook for training and evaluating a NASNetLarge model.

Features
Transfer learning using pre-trained ImageNet weights.

Data preprocessing and augmentation.

Training with validation monitoring.

Evaluation with accuracy, confusion matrix, and classification report.

(Optional) Model checkpointing and saving.

Requirements
Install dependencies using pip:

bash
Copy
Edit
pip install -r requirements.txt
If no requirements.txt is provided, install typical libraries used in Keras/TensorFlow projects:

bash
Copy
Edit
pip install tensorflow keras matplotlib scikit-learn numpy pandas
Dataset
You need to provide your own dataset structured in the following way:

markdown
Copy
Edit
dataset/
├── train/
│   ├── class1/
│   ├── class2/
│   └── ...
└── validation/
    ├── class1/
    ├── class2/
    └── ...
You can customize the data path in the notebooks under the ImageDataGenerator or flow_from_directory section.

Usage
Clone the repository:

bash
Copy
Edit
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
Open the notebook you want to run:

bash
Copy
Edit
jupyter notebook densenet121_large_dataset.ipynb
or

bash
Copy
Edit
jupyter notebook nasnet_large_dataset_large.ipynb
Follow the cells to train and evaluate the model.

Results
Model evaluation metrics such as classification accuracy, loss curves, and confusion matrices are generated and displayed within the notebooks.

License
This project is open-source and available under the MIT License.
