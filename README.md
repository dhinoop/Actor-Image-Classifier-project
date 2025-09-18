# Actor Image Classifier 🎭

A Convolutional Neural Network (CNN) model built using **TensorFlow/Keras** to classify images of two famous actors: **Mammootty** and **Mohanlal**.

## 📌 Project Overview
- Preprocessed images using OpenCV, NumPy, and PIL
- Built a CNN model for binary image classification
- Classified:
  - `0 → Mammootty`
  - `1 → Mohanlal`

## 🗂️ Project Structure
```
Image_Classifier/
│── actors.ipynb          # Main Jupyter Notebook
│── requirements.txt      # Python dependencies
│── README.md             # Project documentation
│── .gitignore            # Ignored files
└── dataset/              # Image dataset (not included in repo)
```

## ⚙️ Installation & Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd Image_Classifier
   ```

2. Create and activate a virtual environment:
   ```bash
   conda create -n cnnenv python=3.9
   conda activate cnnenv
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## ▶️ Usage
Open the notebook and run all cells:
```bash
jupyter notebook actors.ipynb
```

## 📊 Results
The model successfully classifies images of Mammootty and Mohanlal with good accuracy.  

---
