# 🚀 CI/CD DevOps Project README

# 🧩 Task 1: CI/CD Pipeline using Azure

## 📌 Project Overview

This project focuses on building an **automated CI/CD pipeline using Azure DevOps and Azure services** for a Blazor web application. The main objective is to demonstrate how modern DevOps practices enable **continuous integration, continuous delivery, automation, and reliable deployments**.

The application is developed using **ASP.NET Core Blazor**, version-controlled using **Git**, and deployed automatically to **Azure App Service**. Azure DevOps tools are used to manage source code, pipelines, and monitoring, providing an end-to-end DevOps workflow.

---

# 🧩 Task 1: CI/CD Pipeline using Azure (Blazor Web App)

## 🎯 Task Objectives

This task focuses on building a **fully automated CI/CD pipeline using Azure DevOps and Azure services**.

### ✅ What is Covered in Task 1

* Build an **automated CI/CD pipeline** using **Azure Pipelines**
* Automatically deploy web applications via **Azure App Service**
* Monitor pipeline execution to ensure smooth and reliable deployments
* Learn and apply **key DevOps concepts** using Azure tools

Reference: **[www.codealpha.tech](http://www.codealpha.tech)**

---

## 🔹 Explanation of DevOps Project

### 2️⃣ Project Structure Explanation

#### 🔹 Project File (.csproj)

* Contains **Target Framework** configuration.
* Includes C# settings such as:

  * `nullable`
  * `implicitUsings`

These settings improve code safety and reduce boilerplate code.

---

#### 🔹 Program.cs (Entry Point)

* Acts as the **main entry point** of the application.
* Creates and configures the **WebApplication Builder**.
* Registers services and HTTP pipeline configuration.
* Uses **middlewares**, which are built-in functions handling requests and responses.

---

#### 🔹 Connected Services

* No connected services currently.
* No database or third-party integrations configured.

---

#### 🔹 Dependencies

* The Blazor application depends on:

  * `Microsoft.AspNetCore.App`

---

#### 🔹 Properties Folder

* Contains **JSON configuration files**.
* Defines environment-specific settings and development requirements.

---

#### 🔹 wwwroot Folder (Static Files)

* Contains **static files**, which do not change dynamically:

  * HTML
  * CSS
  * JavaScript
  * Images
  * Fonts
  * Videos

---

#### 🔹 Components Folder

* Core functionality of the Blazor application is implemented here.
* **Layout**:

  * Uses **master layout concept**.
  * Avoids duplication of UI design.
  * Provides flexibility and consistency.
* **Pages**:

  * All application pages are defined here.
  * `.razor` files allow writing **HTML + C# code** together.

---

#### 🔹 _Imports.razor

* Contains **shared namespaces**.
* Automatically accessible across all pages.

---

#### 🔹 App.razor

* **Root component** of the application.
* Executes first when the application starts.
* Handles routing and layout rendering.

---

#### 🔹 appsettings.json

* Used to configure application settings.
* Database connections can be added here using **connection strings**.

---

### 🔄 Application Flow

```
Program.cs → App.razor → Routes → Home Page
```

* `Program.cs` calls the App component.
* `App.razor` loads routes.
* Routes render the Home page.

---

### 🚀 Deployment (Automated via Azure CI/CD)

After building the website, deployment is handled through an **automated Azure CI/CD pipeline**:

* Source code is pushed to **Azure Repos**
* **Azure Pipelines** triggers automatically on code changes
* Application is built and packaged
* Docker image (if containerized) is pushed to **Azure Container Registry (ACR)**
* Application is deployed automatically to **Azure App Service**

This ensures **continuous integration, continuous delivery, faster releases, and reduced manual errors**.

---

### 📊 Pipeline Monitoring

* Azure Pipelines dashboard is used to:

  * Track build and release stages
  * Monitor logs and execution status
  * Identify failures quickly
* Ensures smooth and reliable CI/CD execution

---

## ✅ Conclusion

In this task, an end-to-end **CI/CD pipeline using Azure** was successfully implemented. The project demonstrates how code changes can be automatically built, tested, and deployed to the cloud with minimal manual intervention.

Through this task, key DevOps concepts were learned and applied, including:

* Continuous Integration and Continuous Deployment (CI/CD)
* Azure DevOps Pipelines
* Azure App Service deployment
* Source control and automation
* Cloud-based application hosting

This project provides practical, hands-on experience in using **Azure DevOps tools** to deliver scalable and reliable applications efficiently.

---

👤 **Author**: Sameen Afzal
