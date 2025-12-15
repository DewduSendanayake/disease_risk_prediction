

<h1 align="center">🩺 Disease Risk Prediction System</h1>

<p align="center">
  <strong>An AI-powered full-stack application that predicts disease risk using advanced machine learning</strong>
</p>
<p align="center">
  <img src="https://img.shields.io/badge/🏥-Disease%20Risk%20Prediction-4F46E5?style=for-the-badge&labelColor=white" alt="Disease Risk Prediction"/>
</p>
---

## 🌟 Overview

**Disease Risk Prediction System** is a comprehensive full-stack machine learning application that analyzes **23 different health and lifestyle parameters** to predict the probability of disease occurrence. Built with modern web technologies and powered by a **LightGBM** classifier with advanced preprocessing pipelines.

> ⚕️ **Medical Disclaimer**: This application is for **educational and research purposes only**. It should not be used as a substitute for professional medical advice, diagnosis, or treatment. Always consult with qualified healthcare professionals for medical decisions.

---

## ✨ Features

<table>
<tr>
<td width="50%">

### 🤖 Machine Learning
- **LightGBM Classifier** with hyperparameter tuning
- **PCA Dimensionality Reduction** (90% variance retention)
- **KNN Imputation** for handling missing values
- **Smart Feature Engineering** (BMI categories, age groups, HOMA-IR)

</td>
<td width="50%">

### 🎨 User Interface
- **Modern React 19** with beautiful Tailwind CSS styling
- **Multi-Step Form Wizard** with progress indicator
- **Interactive Risk Gauge** visualization
- **Responsive Design** for all devices

</td>
</tr>
<tr>
<td>

### ⚡ Performance
- **Vite-powered** lightning-fast development
- **Optimized Model Loading** on server startup
- **Docker-ready** for containerized deployment
- **Production-ready** with Gunicorn WSGI server

</td>
<td>

### 🛡️ Robust Validation
- **Client-side** and **server-side** validation
- **Comprehensive error handling**
- **Field synchronization** between frontend & backend
- **CORS** properly configured for security

</td>
</tr>
</table>

---

## 🏗️ System Architecture

```
┌─────────────────────────────────────────────────────────────────────────┐
│                        Disease Risk Prediction System                   │
├─────────────────────────────────────────────────────────────────────────┤
│                                                                         │
│  ┌─────────────────┐    ┌─────────────────┐    ┌─────────────────┐      │
│  │   🎨 Frontend   │    │   🔧 Backend   │    │ 🧠 ML Pipeline │      │
│  │   React + Vite  │◄──►│     Flask       │◄──►│    LightGBM     │      │
│  │                 │    │                 │    │                 │      │
│  │ ▪ Multi-step UI │    │ ▪ REST API      │    │ ▪ KNN Imputer   │      │
│  │ ▪ Form Wizard   │    │ ▪ CORS Handler  │    │ ▪ StandardScaler│      │
│  │ ▪ Risk Gauge    │    │ ▪ Data Validator│    │ ▪ OneHotEncoder │      │
│  │ ▪ Tailwind CSS  │    │ ▪ Model Loader  │    │ ▪ PCA Transform │      │
│  └─────────────────┘    └─────────────────┘    └─────────────────┘      │
│                                                                         │
│ 📱 Responsive          🐳 Docker Ready          📊 29 PCA Components   │
│                                                                         │
└─────────────────────────────────────────────────────────────────────────┘
```

---

## 🔧 Technology Stack

