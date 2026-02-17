# SampleWebApp – DevOps CI/CD Pipeline Project (Windows)


## 📌 Project Overview

SampleWebApp is a Java-based web application integrated with a complete CI/CD pipeline using Jenkins.

This project demonstrates an automated DevOps workflow that includes:

- Pulling source code from GitHub
- Building the application using Apache Ant
- Running unit tests using JUnit
- Deploying the application to Apache Tomcat

The goal of this project is to implement a real-time Continuous Integration and Continuous Deployment process.

---

## 🔄 CI/CD Workflow

1. Developer pushes code to GitHub repository.
2. Jenkins automatically pulls the latest code.
3. Ant builds the application and checks quality.
4. JUnit runs test cases and generates reports.
5. If tests pass, the application is deployed to Tomcat.
6. The final application runs on the Tomcat server.

---

## 🛠 Prerequisites

Install the following tools before setup:

- Git
- Java (JDK)
- Apache Tomcat
- Jenkins(windows)
- Apache Ant

### Configure Environment Variables:

- JAVA_HOME
- ANT_HOME
- PATH update

Restart the system after configuration.

---

## ⚙ Tools & Technologies Used

- Git
- GitHub
- Jenkins(windows)
- Apache Ant
- JUnit
- Apache Tomcat
- Java

---

## 📁 Project Structure

SampleWebApp/
│
├── src/
│   └── (Java source files)
│
├── test/
│   └── (JUnit test cases)
│
├── build.xml
│
├── README.md
│
└── ci-cd-pipeline.png

---

## 🔧 Jenkins CI/CD Jobs

### 1️⃣ First Job – GitHub Pull
- Pulls source code from GitHub
- Uses Git Plugin
- Configured with credentials

### 2️⃣ Second Job – Build
- Uses Apache Ant
- Executes build.xml
- Compiles Java code
- Generates WAR file

### 3️⃣ Third Job – Testing
- Executes JUnit test cases
- Displays test results in Jenkins dashboard

### 4️⃣ Fourth Job – Deploy
- Deploys WAR file to Apache Tomcat
- Uses Deploy to Container Plugin
- Application runs on:

http://localhost:8080/SampleWebApp

---

## 📊 Required Jenkins Plugins

- Git Plugin
- Ant Plugin
- JUnit Plugin
- Deploy to Container Plugin
- Pipeline Plugin

---

## 🚀 Setup Steps

1. Install all required tools.
2. Configure environment variables.
3. Install Jenkins plugins.
4. Create Jenkins jobs (Freestyle or Pipeline).
5. Connect GitHub repository.
6. Trigger build manually or via webhook.
7. Verify build success.
8. Check test reports.
9. Verify deployment on Tomcat server.

---

## 🧪 Testing

JUnit is used for validating application functionality.

If any test case fails:
- Deployment step will not execute.
- Build will be marked as FAILED.

---

## 🎯 Final Output

Application successfully deployed on Tomcat server.

Access application at:

http://localhost:8080/SampleWebApp

---

## 👩‍💻 Author

Jayashri Suryawanshi  
DevOps Engineer  
Skills: Linux | Docker | Kubernetes | AWS | Git | Jenkins | CI/CD



