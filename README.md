# AI-PoweredLeadScoringandSegmentation
# AI-Powered Lead Scoring Dashboard

This project is an end-to-end AI system for scoring, segmenting, and engaging sales leads using machine learning and generative AI. It includes:

- **Lead conversion prediction** using Random Forest
- **Lead segmentation** using KMeans clustering
- **Interactive Streamlit dashboard** for insights
- **Personalized message generation** using Google Gemini (Generative AI)



---

## 🚀 Features

### ✅ Predictive Modeling (Random Forest)
- Classifies leads based on likelihood to convert (`converted`)
- Uses features like `demo_given`, `contacted`, `employee_count`, etc.

### ✅ Segmentation (KMeans)
- Clusters leads based on scaled feature similarity
- Identifies conversion patterns in high-performing clusters

### ✅ Insightful Visualizations
- Feature values, cluster-wise statistics
- Lead-specific prediction summaries

### ✅ Personalized Outreach
- Uses Google Gemini API (Generative AI) to draft short, targeted messages for each lead
- Messages are generated based on cluster behavior and predicted score

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/lead-scoring-dashboard.git
cd lead-scoring-dashboard
