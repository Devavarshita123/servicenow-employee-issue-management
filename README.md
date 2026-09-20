# ServiceNow Employee Issue Management

A ServiceNow application that enables employees to raise workplace-related issues through the **Service Portal** using a **Record Producer**, with validations, dependencies, and standardized issue management.

## 📌 Project Overview

In large organizations, employees often report workplace issues such as:

* Payroll discrepancies
* Access problems
* Infrastructure requests
* HR policy clarifications
* Other employee-related concerns

When these issues are reported through emails or informal communication, organizations may face inconsistent data, delayed resolution, limited visibility, and manual effort.

This project provides a structured solution using **ServiceNow** by allowing employees to submit issues directly through the **Service Portal**.

## 🎯 Objectives

* Enable employees to raise issues easily from the Service Portal.
* Use a **Record Producer** instead of exposing the custom table form directly.
* Standardize employee issue data collection.
* Implement client-side and server-side validations.
* Enforce field dependencies and business rules.
* Improve issue assignment and prioritization.
* Provide visibility into issue status and resolution.
* Follow ServiceNow configuration and development best practices.


## 🏗️ Solution Architecture
The application follows this flow:

```text
Employee
   ↓
Service Portal
   ↓
Employee Issue Widget / Catalog Item
   ↓
Record Producer
   ↓
Employee Issue Custom Table
   ↓
Business Rules / Client Scripts / Validations
   ↓
Assignment & Issue Management
   ↓
Resolution & Status Tracking
```

## ✨ Key Features

### 1. Service Portal Integration

Employees can access the issue-raising functionality directly through the Service Portal.

### 2. Record Producer

A Record Producer is used to collect employee issue information and create records in the custom **Employee Issue** table.

### 3. Employee Issue Custom Table

The submitted information is stored in a dedicated custom table for centralized issue management.

### 4. Validations

Client-side and server-side validations help ensure that required and valid information is submitted.

### 5. Field Dependencies

Dependent fields are configured so that the available options can change based on the employee's selections.

### 6. Issue Tracking

Employees and support teams can track the status of submitted issues throughout the resolution process.

### 7. Prioritization and Assignment

Business logic can be used to determine issue priority and route issues to the appropriate team.

## 🛠️ Technologies & ServiceNow Components

* ServiceNow
* Service Catalog
* Record Producer
* Service Portal
* Service Portal Widget
* Custom Tables
* Client Scripts
* Business Rules
* UI Policies
* Data Policies
* HTML
* CSS
* JavaScript
* Portal Configuration
* Developer Tools

## 📋 Main ServiceNow Components

| Component                   | Purpose                                                            |
| --------------------------- | ------------------------------------------------------------------ |
| Employee Issue Custom Table | Stores employee issue records                                      |
| Record Producer             | Creates Employee Issue records from the Service Portal             |
| Service Portal              | Provides the employee-facing interface                             |
| Service Portal Widget       | Provides/customizes the portal experience                          |
| Client Script               | Performs client-side validation and dynamic behavior               |
| Business Rule               | Enforces server-side business logic                                |
| UI Policy                   | Controls field visibility, mandatory state, and read-only behavior |
| Data Policy                 | Enforces data requirements                                         |
| Assignment Logic            | Routes issues to the appropriate support team                      |

## 🔄 Issue Submission Workflow

1. Employee opens the Service Portal.
2. Employee selects **Raise an Employee Issue**.
3. The Record Producer form is displayed.
4. Employee enters the required issue details.
5. Client-side validations are performed.
6. Dependencies and field conditions are applied.
7. The request is submitted.
8. The Record Producer creates an Employee Issue record.
9. Server-side business logic validates and processes the record.
10. The issue is assigned and prioritized.
11. The employee can track the issue status.

## 🧪 Validation & Business Rules

The application is designed to enforce:

* Mandatory fields
* Valid input values
* Field dependencies
* Consistent issue categorization
* Appropriate assignment
* Priority determination
* Server-side validation
* Consistent data capture

## 🚀 Demo

**ServiceNow Demo:**
*[Add your deployed/demo link here](https://drive.google.com/file/d/1KUCvkz39rTa8ajSfNG38yhTT0ZIAn62x/view?usp=drive_link).*

## 👩‍💻 Project Type

**Individual Project**

## 📚 Skills Demonstrated

* ServiceNow Administration
* Service Catalog Configuration
* Record Producer Development
* Service Portal Development
* Client-side Scripting
* Business Rules
* HTML
* CSS
* JavaScript
* Form Validation
* Application Configuration
* Workflow and Issue Management

## 📄 Project Context

This project was developed as an **Employee Raise Issue – Record Producer & Service Portal Integration** solution to demonstrate the design and implementation of a structured employee issue management workflow in ServiceNow.

---

```
