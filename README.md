# 🚀 DevOps CI/CD Sample Web Application

## 📌 Project Overview

This project demonstrates an end-to-end Continuous Integration and Continuous Deployment (CI/CD) pipeline using DevOps tools. It automates the process of building, testing, and deploying a Java web application from source code to a running application on a server.

---

## 🔄 CI/CD Pipeline Flow

1. Developer writes code and pushes to Git repository
2. Code is hosted on GitHub
3. Jenkins pulls the latest code automatically
4. Build process using Ant/Maven
5. Unit testing using JUnit
6. Deployment to Tomcat server
7. Application becomes available to users

---

## 🧰 Tools & Technologies Used

* Git — Version Control
* GitHub — Code Repository
* Jenkins — CI/CD Automation Server
* Java — Application Development
* Ant / Maven — Build Tool
* JUnit — Testing Framework
* Tomcat — Application Server

---

## 📋 Prerequisites

Before running this project, ensure the following are installed:

* Git
* Java (JDK)
* Apache Tomcat
* Jenkins
* Ant or Maven
* Internet connection

---

## ⚙️ Jenkins Plugins Used

* GitHub Plugin
* Ant Plugin
* JUnit Plugin
* Deploy Plugin
* Pipeline Plugin

---

## 🖥️ Project Structure

```
SampleWebApp/
│
├── WebContent/          # Web pages and static content
├── src/example/         # Java source code
├── build/classes/       # Compiled classes
├── build.xml            # Ant build script
├── checkstyle_errors.xml
├── sun_checks.xml
├── TestCalculator_JUnitResult.txt
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository

```
git clone https://github.com/jitendar6486/SampleWebApp.git
cd SampleWebApp
```

2. Configure Jenkins job with GitHub repository

3. Set build steps using Ant/Maven

4. Configure deployment to Tomcat server

5. Run the pipeline

---

## 🎯 Output

. Automated build
. Automated testing
. Automated deployment
. Running web application on Tomcat

---

## 📌 Conclusion

This project demonstrates how multiple DevOps tools work together to implement a fully automated CI/CD pipeline, enabling faster delivery, improved reliability, and reduced manual effort.




