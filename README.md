# automated-pneumonia-diagnosis-efficientnet
A complete workflow for automated diagnosis of pneumonia from chest X‑ray images using the EfficientNet convolutional neural network architecture. The core is a Jupyter notebook that covers data loading, preprocessing, model training, evaluation, and visualization of results.

---

## 📁 Folder Structure

```
automated-pneumonia-diagnosis-efficientnet/
├── README.md
├── requirements.txt
├── Automated Diagnosis of Pneumonia from Classification of Chest X-Ray Images using EfficientNet.ipynb
├── paper/
│   └── <original_research_paper>.pdf
```

---

## 📖 Notebook

* **Location**: `Automated_Diagnosis_of_Pneumonia_from_Classification_of_Chest_XRay_Images_using_EfficientNet.ipynb`
* **Contents**:

  1. Data loading and directory traversal
  2. Class imbalance handling
  3. Image augmentation with `ImageDataGenerator`
  4. Model definition using `tensorflow.keras.applications.EfficientNetB0`
  5. Compilation and training loops
  6. Evaluation metrics: accuracy, classification report, ROC AUC
  7. Visualization of training history and ROC curve
  8. Saving trained model and plots

---

## ⚙️ Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/AryaKoureshi/automated-pneumonia-diagnosis-efficientnet.git
   cd automated-pneumonia-diagnosis-efficientnet
   ```
2. (Optional) Create a virtual environment:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
3. Install required packages:

   ```bash
   pip install -r requirements.txt
   ```

---

## 🚀 Usage

Open and run the notebook:

   ```bash
   jupyter notebook Automated_Diagnosis_of_Pneumonia_from_Classification_of_Chest_XRay_Images_using_EfficientNet.ipynb
   ```
---

## 📈 Results

* Model performance metrics (accuracy, precision, recall, F1-score, ROC curve) are displayed in the notebook.

---

## 📚 Paper

```
paper/Automated_Diagnosis_of_Pneumonia_from_Classification_of_Chest_XRay_Images_using_EfficientNet.pdf
```
