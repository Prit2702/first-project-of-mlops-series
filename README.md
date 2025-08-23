# 🚗 Vehicle Insurance Prediction – MLOps Project  

This project demonstrates a complete **MLOps workflow** for predicting vehicle insurance claims using modern tools and best practices. It integrates data pipelines, cloud services, model deployment, monitoring, and CI/CD automation.  

---

## ✨ Features  

- 🔄 **End-to-End ML Pipeline**: Modular components for data ingestion, validation, training, and deployment.  
- 🗄️ **MongoDB Integration**: Store and retrieve datasets using MongoDB Atlas.  
- ☁️ **AWS Integration**: Leverages AWS S3 for model storage and EC2 for deployment.  
- 📦 **Dockerized Application**: Containerized for seamless deployment across environments.  
- ⚡ **CI/CD with GitHub Actions**: Automated testing, building, and deployment workflows.  
- 🛠️ **Logging & Exception Handling**: Robust error tracking and debugging support.  
- 📓 **Jupyter Notebooks**: For exploratory data analysis (EDA) and feature engineering.  

---

## 📂 Project Structure  

```

.
├── app.py                # Main application entry point
├── demo.py               # Demo script for testing components
├── Dockerfile            # Docker configuration
├── requirements.txt      # Python dependencies
├── pyproject.toml        # Project metadata and build config
├── setup.py              # Setup script
├── src/                  # Source code
│   ├── cloud\_storage/
│   ├── components/
│   ├── configuration/
│   ├── constants/
│   ├── data\_access/
│   ├── entity/
│   ├── exception/
│   ├── logger/
│   ├── pipeline/
│   └── utils/
├── notebook/             # Jupyter notebooks and experiments
│   ├── exp-notebook.ipynb
│   ├── mongoDB\_demo.ipynb
│   └── data.csv
├── templates/            # HTML templates
│   └── vehicledata.html
├── static/               # Static files (CSS, images, etc.)
├── config/               # Model and schema configs
└── projectflow\.txt       # Workflow documentation

````

---

## 🚀 Getting Started  

### 1. Clone the repository  
```bash
git clone https://github.com/<your-username>/Vehicle-Insurance-Prediction.git
cd Vehicle-Insurance-Prediction
````

### 2. Create and activate a virtual environment

```bash
conda create -n vehicle python=3.10 -y
conda activate vehicle
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Set up environment variables

**MongoDB**

```bash
export MONGODB_URL="mongodb+srv://<username>:<password>@<cluster-url>"
```

**AWS**

```bash
export AWS_ACCESS_KEY_ID="your-access-key"
export AWS_SECRET_ACCESS_KEY="your-secret-key"
export AWS_DEFAULT_REGION="us-east-1"
```

### 5. Run the application

```bash
python app.py
```

---

## 🧪 Notebooks

* Use the `notebook/` folder for:

  * Exploratory Data Analysis (EDA)
  * Feature Engineering
  * MongoDB operations

---

## ⚙️ Deployment

* 🐳 **Docker**: Containerization using Dockerfile.
* ⚡ **CI/CD**: Configured via GitHub Actions (`.github/workflows/aws.yaml`).
* ☁️ **Cloud**: Deployment to AWS EC2 and storage in S3.

---

## 📜 License

This project is licensed under the **MIT License**. See [LICENSE](LICENSE) for details.

---

## 👨‍💻 Author

**Prit2702**

---