<table>
<tr>
<th>Layer</th>
<th>Technology</th>
<th>Purpose</th>
</tr>
<tr>
<td rowspan="4"><strong>🎨 Frontend</strong></td>
<td><img src="https://img.shields.io/badge/React-19.1.1-61DAFB?logo=react&logoColor=white" alt="React"/></td>
<td>Modern UI framework with hooks</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/Vite-7.1.7-646CFF?logo=vite&logoColor=white" alt="Vite"/></td>
<td>Lightning-fast build tool & dev server</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/Tailwind-4.1.14-06B6D4?logo=tailwindcss&logoColor=white" alt="Tailwind"/></td>
<td>Utility-first CSS framework</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/Lucide-Icons-F56565" alt="Lucide"/></td>
<td>Beautiful, consistent icon library</td>
</tr>
<tr>
<td rowspan="3"><strong>🔧 Backend</strong></td>
<td><img src="https://img.shields.io/badge/Flask-Latest-000000?logo=flask&logoColor=white" alt="Flask"/></td>
<td>Lightweight Python web framework</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/Flask--CORS-Enabled-000000" alt="Flask-CORS"/></td>
<td>Cross-origin resource sharing</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/Gunicorn-WSGI-499848?logo=gunicorn&logoColor=white" alt="Gunicorn"/></td>
<td>Production-grade WSGI server</td>
</tr>
<tr>
<td rowspan="5"><strong>🧠 ML/AI</strong></td>
<td><img src="https://img.shields.io/badge/LightGBM-Classifier-9ACD32" alt="LightGBM"/></td>
<td>Gradient boosting framework</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/scikit--learn-Preprocessing-F7931E?logo=scikitlearn&logoColor=white" alt="scikit-learn"/></td>
<td>ML preprocessing & utilities</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/pandas-Data-150458?logo=pandas&logoColor=white" alt="pandas"/></td>
<td>Data manipulation & analysis</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/NumPy-Numerical-013243?logo=numpy&logoColor=white" alt="NumPy"/></td>
<td>Numerical computing</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/joblib-Serialization-FF6B6B" alt="joblib"/></td>
<td>Model serialization & loading</td>
</tr>
<tr>
<td rowspan="2"><strong>🚀 DevOps</strong></td>
<td><img src="https://img.shields.io/badge/Docker-Containerization-2496ED?logo=docker&logoColor=white" alt="Docker"/></td>
<td>Container deployment</td>
</tr>
<tr>
<td><img src="https://img.shields.io/badge/HuggingFace-Spaces-FFD21E?logo=huggingface" alt="HuggingFace"/></td>
<td>Cloud deployment platform</td>
</tr>
</table>

---

## 📊 Input Parameters

The model analyzes **23 health and lifestyle features** organized into 5 categories:

### 👤 Personal Information
| Parameter | Type | Range | Description |
|-----------|------|-------|-------------|
| Gender | Select | Male/Female | Biological gender |
| Age | Number | 18-100 years | Age in full years |
| Income | Number | $0-$500,000 | Annual gross income |
| Marital Status | Select | Single/Married/Divorced | Legal marital status |
| Work Hours | Number | 0-80 hrs/week | Weekly work hours |

### 💓 Health Vitals
| Parameter | Type | Range | Description |
|-----------|------|-------|-------------|
| Blood Pressure | Number | 90-200 mmHg | Systolic pressure |
| Heart Rate | Number | 40-150 BPM | Resting heart rate |
| Glucose | Number | 60-400 mg/dL | Blood glucose level |
| Insulin | Number | 1-50 μU/mL | Fasting insulin |
| Cholesterol | Number | 100-400 mg/dL | Total cholesterol |
| Mental Health Score | Number | 1-100 | Psychological wellbeing |

### 📏 Physical Measurements
| Parameter | Type | Range | Description |
|-----------|------|-------|-------------|
| BMI | Number | 15-50 | Body Mass Index |
| Waist Size | Number | 50-150 cm | Waist circumference |
| Physical Activity | Number | 0-40 hrs/week | Exercise duration |

### 🍎 Lifestyle & Diet
| Parameter | Type | Options | Description |
|-----------|------|---------|-------------|
| Calorie Intake | Number | 1000-5000 | Daily calories |
| Sugar Intake | Number | 0-200 g | Daily sugar consumption |
| Water Intake | Number | 0-10 L | Daily water intake |
| Dietary Habits | Select | Balanced, Vegetarian, Vegan, Keto, etc. | Eating pattern |
| Exercise Type | Select | Cardio, Strength, Mixed | Primary exercise |

