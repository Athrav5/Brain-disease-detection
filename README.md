# 🧠 Brain Disease Detection Using AI

An AI-powered web application that uses Deep Learning and Computer Vision to classify brain MRI images for brain tumor, stroke, and Alzheimer's disease detection.

## 📌 Project Overview

**Brain Disease Detection Using AI** is a final-year engineering project developed to explore the application of Artificial Intelligence in medical image analysis.

The application allows users to upload brain images through a web interface. The images are preprocessed and analyzed using trained Deep Learning models, and the system displays the resulting classification.

The project combines Machine Learning, Deep Learning, Computer Vision, Web Development, and Database Management.

> **Disclaimer:** This project is intended for educational and research purposes only. Its predictions are not a medical diagnosis and must not replace evaluation by a qualified healthcare professional.

## 🎯 Project Objectives

- Develop an AI-based brain image classification system.
- Explore brain tumor, stroke, and Alzheimer's disease classification.
- Apply image preprocessing techniques to MRI images.
- Integrate trained Deep Learning models with a Flask web application.
- Provide a simple interface for image upload and prediction.
- Explore the use of AI in healthcare-related research.

## ✨ Features

- 🧠 Brain MRI image classification
- 🔬 Image preprocessing using OpenCV
- 🤖 Deep Learning models using TensorFlow and Keras
- 🌐 Flask-based web application
- 🗄️ MySQL database integration
- 📤 Image upload functionality
- 📊 Prediction result display
- 🧪 Model development using Python and Jupyter Notebook

*Feature availability depends on the models and modules configured in the application.*

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| TensorFlow | Deep Learning framework |
| Keras | Neural network development |
| VGG16 | Transfer learning / feature extraction |
| OpenCV | Image processing |
| NumPy | Numerical operations |
| Pandas | Data manipulation |
| Flask | Web application backend |
| HTML, CSS, JavaScript | Frontend development |
| MySQL | Database management |
| Jupyter Notebook | Model experimentation |
| Git & GitHub | Version control |

## 🧠 Disease Classification Modules

### 1. Brain Tumor Detection

Uses a trained image classification model to analyze brain images and predict the relevant tumor classification represented in the training dataset.

### 2. Stroke Detection

Explores Deep Learning-based classification of brain images for stroke-related categories represented by the trained model.

### 3. Alzheimer's Disease Detection

Uses a trained neural network to classify brain images into the categories supported by the model.

**Important:** These modules are experimental classification tools. Their predictions have not been established as clinically reliable diagnoses.

## ⚙️ How the System Works

1. The user opens the Flask web application.
2. The user uploads a supported brain image.
3. The application preprocesses the image.
4. The appropriate trained model processes the image.
5. The model generates a classification result.
6. The application displays the result to the user.

```text
User
  ↓
Flask Web Application
  ↓
Upload Brain Image
  ↓
Image Preprocessing (OpenCV / NumPy)
  ↓
Trained Deep Learning Model
  ↓
Image Classification
  ↓
Display Prediction
```

## 🏗️ Project Architecture

The project consists of the following major components:

- **Frontend:** Provides the user interface for image upload and result display.
- **Backend:** Flask handles requests and coordinates the prediction workflow.
- **Image Processing:** OpenCV and NumPy prepare images for model input.
- **Deep Learning:** TensorFlow/Keras models perform image classification.
- **Database:** MySQL supports the application's configured data-storage features.

## 📂 Project Structure

```text
Brain-disease-detection/
│
├── app.py
├── brain_prefinal.py
├── hybrid_approach.py
├── alzheimer_train_model.py
├── alzheimer-mri-prediction.ipynb
├── balanced_labels.csv
├── Brain_Disease_Prediction.sql
│
├── model/
│   └── Trained model files (stored separately)
│
├── static/
│   └── CSS, JavaScript, images and uploads
│
├── templates/
│   └── HTML templates
│
├── content/
│   └── Supporting project files
│
├── requirements.txt
├── .gitignore
└── README.md
```

*This is an indicative structure. Actual filenames and folders may differ slightly in the repository.*

