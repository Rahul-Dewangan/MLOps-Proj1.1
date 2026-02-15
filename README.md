# 🚗 Vehicle Insurance MLOps Project

End-to-end **production-ready Machine Learning system** that covers data ingestion → validation → transformation → model training → evaluation → deployment → CI/CD → cloud hosting.

Built with industry practices used in real ML platforms.

---

## 🌟 Project Highlights

✅ Modular pipeline architecture
✅ MongoDB Atlas data source
✅ Data validation with schema enforcement
✅ Reproducible training
✅ AWS S3 model registry
✅ Dockerized application
✅ GitHub Actions CI/CD
✅ Self-hosted runner on EC2
✅ Production inference via Flask API
✅ Environment variable based secret management
✅ Logging & custom exception handling

---

## 🧱 System Architecture

![Image](https://miro.medium.com/v2/resize%3Afit%3A1400/1%2AfQaST8tSpIbjIRfhiNuhOw.png)

![Image](https://images.openai.com/static-rsc-3/YuOWQilPfXku4q7Fvehk6uxsvY5ZniJ_nGPdok4UECmRRD9lkSQ6wdz5Bww_7XmqMbaJXcJ2umdO5SQ_I_jYzmNN7vUVQMOA9xFvjvB5nF4?purpose=fullsize\&v=1)

![Image](https://valohai.com/assets/img/cicd-abstract.png)

![Image](https://blog.paperspace.com/content/images/2018/07/ml-cd2.png)

---

## ⚙️ Tech Stack

### 👨‍💻 Programming & ML

* Python
* NumPy / Pandas / Scikit-learn
* Jupyter Notebook

### 🧩 MLOps & Backend

* Modular pipeline design
* Custom logging & exception framework
* YAML based schema validation

### ☁️ Cloud

* Amazon Web Services
* Amazon S3 → Model registry
* Amazon EC2 → Hosting
* Amazon ECR → Docker images
* AWS Identity and Access Management → Permissions

### 🔄 DevOps

* Docker
* GitHub Actions
* Self-hosted Linux runner

### 🗄️ Database

* MongoDB Atlas

---

## 📁 Project Structure

```
artifact/
notebook/
src/
  ├── components/
  ├── configuration/
  ├── data_access/
  ├── entity/
  ├── aws_storage/
  ├── constants/
app.py
requirements.txt
Dockerfile
.github/workflows/aws.yaml
```

---

## 🚀 Features Recruiters Love

### 🧩 1. Production Grade Pipeline

* Independent components
* Config driven
* Easy retraining
* Clear artifacts

### 🧪 2. Data Validation

* Schema comparison
* Missing column detection
* Data drift prevention

### 🔁 3. Model Versioning

* Stored in S3
* Threshold based model replacement

### 🧠 4. Training Automation

Trigger via:

```
/training
```

### 🌐 5. Real Time Prediction API

Web app deployed on EC2:

```
http://<public-ip>:5080
```

### 🔒 6. Secure Secrets Handling

* Environment variables
* GitHub secrets
* No credentials in code

---

## 🧬 Pipeline Components

| Stage               | Responsibility                          |
| ------------------- | --------------------------------------- |
| Data Ingestion      | Fetch from MongoDB & create raw dataset |
| Data Validation     | Validate with schema.yaml               |
| Data Transformation | Feature engineering & preprocessing     |
| Model Trainer       | Train & select best model               |
| Model Evaluation    | Compare with production model           |
| Model Pusher        | Upload to S3                            |
| Prediction Pipeline | Serve inference                         |

---

## 🛠️ Local Setup

```bash
conda create -n vehicle python=3.10 -y
conda activate vehicle
pip install -r requirements.txt
```

Verify:

```bash
pip list
```

---

## 🗄️ Database Setup (MongoDB Atlas)

![Image](https://www.mongodb.com/docs/charts/static/db3b18603663b0372ec02a4dd216b9ec/0dbfc/sample-dashboard.webp)

![Image](https://www.mongodb.com/community/forums/uploads/default/original/2X/a/a1d3d80a9109c505778cb8062ae2a063d077042f.png)

![Image](https://i.sstatic.net/vnZQb.png)

![Image](https://i.sstatic.net/ITq6c.png)

* Create project
* Create M0 cluster
* Create DB user
* Allow IP `0.0.0.0/0`
* Get Python connection string
* Push dataset from notebook

---

## ☁️ AWS Setup Summary

* Create IAM user
* Generate access keys
* Configure environment variables
* Create S3 bucket → model registry
* Create ECR repo
* Launch EC2 Ubuntu machine

---

## 🐳 Docker + CI/CD Flow

![Image](https://media2.dev.to/dynamic/image/width%3D1600%2Cheight%3D900%2Cfit%3Dcover%2Cgravity%3Dauto%2Cformat%3Dauto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fgnnd2c1i7ksf3ou2fu7q.png)

![Image](https://docs.aws.amazon.com/images/prescriptive-guidance/latest/patterns/images/pattern-img/c39c110e-cbe5-459e-a0aa-de27e884fb10/images/298e0e16-3054-49b7-8695-db510e0df2df.png)

![Image](https://user-images.githubusercontent.com/60080580/148239847-db32352e-50f2-40f6-9f9e-a82238c30374.png)

![Image](https://trstringer.com/images/github-self-hosted-ephemeral3.png)

On every push:

✔ Build Docker image
✔ Push to ECR
✔ Runner pulls latest image
✔ Container restarted on EC2

---

## 📊 Experimentation

* EDA notebook
* Feature engineering
* Modular utilities
* Reusable preprocessing

---

## 🎯 What This Project Demonstrates

This is not just ML.

It proves ability in:

✔ writing maintainable code
✔ data engineering
✔ distributed systems thinking
✔ cloud architecture
✔ CI/CD automation
✔ production deployment
✔ monitoring mindset

Exactly what companies expect from an **ML Engineer / MLOps Engineer**.

---

## 👨‍💼 Ideal For Roles

* Machine Learning Engineer
* MLOps Engineer
* Applied AI Engineer
* Backend ML Developer

---

If you want, I can also help you create:

✅ resume points from this project
✅ interview explanation (how to present in HR/tech rounds)
✅ architecture diagram for PPT
✅ GitHub profile description
✅ recruiter one-line pitch
✅ portfolio website content
✅ STAR format stories

What would you like next? 🚀
