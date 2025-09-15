****🎥 Anime Recommender System (MLOps Project)****

📌 Overview

This project is an **Anime Recommendation System** built as part of an MLOps certification project.
The system leverages ETL pipelines, GCP, Comet ML, and Jenkins CI/CD to deliver scalable and automated model training & deployment.

It is designed for:

**Anime streaming platforms ** to personalize recommendations for users.

**Anime enthusiasts (geeks)** who want smart suggestions for what to watch next.

****🚀 Features****

✅ Data ingestion & preprocessing with **ETL pipeline**

✅ Model tracking & experiment management via **Comet ML
**
✅ Automated CI/CD pipeline using **Jenkins
**
✅ Scalable infrastructure deployed on **Google Cloud Platform (GCP)
**
✅ Recommender system powered by collaborative filtering + content-based approaches


****⚙️ Installation & Setup****

1️⃣ **Clone the repository**
```git clone https://github.com/your-username/anime-recommender-mlops.git```
```cd anime-recommender-mlops```

2️⃣ Create virtual environment & install dependencies
```python -m venv venv```
```source venv/bin/activate```   # (Linux/Mac)
```venv\Scripts\activate```      # (Windows)

```pip install -r requirements.txt```

3️⃣ Configure Comet ML

Create a Comet ML account and get your API key.

Set it as an environment variable:

export COMET_API_KEY="your-api-key"

4️⃣ Run ETL pipeline
python src/etl/run_etl.py

5️⃣ Train the model
python src/models/train.py

6️⃣ Deploy via Jenkins (CI/CD)

Jenkins is configured to:

Pull latest code from GitHub

Run tests

Trigger model training

Deploy to GCP
