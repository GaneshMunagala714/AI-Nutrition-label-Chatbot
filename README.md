# AI-Nutrition-label-Chatbot
AI-powered nutrition label extraction and health classification chatbot using OCR and Deep Learning.  
## Smart Food Health Assistant using OCR & Deep Learning

---

##  Overview

The **AI Nutrition Label Chatbot** is an end-to-end intelligent system that extracts nutritional information from food labels and classifies food healthiness using Deep Learning.

This project combines:

- Optical Character Recognition (OCR)
- Data preprocessing pipelines
- Feature engineering
- Artificial Neural Networks (ANN)
- Chat-based health explanation module

The system transforms raw nutrition labels into meaningful, structured health insights.

---

## Problem Statement

Understanding nutrition labels can be challenging due to:

- Inconsistent unit formats (mg, g, kcal)
- Complex ingredient lists
- Lack of contextual health interpretation
- Difficulty comparing products

This project automates:

✔ Nutrition extraction  
✔ Data normalization  
✔ Health classification  
✔ Chatbot-based explanation  

---

## System Architecture

### 1.Input Layer
- Food label image or structured text

### 2.OCR Module
- Extracts raw text from label
- Cleans unwanted characters
- Structures nutritional values

### 3.Data Preprocessing
- Unit normalization (mg → g where needed)
- Missing value handling
- Feature selection
- Data transformation

### 4.Deep Learning Model
- Multi-Layer Perceptron (MLP / ANN)
- Hidden Dense Layers
- ReLU Activation
- Softmax Output

Classification Output:
- Healthy
- Moderate
- Unhealthy

### 5.Chatbot Layer
- Explains classification result
- Answers nutrition-related queries
- Provides comparison insights

---

## Tech Stack

| Component       |         Technology                  |
|-----------------|-------------------------------------|
| Language        | Python                              |
| Development     | Jupyter Notebook                    |
| OCR             | Tesseract / EasyOCR                 |
| Data Processing | Pandas, NumPy                       |
| ML Framework    | TensorFlow / PyTorch / Scikit-learn |
| Model Type      | Artificial Neural Network (ANN)     |
| Visualization   | Matplotlib / Seaborn                |

---

## Model Development

### Feature Engineering
- Extracted macronutrients (Protein, Carbs, Fat)
- Extracted micronutrients (Sodium, Sugar)
- Standardized units across dataset
- Created structured dataset from OCR output

### Model Architecture
- Input Layer (Nutritional Features)
- 2–3 Hidden Dense Layers
- ReLU Activation
- Dropout (if used)
- Softmax Output Layer

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

The model predicts health category based on nutrient density and caloric distribution.

---

## Project Structure
AI-Nutrition-label-Chatbot
│
├── docs/
│ └── AI_Nutrition_Label_Chatbot_Report.pdf
│
├── notebooks/
│ └── ai_nutrition_label_chatbot.ipynb
│
├── README.md
├── LICENSE
└── .gitignore    

## How to run
1.Clone Repository
git clone https://github.com/yourusername/AI-Nutrition-label-Chatbot.git
cd AI-Nutrition-label-Chatbot

2.Install Dependencies
pip install -r requirements.txt

3.Launch Notebook
Open:
notebooks/ai_nutrition_label_chatbot.ipynb
Run cells sequentially.

## Key Features
- Automated nutrition extraction
- Health classification using ANN
- Clean preprocessing pipeline
- Chatbot explanation module
- End-to-end AI workflow

## Future Enhancements
- Deploy as Streamlit Web Application
- Real-time camera-based scanning
- Cloud deployment (AWS)
- Model optimization
- API conversion for production




Run all cells sequentially.

---

# Example Workflow

1. Upload label image  
2. OCR extracts nutrition text  
3. Data normalized & structured  
4. ANN predicts health category  
5. Chatbot explains decision  

---

# Future Enhancements

- Convert notebook to production API  
- Deploy via Streamlit Web App  
- Integrate camera-based scanning  
- Cloud deployment (AWS EC2 + S3)  
- Improve OCR with image preprocessing  
- Add recommendation engine  

---

# Academic Context

Developed as part of Deep Learning coursework focusing on:

- Neural Network design  
- Real-world OCR preprocessing  
- Feature engineering  
- Model evaluation  
- Explainable AI pipeline  

---

# Author

**Ganesh Munagala**  
Master’s in Data Science  
University of New Haven  

---

# License

MIT License

---

<p align="center">
  ⭐ Star this repository if you found it useful.
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,100:0f2027&height=120&section=footer"/>
</p>

 ## Documentation
   Full project documentation available in:
   docs/AI_Nutrition_Label_Chatbot_Report.pdf 
