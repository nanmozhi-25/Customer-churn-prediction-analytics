# 📊 AI-Powered Customer Churn Prediction & Analytics

An end-to-end Telecom Customer Churn Prediction and Analytics Platform built using React, Node.js, Python, FastAPI, MongoDB, and Power BI.

The application helps telecom companies identify customers who are likely to churn by combining Machine Learning, interactive dashboards, customer management, analytics, report generation, and business intelligence.

---

# 🚀 Features

- 🔐 User Authentication
- 👥 Customer Management
- 🤖 AI-based Customer Churn Prediction
- 📂 Bulk CSV Prediction
- 📈 Interactive Dashboard
- 📊 Customer Analytics
- 📄 PDF & CSV Report Generation
- 📉 Power BI Dashboard Integration
- 💻 Modern Responsive User Interface

---

# 🛠️ Tech Stack

## Frontend

- React.js
- Vite
- JavaScript
- HTML5
- CSS3
- Recharts
- Lucide Icons

## Backend

- Node.js
- Express.js

## Machine Learning

- Python
- FastAPI
- Scikit-learn

## Database

- MongoDB

## Business Intelligence

- Microsoft Power BI

---

# 📁 Project Structure

```
Customer-Churn-Prediction
│
├── client/                          # React Frontend (Vite)
│   ├── src/
│   │   ├── components/              # Reusable UI (Sidebar, Navbar, Loader)
│   │   ├── context/                 # Auth Context
│   │   ├── pages/                   # Views (Dashboard, Prediction, Customers)
│   │   ├── index.css                # Aurora Theme Tokens
│   │   └── App.jsx                  # Guards and Routes
│
├── server/                          # Node.js + Express Backend API
│   ├── config/                      # Mongoose & Fallback Local DB Configs
│   ├── controllers/                 # Business logic
│   ├── middleware/                  # JWT auth & Multer CSV configs
│   ├── models/                      # MongoDB Schemas
│   ├── uploads/                     # Temp file storage & local DB JSON file
│   ├── utils/                       # Prediction fallback engines
│   └── server.js                    # Entry point (Port 5000)
│
├── ml-service/                      # Python FastAPI ML Server
│   ├── dataset/                     # Local train database copy
│   ├── saved_model/                 # Pickled Scikit-Learn classifiers
│   ├── train.py                     # Synthetic generation & Random Forest trainer
│   ├── app.py                       # REST predicting service (Port 8000)
│   └── requirements.txt
│
└── powerbi/
    └── README.md                    # Business DAX & chart config guide
```

---

# ⚙️ Installation

## 1. Clone Repository

```bash
git clone https://github.com/nanmozhi-25/Customer-churn-prediction-analytics.git
```

```bash
cd Customer-churn-prediction-analytics
```

---

## 2. Install Backend

### 💻 Installation & Startup

#### Step 1: Run the Backend Server
1. Navigate to the server folder:
   ```bash
   cd server
   ```
2. Install npm dependencies:
   ```bash
   npm install
   ```
3. Start the Express API:
   ```bash
   npm start
   ```
   *Note: If MongoDB is offline, the API automatically mounts `server/uploads/local_db.json` to store user and subscriber details.*

---

#### Step 2: Run the ML Service (Optional)
If Python is installed on your local environment:
1. Navigate to the ml-service folder:
   ```bash
   cd ml-service
   ```
2. Install Python packages:
   ```bash
   pip install -r requirements.txt
   ```
3. Generate the model and run the service:
   ```bash
   python train.py
   python app.py
   ```
   *Note: If the FastAPI service is not running, the Node.js API automatically routes queries through a built-in smart heuristic rules engine to prevent prediction errors.*

---

#### Step 3: Run the React Client
1. Navigate to the client folder:
   ```bash
   cd client
   ```
2. Install packages:
   ```bash
   npm install
   ```
3. Boot the development server:
   ```bash
   npm run dev
   ```
4. Click the link shown in terminal (typically `http://localhost:5173`) to launch the workspace in your browser.

---


# 📊 Modules

## 🏠 Dashboard

- Total Subscribers
- Active Subscribers
- Churn Rate
- Revenue Metrics
- Interactive Charts

---

## 👥 Customers

- Customer Information
- Customer List
- Customer Management

---

## 🤖 AI Predict

- Single Customer Prediction
- Bulk CSV Prediction
- Churn Risk Estimation

---

## 📈 Analytics

- Customer Analytics
- Business Insights
- Interactive Visualizations

---

## 📄 Reports

- Executive Reports
- PDF Generation
- CSV Export

---

## 📉 Power BI

- Business Dashboard
- KPI Visualization
- Customer Insights

---

# 💡 Workflow

```
Customer Data
      │
      ▼
React Frontend
      │
      ▼
Node.js API
      │
      ▼
Python ML Model
      │
      ▼
Prediction Result
      │
      ▼
Dashboard & Reports
```

---

# 📷 Application Preview

screenshots/
│
├── login.png
├── dashboard.png
├── customers.png
├── prediction.png
├── analytics.png
├── reports.png
└── powerbi.png
```

---

# 🎯 Future Improvements

- Docker Deployment
- Cloud Hosting
- Explainable AI
- Email Notifications
- Mobile Application
- Real-time Analytics
- Multi-user Role Management

## ⚡ Smart Heuristic Fallback Predictor
In the absence of a running Python FastAPI microservice, the system uses a smart heuristic scoring algorithm based on historical Telco churn patterns:
- **Contracts**: Month-to-month contracts trigger high churn risks (+35%), while Two-year contracts decrease risk (-15%).
- **Tenure**: Early customers (<6 months) carry a +20% risk driver.
- **Billing Methods**: Manual checks and Electronic Billing add +12% risk.
- **Missing Features**: Accounts lacking Tech Support or Online Security incur additional churn penalties (+8% each).
This guarantees that prediction forms and bulk imports remain 100% operational for evaluation and demos.



## 📸 Application Screenshots

### Dashboard

![Dashboard](screenshots/dashboard.png)

### AI Prediction

![Prediction](screenshots/prediction.png)

### Analytics

![Analytics](screenshots/analytics.png)

### Reports

![Reports](screenshots/reports.png)

---

# 👨‍💻 Author

**Nanmozhi Tamilarasan**


GitHub:
https://github.com/nanmozhi-25

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.