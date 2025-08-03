# AutoAI-Based NSAP Scheme Eligibility Predictor

This project uses **IBM Watson AutoAI** to build a predictive model that determines which NSAP (National Social Assistance Programme) scheme an individual is eligible for based on demographic information.

## 🔍 Problem Statement
Identifying eligible applicants for NSAP schemes like IGNOAPS, IGNDPS, or others can be slow and error-prone when done manually. This project solves the problem using an AI-based model hosted on IBM Cloud.

## ⚙️ Technologies Used
- IBM Cloud
- IBM Watson Studio
- IBM AutoAI
- Watson Machine Learning (Deployment)
- CSV Dataset from AI Kosh (IndiaAI.gov.in)

## 📥 Input Features
- Age
- Gender
- Disability Status
- Income Level
- Marital Status
- State of Residence

## 🎯 Output
Predicted NSAP scheme eligibility:
- IGNOAPS
- IGNDPS
- None

## 🚀 How to Use
1. Upload your applicant data via the Watson Studio UI or API.
2. The model will process input and return the eligible scheme.
3. Outputs can be visualized graphically or accessed via REST API.

## 🧪 Project Status
- ✅ AutoAI experiment completed
- ✅ Best model selected and deployed
- ✅ Real-time API enabled
- ✅ Tested via Watson Studio Test UI

## 📄 Author
**Vaishnavi Suryawanshi**

## 📚 References
- [IBM Watson Studio](https://www.ibm.com/cloud/watson-studio)
- [AutoAI Documentation](https://dataplatform.cloud.ibm.com/docs/content/wsj/autoai/autoai-overview.html)
- [AI Kosh Dataset](https://aikosh.indiaai.gov.in/)
