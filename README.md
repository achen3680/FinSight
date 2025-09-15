# Transaction Classifier with PyTorch + MLflow  

An end-to-end ML project to practice **PyTorch modeling** and **MLflow experiment tracking**, focusing on expense classification in a finance context.  

---

## ✨ Features
- 🔍 **Expense Classification**  
  Train a PyTorch model to automatically categorize financial transactions (e.g., Dining, Travel, Groceries).  

- 📊 **Experiment Tracking with MLflow**  
  Log hyperparameters, metrics, and model artifacts across runs. Compare experiments and register best models.  

- 🛡️ **Governance Checks**  
  Add basic audit logging, per-category accuracy reporting, and drift detection for incoming transactions.  

- ⚡ **Deployment Ready**  
  Containerized with Docker + FastAPI endpoint, CI/CD integration (GitHub Actions).  

---

## 🧱 Tech Stack
- **ML:** PyTorch, MLflow  
- **Backend:** Python, FastAPI  
- **Infra/DevOps:** Docker, GitHub Actions CI/CD, Azure App Service (optional)  
- **Data:** Public transaction/expenses dataset (mocked initially)  

---

## 🚀 Setup Instructions
```bash
# clone the repo
git clone https://github.com/achen3680/finsight.git
cd finsight

# create virtual environment
python -m venv venv
source venv/bin/activate  # mac/linux
venv\Scripts\activate     # windows

# install dependencies
pip install -r requirements.txt

# run training script (logs to MLflow)
python train.py

# run FastAPI app for inference
uvicorn main:app --reload
```
## 📈 Roadmap

- Baseline PyTorch classifier (MLP)  
- MLflow experiment tracking + registry  
- Governance metrics (bias checks, drift monitoring)  
- Dockerize and deploy to Azure App Service  
- Optional: Streamlit dashboard for interactive demo  

 

├── data/              # sample transactions dataset
├── notebooks/         # exploration + baseline models
├── src/               # training + inference code
├── requirements.txt   # dependencies
├── train.py           # main training script
├── main.py            # FastAPI inference server
└── README.md





