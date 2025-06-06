# FinSight

**AI-powered personal finance dashboard**  
Auto-categorize your expenses, forecast future spend, and ask natural language questions about your finances - all in one place.

---

## ✨ Features

- 🔍 **Smart Expense Categorization**  
  Automatically categorize transactions using ML models or embeddings

- 📈 **Cash Flow Forecasting**  
  Predict upcoming income and expenses with time-series modeling

- 🧠 **LLM-Powered Finance Chat**  
  Ask questions like “How much did I spend on dining last month?” using natural language

- 📊 **Personalized Spending Insights**
  Surface trends like “Your rideshare spend is up 22% this week”

- 🔁 **Recurring Subscription Detection**  - Nice to Have
  Identify and manage monthly charges — detect unused or new subscriptions

---

## 🧱 Tech Stack

- **Backend:** Python, FastAPI
- **Frontend:** Streamlit or React (WIP)
- **ML:** scikit-learn, OpenAI Embeddings, Prophet (or ARIMA)
- **Integrations:** Plaid or Stripe (mocked initially), OpenAI API
- **Deployment:** GCP / Streamlit Cloud / Vercel (based on stack)

---

## 🧪 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/achen3680/finsight.git
cd finsight

# Create virtual environment
python -m venv venv
source venv/bin/activate  # on Mac/Linux
venv\Scripts\activate     # on Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py  # or uvicorn main:app --reload (if using FastAPI)
```
