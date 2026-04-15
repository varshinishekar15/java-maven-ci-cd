# 🚀 Java Maven CI/CD Pipeline with GitHub Actions

This project demonstrates how to create a Java application using Maven and automate the build process using GitHub Actions.

---

## 📌 Overview

This project implements a simple CI pipeline:

- ☕ Java application built using Maven  
- ⚙️ Automated build using GitHub Actions  
- 🔄 Continuous Integration triggered on every push  

---

## 🛠️ Tech Stack

- Java (JDK 17)
- Maven
- GitHub Actions

---

## 📂 Project Structure

- `pom.xml` → Maven configuration  
- `src/` → Source code  
- `.github/workflows/` → CI/CD pipeline  
- `README.md` → Project documentation  
---

## ⚙️ How It Works

1. Developer pushes code to repository  
2. GitHub Actions workflow is triggered  
3. Maven compiles the project  
4. Application runs automatically  

---

## ▶️ Run Locally

```bash
mvn clean compile
java -cp target/classes com.example.HelloWorld
