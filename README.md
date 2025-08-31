# Human_Eye_Disease_Prediction_with_react
# 🧠 Human Eye Disease Prediction (OCT)

This project is a **full-stack web app** for **Retinal OCT (Optical Coherence Tomography) image analysis**.  
It uses a **FastAPI backend** (TensorFlow model) and a **React + Tailwind frontend**.

---

## 🚀 Features
- Upload OCT images and get **disease predictions**:
  - CNV (Choroidal Neovascularization)
  - DME (Diabetic Macular Edema)
  - Drusen (Early AMD)
  - Normal Retina
- Backend powered by **TensorFlow + FastAPI**
- Frontend built with **React + Tailwind CSS**
- Shows **confidence scores** with a bar chart (Recharts)
- Provides **medical recommendations** for each condition

---

## ⚙️ Backend Setup (FastAPI + TensorFlow)

### 1. Create & activate virtual environment
```bash
python -m venv venv
# On Windows
venv\Scripts\activate
# On Linux/Mac
source venv/bin/activate

2. Install dependencies
pip install fastapi uvicorn tensorflow python-multipart

3. Run the server
uvicorn main:app --reload


3. Run development server
npm run dev   # for Vite
# or
npm start     # for Create React App
