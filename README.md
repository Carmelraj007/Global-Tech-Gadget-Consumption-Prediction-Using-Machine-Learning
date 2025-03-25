# Global Tech Gadget Consumption Prediction Using Machine Learning

## 📌 Project Overview
This project leverages **machine learning** to predict key trends in the **consumer electronics industry**, specifically:
- **Smartphone Sales (Millions) 📱**
- **5G Penetration Rate (%) 📡**
- **Gaming Console Adoption 🎮**

By analyzing **global tech gadget data**, we provide insights for **businesses, telecom providers, and gaming companies** to make **data-driven decisions** on product demand and market trends.

---

## 📊 Dataset Overview
The dataset contains information on:
- **Country & Year**
- **Smartphone Sales, Laptop Shipments**
- **Gaming Console Adoption & Smartwatch Penetration**
- **Consumer Spending on Gadgets ($)**
- **E-Waste Generated (Metric Tons)**
- **5G Penetration Rate (%)**

We apply **feature engineering** to derive additional insights such as:
- **Yearly Growth Rates** for Smartphone Sales & 5G Penetration
- **Spending per Capita on Gadgets**
- **E-Waste per Device Sold**

---

## 🚀 Machine Learning Models Used
### **Regression Models (For Numerical Predictions)**
✅ **Smartphone Sales Prediction** → **Ridge Regression**  
✅ **5G Penetration Rate Prediction** → **XGBoost Regressor**  

### **Classification Model (For Categorical Predictions)**
✅ **Gaming Console Adoption (High or Low)** → **Random Forest Classifier**  

---

## 🔍 Model Evaluation Metrics
We use standard evaluation metrics:
- **Regression:** MAE, RMSE, R² Score
- **Classification:** Accuracy, Precision, Recall, F1-score

---

## 📂 Project Structure
```
📁 Global_Tech_Gadget_Prediction
│-- 📄 dataset.csv  (Tech gadget consumption dataset)
│-- 📄 model.py     (Machine learning model implementation)
│-- 📄 app.py       (Streamlit web app for deployment)
│-- 📄 requirements.txt (Dependencies)
│-- 📄 README.md    (Project documentation)
```

---

## 💡 Future Enhancements
🔹 **Real-time data integration** for dynamic predictions  
🔹 **Web-based dashboard using Streamlit**  
🔹 **Hyperparameter tuning for improved accuracy**  

---

## 🛠 Installation & Setup
1️⃣ Clone the repository:
```bash
git clone https://github.com/your-username/Global_Tech_Gadget_Prediction.git
cd Global_Tech_Gadget_Prediction
```
2️⃣ Install dependencies:
```bash
pip install -r requirements.txt
```
3️⃣ Run the model:
```bash
python model.py
```
4️⃣ (Optional) Launch the web app:
```bash
streamlit run app.py
```

---

## 🤝 Contributing
Want to improve this project? Feel free to **fork the repo**, create a branch, and submit a PR!

---

## 📄 License
This project is licensed under the **MIT License**.

---

## 📬 Contact
For any queries, reach out on [LinkedIn](https://www.linkedin.com/in/carmelrajc/) or [GitHub](https://github.com/Carmelraj007).

