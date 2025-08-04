# ⚡ Power Fault Detector on IBM Cloud

This project was developed as part of the IBM SkillsBuild Capstone Internship.

## 📌 Problem Statement

Faults in power distribution systems—such as line-to-ground, line-to-line, and three-phase faults—must be detected quickly to ensure system reliability and avoid equipment damage or outages.

## 💡 Proposed Solution

A machine learning-based solution using voltage and current phasor data to classify power system faults. The system is trained using a Random Forest model and deployed on IBM Cloud Lite using IBM Watson Studio.

## 🛠️ Tools & Technologies

- **Platform:** IBM Cloud Lite
- **IDE:** IBM Watson Studio, Jupyter Notebook
- **Languages:** Python
- **Libraries:** scikit-learn, pandas, numpy, matplotlib

## ⚙️ Steps Involved

1. **Data Collection**  
   - Voltage and current phasor data from simulated environments.

2. **Data Preprocessing**  
   - Noise removal, missing value handling, normalization.

3. **Feature Extraction**  
   - Relevant feature selection from electrical data.

4. **Model Selection**  
   - Random Forest Classifier chosen for accuracy and interpretability.

5. **Training & Evaluation**  
   - Model trained on labeled dataset and evaluated using accuracy, precision, recall, F1-score.

6. **Deployment**  
   - Model deployed on IBM Cloud via Watson Studio and exposed through a simple interface.

## 📊 Results

- Real-time fault classification (normal vs fault types)
- High classification accuracy
- Confusion matrix and cross-validation used for validation

## 🚀 Future Enhancements

- Integration with live SCADA system data
- Mobile/web dashboards for field engineers
- GPS-based visualization of fault locations
- Use of deep learning models (e.g., LSTM) for improved accuracy

## 📚 References

- Kaggle Dataset: [Power System Faults](https://www.kaggle.com/datasets/ziya07/power-systemfaults-dataset)  
- IBM Cloud: [cloud.ibm.com](https://cloud.ibm.com)  
- IBM Watson Studio Documentation

## 👤 Author

**Lakkam Chandu**  
B.Tech CSE (AIML), Malla Reddy College of Engineering and Technology

---

✅ **Certifications:**
- IBM SkillsBuild: Getting Started with Artificial Intelligence
- IBM SkillsBuild: Journey to Cloud – Envisioning Your Solution
- Lab Completion: Retrieval Augmented Generation with LangChain
