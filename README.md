# EV-Charging-Station-Maintenance-Automation
An end-to-end Microsoft Power Platform solution features a Canvas App for field technicians, Dataverse relational schema, a Model-Driven administrative dashboard, and automated Power Automate cloud flows.
# EV Station Maintenance & Automation Portal

## 🚀 Project Overview
An enterprise-grade, end-to-end automation solution designed to streamline field tracking, maintenance dispatch, and administrative oversight for EV charging infrastructure. Built entirely within the Microsoft Power Platform environment utilizing Dataverse relational databases.

## 🏗️ System Architecture
The solution container holds a dual-app architecture tied into a centralized cloud database:

* **Front-End Data Entry:** A responsive **Canvas Power App** tailored for field technicians to initialize logs, select assets, and report system faults.
* **Back-Office Administration:** A **Model-Driven Power App** acting as an operations management hub, auto-generating data grids and analytical tracking views.
* **Relational Backend:** Custom **Microsoft Dataverse** schemas mapped with relational lookup capabilities between `Maintenance Logs` and `EV Charging Stations`.
* **Automated Cloud Logic:** A **Power Automate Flow** parsing JSON arrays and utilizing OData filtering expressions to dynamically fetch asset location metadata and dispatch structured alerts.

## 📦 Deployment Instructions
To replicate or audit this deployment:
1. Download the unmanaged `.zip` archive file from this repository.
2. Navigate to your target Power Apps environment maker portal.
3. Go to **Solutions** -> **Import solution** and upload the archive package.
4. Update connection references for Outlook and Dataverse components.