## 💻 Requirements

- Python 3.10 or another Python version compatible with the project's dependencies
- pip
- MySQL Server, if database functionality is required
- Git
- Trained model files required by the application

## 🚀 Installation and Setup

### Step 1: Clone the Repository

```bash
git clone https://github.com/Athrav5/Brain-disease-detection.git
```

### Step 2: Open the Project Folder

```bash
cd Brain-disease-detection
```

### Step 3: Create a Virtual Environment

Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

### Step 4: Install Dependencies

If `requirements.txt` exists:

```bash
pip install -r requirements.txt
```

If the dependency file is named `requirement.txt`, rename it to `requirements.txt` or use its current filename in the command.

For compatibility, install the TensorFlow/Keras versions specified by the project. Do not assume every TensorFlow version supports every Python version.

### Step 5: Configure MySQL

If the application requires MySQL:

1. Start MySQL Server.
2. Create the required database.
3. Import `Brain_Disease_Prediction.sql` using MySQL Workbench or the MySQL command line.
4. Configure the database connection in the application.

Use your own local database credentials. Never publish real passwords, secret keys, or other credentials on GitHub.

### Step 6: Add the Trained Models

Large `.keras` and `.h5` files are excluded from this repository because of GitHub file-size limits.

Download or obtain the required model files from a trusted storage location and place them in the appropriate `model/` directory.

The model filenames and paths must match those referenced by the application code.

### Step 7: Run the Application

```bash
python app.py
```

If startup is successful, open the local URL shown in the terminal, commonly:

```text
http://127.0.0.1:5000/
```

## 📊 Model Development

The project uses TensorFlow/Keras for Deep Learning experimentation and includes work with VGG16-based transfer learning.

The general model development pipeline is:

1. Collect and organize the dataset.
2. Inspect labels and clean the data.
3. Preprocess the images.
4. Split the data into training, validation, and test sets.
5. Train or fine-tune the model.
6. Evaluate the model using appropriate metrics.
7. Save the trained model for integration with Flask.

## 📈 Evaluation Metrics

The models can be evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

Actual performance metrics should be added here after evaluation on a separate, representative test dataset. No accuracy figures are claimed in this README.

## 🔒 Large Model Files

The repository excludes large model files and virtual environments to keep the GitHub repository manageable.

Common excluded files and directories include:

```text
venv/
venv312/
__pycache__/
*.pyc
.env
model/*.keras
model/*.h5
```

If the application requires trained models, provide a documented download method or use a suitable model-storage service. Do not upload credentials or private datasets.

## 🔮 Future Scope

- Improve model evaluation and generalization.
- Add explainable AI methods such as Grad-CAM.
- Develop a more responsive user interface.
- Improve model and dataset documentation.
- Add secure user authentication and prediction history.
- Deploy the application in a controlled research environment.
- Evaluate models on independent datasets before considering clinical applications.

## 🎓 Learning Outcomes

This project provides practical experience in:

- Python programming
- Machine Learning and Deep Learning
- CNNs and transfer learning
- Medical image preprocessing
- TensorFlow and Keras
- Flask web development
- MySQL database integration
- Git and GitHub
- AI application development

## 👨‍💻 Project Team

**Project Title:** Brain Disease Detection Using AI

**Team Members:**
- Athrav Patil
- Rashid Shaikh
- Pratik Pote
- Suraj Palavi

**Project Guide:** Ms. G. D. Bendale

**Academic Program:** Bachelor of Engineering – Computer Engineering

## ⚠️ Medical Disclaimer

This project is an educational prototype and is not approved or validated as a medical diagnostic device. Its outputs may be inaccurate or misleading. Do not use it to make medical decisions, delay care, or determine treatment. Consult a qualified healthcare professional for medical concerns.

## 🔗 GitHub Repository

[View Brain Disease Detection on GitHub](https://github.com/Athrav5/Brain-disease-detection)

If you find this project useful, consider giving the repository a ⭐.

## 📄 License

Before reusing or distributing this project, review the licenses and terms applicable to the source code, datasets, pretrained models, and other third-party components.
