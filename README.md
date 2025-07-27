# AI-PoweredLeadScoringandSegmentation
# AI-Powered Lead Scoring Dashboard

This project is an end-to-end AI system for scoring, segmenting, and engaging sales leads using machine learning and generative AI. It includes:

- **Lead conversion prediction** using Random Forest
- **Lead segmentation** using KMeans clustering
- **Interactive Streamlit dashboard** for insights
- **Personalized message generation** using Google Gemini (Generative AI)



---

## Features

### Predictive Modeling (Random Forest)
- Classifies leads based on likelihood to convert (`converted`)
- Uses features like `demo_given`, `contacted`, `employee_count`, etc.

### Segmentation (KMeans)
- Clusters leads based on scaled feature similarity
- Identifies conversion patterns in high-performing clusters

### Insightful Visualizations
- Feature values, cluster-wise statistics
- Lead-specific prediction summaries

### Personalized Outreach
- Uses Google Gemini API (Generative AI) to draft short, targeted messages for each lead
- Messages are generated based on cluster behavior and predicted score

---

## Installation

### 1. Clone the Repository

```bash
git clone "githubrepo"
cd "githubrepo"

### 2. Set Up Environment
python -m venv venv
source venv/bin/activate      # On Windows: venv\Scripts\activate
pip install -r requirements.txt

### 3. Add Google API Key
Add your Google API key as an environment variable:
```bash
export GOOGLE_API_KEY='your-api-key'  # For Linux/Mac
set GOOGLE_API_KEY=your-api-key       # For Windows CMD

### 4. Running the App
```bash
streamlit run app.py
If you're using Colab or Jupyter, you can expose the Streamlit app via Ngrok:

python
from pyngrok import ngrok
public_url = ngrok.connect(8501)
print(f"App running at {public_url}")

Medium : https://medium.com/@priyaskulkarni/ai-powered-lead-scoring-and-segmentation-a-complete-end-to-end-solution-578c9e1c769a
