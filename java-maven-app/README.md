# 🚀 CI/CD Pipeline using Jenkins for a Java Maven Application

## 📌 Project Overview

This project demonstrates a Continuous Integration (CI) pipeline using Jenkins for a Java Maven application. The application source code is hosted on GitHub, and Jenkins automatically fetches the code, builds it using Maven, and generates a JAR artifact.

---

## 🛠️ Technologies Used

- Jenkins
- Java 21
- Maven 3
- Git & GitHub
- AWS EC2 (Ubuntu)
- Linux

---

## 📂 Project Structure

```
java-maven-jenkins-project
│
├── java-maven-app
│   ├── pom.xml
│   ├── src
│   └── target
│
├── images
│   ├── project-ec2-instance.png
│   ├── jenkins-dashboard.png
│   ├── jenkins-build-config.png
│   ├── jenkins-build-success.png
│   ├── jenkins-console-output.png
│   ├── jenkins-git-config1.png
│   └── jenkins-git-config2.png
│
└── README.md
```

---

## ⚙️ Project Workflow

1. Launch an AWS EC2 Ubuntu instance.
2. Install Java, Git, Maven, and Jenkins.
3. Create a Java Maven application.
4. Push the source code to GitHub.
5. Configure Jenkins Freestyle Project.
6. Connect Jenkins with the GitHub repository.
7. Build the application using Maven (`clean package`).
8. Generate the executable JAR file successfully.

---

## 📸 Project Screenshots

### AWS EC2 Instance

![EC2](images/project-ec2-instance.png)

---

### Jenkins Dashboard

![Dashboard](images/jenkins-dashboard.png)

---

### Jenkins Git Configuration

![Git Config 1](images/jenkins-git-config1.png)

![Git Config 2](images/jenkins-git-config2.png)

---

### Jenkins Build Configuration

![Build Config](images/jenkins-build-config.png)

---

### Build Success

![Build Success](images/jenkins-build-success.png)

---

### Console Output

![Console Output](images/jenkins-console-output.png)

---

## ✅ Build Result

- Source Code cloned successfully from GitHub.
- Maven dependencies downloaded successfully.
- Java project compiled successfully.
- Executable JAR file generated.
- Jenkins Build Status: **SUCCESS**

---

## 📚 Key Learning

- Jenkins Installation & Configuration
- Maven Build Automation
- GitHub Integration with Jenkins
- Continuous Integration (CI)
- Java Application Build Process
- AWS EC2 Server Management

---

## 👩‍💻 Author

**Rutuja Wavhal**

DevOps & Cloud Enthusiast