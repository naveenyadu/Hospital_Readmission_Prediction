# Hospital_Readmission_Prediction

Here’s a detailed and structured README file you can use for your GitHub repository:

---

# **Hospital Readmission Prediction System**

## 🚀 **Overview**
The **Hospital Readmission Prediction System** is a cutting-edge project designed to leverage advanced **Large Language Models (LLMs)** to predict hospital readmissions within 30 days. Developed as part of the **DATA 298B Capstone Project** at **San Jose State University**, this system empowers healthcare professionals with actionable insights, enabling better patient care and efficient resource utilization.

## 🩺 **Objective**
To reduce hospital readmissions by building a scalable, accurate, and real-time prediction system using the **MIMIC-III** dataset. The system integrates with healthcare IT systems and provides healthcare providers with insights to:
- Identify high-risk patients.
- Personalize care plans.
- Optimize hospital resources.

## 📊 **Dataset**
The project uses the publicly available **MIMIC-III (Medical Information Mart for Intensive Care)** dataset, which includes:
- Patient demographics
- Admission and discharge information
- Medical history and diagnoses
- Clinical notes and lab results

## 💡 **Key Features**
1. **Advanced Predictive Models**:
   - ClinicalBERT
   - PubMedBERT
   - Clinical BigBird
   - GPT-4 Turbo
   - Clinical XLNet
2. **Performance Metrics**:
   - Accuracy: 85%+
   - Precision, Recall, F1-Score: Above industry standards
3. **Secure & Scalable Architecture**:
   - Built using **Python, FastAPI, and React**.
   - Cloud storage on **AWS S3**, ensuring HIPAA compliance.

## 🛠 **Tech Stack**
- **Backend**: Python, FastAPI
- **Frontend**: React
- **Cloud**: AWS (S3, EC2)
- **Libraries**: PyTorch, Hugging Face Transformers, Med7
- **Data Analysis**: Pandas, NumPy, Scikit-learn

## ⚙️ **How It Works**
1. **Data Preprocessing**:
   - Cleaned, tokenized, and normalized patient data.
   - Feature engineering to identify key predictors of readmission.
2. **Model Training**:
   - Trained multiple LLMs on structured and unstructured data.
   - Fine-tuned for maximum predictive accuracy.
3. **Evaluation**:
   - Assessed model performance using metrics like accuracy, precision, recall, and F1-score.
4. **Deployment**:
   - Real-time prediction system integrated with a React-based user interface.

## 🎯 **Outcomes**
- **Proactive Healthcare**: Early identification of high-risk patients.
- **Optimized Resources**: Improved allocation of hospital resources.
- **Enhanced Patient Care**: Reduced readmission rates and better health outcomes.

## 🔧 **Installation**
### Prerequisites:
- Python 3.9+
- Node.js
- AWS account

### Steps:
Clone the repository:
   ```bash
   git clone https://github.com/naveenyadu/hospital_readmission_prediction.git
   cd hospital_readmission_prediction
   ```

   ```

## 🔍 **Usage**
1. Upload patient data via the frontend interface.
2. The system preprocesses the data and makes predictions in real-time.
3. Visualize results, including readmission probabilities and key risk factors.

## 📖 **Contributing**
We welcome contributions to enhance the system's features and capabilities. To contribute:
1. Fork the repository.
2. Create a feature branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and create a pull request.

## 🛡 **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙌 **Acknowledgments**
- **Team Members**: Jaya Lakshmi Gunji, Naveen Yadav Gongati, Neha Dabeeru, Priyanka Akula, Somna Sattoor
- **Mentor**: Simon Shim
- **Dataset**: [MIMIC-III Database](https://mimic.mit.edu/)

## 🤝 **Connect with Us**
Have questions or suggestions? Reach out to us:
- [Naveen Yadav Gongati - LinkedIn](https://www.linkedin.com/in/naveen-yadav-gongati/)
- [Email](mailto:naveenyadu988@gmail.com)

---

Feel free to adjust the content based on specific repository details and configurations!
