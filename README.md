# 🚀 Azure App Service + GitHub Actions CI/CD Integration Guide

This documentation explains how to deploy an application from a **GitHub repository** to **Azure App Service** using **GitHub Actions** for continuous integration and continuous deployment (CI/CD).

---

## 📘 Overview

**Azure App Service** is a fully managed platform for building, deploying, and scaling web apps.  
By integrating it with **GitHub Actions**, you can automate your deployment process — every time you push changes to your repo, your app is built and deployed automatically.

---

## ⚙️ Prerequisites

Before you begin, ensure you have:

- An **Azure subscription** ([Free trial](https://azure.microsoft.com/free/))
- An **Azure App Service** created (Web App)
- A **GitHub repository** containing your app code
- **Azure CLI** installed and logged in  
  ```bash
  az login