### 🚭 Habits & Stress
| Parameter | Type | Options | Description |
|-----------|------|---------|-------------|
| Smoking Status | Select | Never, Former, Current, Heavy | Tobacco use |
| Alcohol Consumption | Select | None, Light, Moderate, Heavy | Alcohol intake |
| Caffeine Intake | Select | None, Low, Medium, High | Caffeine consumption |
| Stress Level | Select | Low, Medium, High | Perceived stress |

---

## 🤖 Machine Learning Pipeline

The prediction system uses a sophisticated **6-stage ML pipeline**:

```python
📥 Raw Input (23 features)
        │
        ▼
┌───────────────────────────────────────┐
│ Stage 1: Sanitization & Coercion      │
│  • Convert data types                 │
│  • Handle unknown categories          │
│  • Map user inputs to model features  │
└───────────────────────────────────────┘
        │
        ▼
┌───────────────────────────────────────┐
│ Stage 2: KNN Imputation               │
│  • Handle missing values              │
│  • 5-neighbor imputation              │
│  • Columns: blood_pressure, heart_rate│
│             insulin, income           │
└───────────────────────────────────────┘
        │
        ▼
┌───────────────────────────────────────┐
│ Stage 3: Feature Engineering          │
│  • BMI categorization (4 groups)      │
│  • Age grouping (Young→Senior)        │
│  • HOMA-IR: (glucose × insulin) / 405 │
│  • Diabetes risk flagging             │
└───────────────────────────────────────┘
        │
        ▼
┌───────────────────────────────────────┐
│ Stage 4: Scaling & Encoding           │
│  • StandardScaler (18 numerical)      │
│  • OneHotEncoder (15 categorical)     │
│  • OrdinalEncoder (2 ordinal)         │
└───────────────────────────────────────┘
        │
        ▼
┌───────────────────────────────────────┐
│ Stage 5: PCA Transformation           │
│  • 90% variance retention             │
│  • Dimensionality reduction           │
│  • Output: 29 principal components    │
└───────────────────────────────────────┘
        │
        ▼
┌───────────────────────────────────────┐
│ Stage 6: LightGBM Prediction          │
│  • n_estimators: 400                  │
│  • learning_rate: 0.1                 │
│  • max_depth: 12                      │
│  • num_leaves: 70                     │
│  • min_child_samples: 20              │
└───────────────────────────────────────┘
        │
        ▼
📤 Prediction (Disease / No Disease + Probability)
```

### 🔬 Feature Engineering Details

```python
# BMI Categorization
BMI_BINS = [0, 18.5, 25.0, 30.0, ∞]
BMI_LABELS = ['Underweight', 'Normal', 'Overweight', 'Obese']

# Age Grouping
AGE_BINS = [18, 26, 41, 61, ∞]
AGE_LABELS = ['Young', 'Adult', 'Middle-aged', 'Senior']

# HOMA-IR (Insulin Resistance Score)
HOMA_IR = (Glucose × Insulin) / 405

# Diabetes Risk Flag
diabetes_risk = 'High Risk' if Glucose > 125 else 'Normal/Pre-Risk'
```

---

## 🚀 Quick Start

### 📋 Prerequisites

- **Node.js** 18+ and npm
- **Python** 3.11+
- **Git**

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/dulhara79/disease_risk_prediction.git
cd disease_risk_prediction
```

### 2️⃣ Backend Setup

```bash
# Navigate to server directory
cd server

# Create virtual environment
python -m venv .venv

# Activate virtual environment
# 🪟 Windows:
.venv\Scripts\activate
# 🍎 macOS/Linux:
source .venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Start the Flask server
python app.py
```

🟢 **Backend running at:** `http://127.0.0.1:8000`

### 3️⃣ Frontend Setup

