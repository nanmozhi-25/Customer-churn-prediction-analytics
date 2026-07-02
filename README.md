# 🚀 Aurora AI – Telecom Customer Churn Prediction & Analytics Platform

Aurora AI is an end-to-end Customer Churn Prediction platform that combines Machine Learning, React, Node.js, FastAPI, and Power BI to help telecom companies identify customers who are likely to churn. The platform provides real-time predictions, interactive dashboards, bulk customer analysis, and business intelligence reports.

---

## 📌 Project Overview

Customer churn is one of the biggest challenges in the telecom industry. Aurora AI predicts whether a customer is likely to leave the service by analyzing customer attributes and historical data. The system enables businesses to take proactive actions to improve customer retention.

---

# ✨ Features

- 🔐 Secure User Authentication (JWT)
- 🤖 Real-Time Customer Churn Prediction
- 📂 Bulk CSV Upload & Prediction
- 📊 Interactive Dashboard
- 📈 Power BI Business Intelligence Reports
- 📉 Customer Analytics & Visualizations
- 🧠 Machine Learning Prediction Engine
- ⚡ Smart Heuristic Fallback Prediction
- 💾 MongoDB Database with Local JSON Fallback
- 📱 Responsive Modern UI

---

# 🛠️ Tech Stack

## Frontend
- React.js (Vite)
- HTML5
- CSS3
- JavaScript
- Recharts
- Lucide Icons

## Backend
- Node.js
- Express.js
- JWT Authentication
- Multer

## Machine Learning
- Python
- FastAPI
- Scikit-Learn
- Pandas
- NumPy

## Database
- MongoDB
- Mongoose
- Local JSON Fallback

## Business Intelligence
- Power BI

---

# 📂 Project Structure

```
Customer-Churn-Prediction/
│
├── client/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── uploads/
│   └── server.js
│
├── ml-service/
│   ├── dataset/
│   ├── saved_model/
│   ├── train.py
│   ├── app.py
│   └── requirements.txt
│
├── powerbi/
│
├── README.md
└── package.json
```

---

# 🚀 Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/nanmozhi-25/Customer-churn-prediction-analytics.git
```

---

## 2️⃣ Open Project

```bash
cd Customer-churn-prediction-analytics
```

---

## 3️⃣ Install Backend

```bash
cd server
npm install
```

Run Backend

```bash
npm start
```

or

```bash
npm run dev
```

---

## 4️⃣ Install Frontend

Open a new terminal.

```bash
cd client
npm install
```

Run Frontend

```bash
npm run dev
```

---

## 5️⃣ Machine Learning Service (Optional)

```bash
cd ml-service
pip install -r requirements.txt
python train.py
python app.py
```

---

# 📊 Dashboard Features

- Customer Churn Rate
- Customer Segmentation
- Monthly Revenue Analysis
- Churn Distribution
- Contract Type Analysis
- Payment Method Analysis
- Business KPIs
- Interactive Power BI Reports

---

# 🧠 Machine Learning Model

The prediction engine is built using **Random Forest Classifier** trained on Telecom Customer Churn data.

### Model Workflow

- Data Preprocessing
- Feature Engineering
- Model Training
- Model Evaluation
- Prediction API
- Real-Time Prediction

---

# ⚡ Smart Heuristic Prediction

If the Python ML service is unavailable, Aurora AI automatically switches to a built-in heuristic prediction engine based on:

- Contract Type
- Customer Tenure
- Payment Method
- Tech Support
- Online Security
- Internet Service

This ensures uninterrupted prediction during demonstrations.

---

# 📸 Screenshots

Create a folder named:

```
screenshots
```

Add screenshots such as:

```
screenshots/login.png
screenshots/dashboard.png
screenshots/prediction.png
screenshots/powerbi.png
```

Then update this section:

```markdown
## Login

![Login](screenshots/login.png)

## Dashboard

![Dashboard](screenshots/dashboard.png)

## Prediction

![Prediction](screenshots/prediction.png)

## Power BI Dashboard

![Power BI](screenshots/powerbi.png)
```

---

# 🔮 Future Enhancements

- Docker Deployment
- Cloud Hosting
- Explainable AI (SHAP)
- Email Notifications
- Multi-user Roles
- Mobile Application
- Real-Time Streaming Analytics

---

# 👩‍💻 Author

**Nanmozhi Tamilarasan**


💡 Interests:
- Artificial Intelligence
- Machine Learning
- Deep Learning
- Data Science
- Power BI
- Full Stack Development

**GitHub:** https://github.com/nanmozhi-25

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

It helps others discover the project and supports future development.