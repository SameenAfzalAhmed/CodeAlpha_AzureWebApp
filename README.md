# 🚀 CI/CD DevOps Project README

## 📌 Project Overview

This project implements an automated CI/CD pipeline using Azure DevOps for a Blazor web application named AzureWebApp. The objective is to automate the build, integration, and deployment process so that code changes are delivered quickly, reliably, and consistently.

The application is developed using ASP.NET Core Blazor, managed with Git, and deployed automatically to Azure App Service through Azure Pipelines. This project demonstrates practical DevOps concepts used in cloud-based enterprise applications.
---
🛠️ Tools Used

Visual Studio Code – Development IDE

Blazor Web App (ASP.NET Core) – Web application framework

Git – Version control

Azure DevOps – Repository and CI/CD pipeline management

Azure Pipelines – Automated build and release pipeline

Azure App Service – Hosting and deployment

Azure Container Registry (ACR) – Container image storage (if containerized)
---

# 🧩 Task 1: CI/CD Pipeline – Azure Blazor Web App

## 🔹 Explanation of DevOps Project

### 1️⃣ Development Environment Setup

* **VS Code** installed and configured (already completed).
* Created a **Blazor Web App** using **ASP.NET Core Framework**.
* Project name: **AzureWebApp**.
* Application initially runs on **localhost**.
* Objective: **Publish the application to Azure App Service**.

---

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

### 🚀 Deployment (Publishing)

After building the website:

* The application is **published to Azure App Service** using:

  * VS Code publish option
* Alternative deployment method:

  * Push code to **Git repository** and deploy from source control

---
✅ Conclusion

This task successfully demonstrates a complete Azure-based CI/CD pipeline. It highlights how automation improves deployment speed, reliability, and consistency while reducing manual effort.

The project provides strong hands-on experience with Azure DevOps, Azure App Service, and modern DevOps workflows.


👤 **Author**: Sameen Afzal