```bash
# Navigate to client directory (new terminal)
cd client

# Install dependencies
npm install

# Start development server
npm run dev
```

🟢 **Frontend running at:** `http://localhost:5173`

### 4️⃣ Access the Application

Open your browser and navigate to `http://localhost:5173` 🎉

---

## 🐳 Docker Deployment

```bash
# Navigate to server directory
cd server

# Build the Docker image
docker build -t disease-risk-api .

# Run the container
docker run -p 8000:8000 disease-risk-api
```

---

## 📡 API Reference

### 🔍 Health Check

```http
GET /
```

**Response:**
```json
{
    "status": "API is operational",
    "version": "1.0"
}
```

### 🔮 Predict Disease Risk

```http
POST /predict
Content-Type: application/json
```

**Request Body:**
```json
{
    "gender": "Male",
    "age": 45,
    "blood_pressure": 135,
    "heart_rate": 82,
    "glucose": 110,
    "insulin": 12.5,
    "cholesterol": 210.5,
    "bmi": 28.5,
    "physical_activity": 5,
    "waist_size": 95.0,
    "calorie_intake": 2200,
    "mental_health_score": 78,
    "sugar_intake": 55.0,
    "smoking_status": "Former Smoker",
    "alcohol_consumption": "Moderate",
    "stress_level": "Medium",
    "income": 65000.0,
    "marital_status": "Married",
    "exercise_type": "Cardio",
    "dietary_habits": "Balanced",
    "caffeine_intake": "2 cups daily",
    "water_intake": 2.5,
    "work_hours": 45
}
```

**Success Response (200):**
```json
{
    "status": "success",
    "prediction_label": "Disease",
    "probability_of_disease": 0.7839
}
```

**Error Response (400):**
```json
{
    "error": "Missing required features in input data",
    "missing": ["age", "bmi"]
}
```

---

## 🧪 Testing

### Backend Tests

```bash
cd server

# Test API endpoint
python tests/test_api.py

# Test full prediction pipeline
python tests/test_full_prediction.py

# Test preprocessing only
python tests/test_preprocess.py

# Debug utilities
python tests/debug_scaler.py
python tests/debug_onehot.py
```

### Frontend Tests

```bash
cd client

# Run ESLint
npm run lint

# Validate field synchronization
node src/validate_fields.js
```

---

## ⚙️ Configuration

### Backend (`server/config.py`)

```python
# Model paths
MODELS_DIR = Path("models")
FINAL_MODEL_PATH = MODELS_DIR/'final_diseased_prediction_model_lgbm_tuned.joblib'

# Feature columns
USER_INPUT_COLUMNS = [
    'gender', 'age', 'blood_pressure', 'heart_rate', ...
]

# Preprocessing parameters
BMI_BINS = [0, 18.5, 25.0, 30.0, float('inf')]
AGE_BINS = [18, 26, 41, 61, float('inf')]
HOMA_IR_DIVISOR = 405.0
GLUCOSE_RISK_THRESHOLD = 125
```

### Frontend (`client/src/App.jsx`)

```javascript
// API endpoint
const API_ENDPOINT = "https://dulharakaushalya-disease-risk-backend.hf.space/run/predict";

// Input order (must match backend)
const INPUT_ORDER = [
    "gender", "age", "blood_pressure", ...
];
```

---

## 📈 Model Performance

| Metric | Value |
|--------|-------|
| **Algorithm** | LightGBM Classifier |
| **Input Features** | 23 raw → 29 PCA components |
| **Training Method** | RandomizedSearchCV (3-fold CV) |
| **Class Balancing** | SMOTE |
| **Scoring Metric** | ROC-AUC |

### LightGBM Hyperparameters

```python
LGBMClassifier(
    n_estimators=400,
    learning_rate=0.1,
    max_depth=12,
    num_leaves=70,
    min_child_samples=20
)
```

---

## 🛠️ Development

### Development Mode

