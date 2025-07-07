# ArgoCD Demo

This project demonstrates how to use Argo CD for **Continuos Deployment**. Helm Charts are stored under base directory and new application can be deployed my modifying the values.yml file in the helm chart

---

## ✨ Features

- CD pipeline using ArgoCD
  - Automated Deployment in k8s cluster as soon as changes are made in github repo

---

## 📁 Project Structure

```

├── base/                 # Application Helm Charts
│   └── helm-charts
├── environments
    └── dev
    └── prod
├── .github/workflows                   # Github Action Workflows
└── helm-application.yml
└── application.yml
└── README.md

```

DevOps & Cloud Enthusiast | MS in Cloud Computing
GitHub: [@ranjan039](https://github.com/ranjan0369)