```bash
# Backend (with debug mode)
cd server
python app.py  # Debug mode auto-enabled

# Frontend (with hot reload)
cd client
npm run dev
```

### Production Build

```bash
# Frontend production build
cd client
npm run build

# Backend with Gunicorn
pip install gunicorn
gunicorn -w 4 -b 0.0.0.0:8000 app:app
```

---

## 🚨 Troubleshooting

<details>
<summary><strong>❌ Model Loading Errors</strong></summary>

Ensure all model files exist:
```bash
ls server/models/
# Should contain:
# - final_diseased_prediction_model_lgbm_tuned.joblib
# - standard_scaler.joblib
# - one_hot_encoder.joblib
# - ordinal_encoder.joblib
# - knn_imputer.joblib
# - pca_90_variance.joblib
# - label_encoder.joblib
# - final_features_list.json
```
</details>

<details>
<summary><strong>❌ CORS Errors</strong></summary>

Check CORS configuration in `server/app.py`:
```python
CORS(app, resources={r"/predict": {"origins": [
    "http://localhost:5173",  # Local development
    "https://disease-risk-prediction-frontend.vercel.app"  # Production
]}})
```
</details>

<details>
<summary><strong>❌ Feature Mismatch</strong></summary>

Validate field synchronization:
```bash
cd client/src && node validate_fields.js
```
</details>

<details>
<summary><strong>❌ Port Conflicts</strong></summary>

- **Frontend**: Modify `vite.config.js`
- **Backend**: Modify port in `app.py`
</details>

---

## 🌐 Deployment

### Currently Deployed

| Service | Platform | URL |
|---------|----------|-----|
| 🔧 Backend | HuggingFace Spaces | [dulharakaushalya-disease-risk-backend.hf.space](https://dulharakaushalya-disease-risk-backend.hf.space) |
| 🎨 Frontend | Vercel | [disease-risk-prediction-frontend.vercel.app](https://disease-risk-prediction-frontend.vercel.app) |

---


---

## 👩‍💻 Authors

<p align="center">
  <strong>Dewdu Sendanayake</strong><br>
  <strong>Dulhara Kaushalya</strong><br>
  <strong>Senuvi Layathma</strong><br>
  <strong>Uvindu Seneviratne</strong><br>
</p>

---

<div align="center">

<p align="center">
  <a href="#-features"><img src="https://img.shields.io/badge/✨-Features-blue?style=flat-square" alt="Features"/></a>
  <a href="#-quick-start"><img src="https://img.shields.io/badge/🚀-Quick%20Start-green?style=flat-square" alt="Quick Start"/></a>
  <a href="#-api-reference"><img src="https://img.shields.io/badge/📡-API-orange?style=flat-square" alt="API"/></a>
  <a href="#-machine-learning"><img src="https://img.shields.io/badge/🤖-ML%20Pipeline-purple?style=flat-square" alt="ML Pipeline"/></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.11+-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/React-19.1.1-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React"/>
  <img src="https://img.shields.io/badge/Flask-Latest-000000?style=for-the-badge&logo=flask&logoColor=white" alt="Flask"/>
  <img src="https://img.shields.io/badge/LightGBM-ML%20Model-9ACD32?style=for-the-badge&logo=lightgbm&logoColor=white" alt="LightGBM"/>
  <img src="https://img.shields.io/badge/TailwindCSS-4.1.14-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white" alt="Tailwind"/>
  <img src="https://img.shields.io/badge/Vite-7.1.7-646CFF?style=for-the-badge&logo=vite&logoColor=white" alt="Vite"/>
</p>

<p align="center">
  <img src="https://img.shields.io/github/license/dulhara79/disease_risk_prediction?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/badge/Deployed-HuggingFace%20Spaces-FFD21E?style=flat-square&logo=huggingface" alt="Deployed"/>
  <img src="https://img.shields.io/badge/Containerized-Docker%20Ready-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"/>
</p>
**Made with ❤️ for Data Mining & Healthcare AI**

---

</div>
