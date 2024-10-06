
# DevOps CI/CD Pipeline

I’ve set up a complete CI/CD pipeline using **Docker** and **Jenkins**, enabling seamless deployment of a Java application. Below are the key features of the pipeline:

## Docker Environment
- Three containers are used:
  - **Jenkins Master Node**
  - Two **Linux-based Jenkins build agents** with **Maven** installed, enabling Java builds.

## GitHub Repositories
- The [**application code**](https://github.com/Indrakumar-Mhaski/JavaCalculatorApp) and the **pipeline code** are hosted separately on GitHub to maintain clean version control and modularity.

## Build and Deployment Process
- The Jenkins master fetches both the application and pipeline code.
- The application artifact is built on the Jenkins agents.
- The artifact is deployed via **SSH** to an **EC2 instance** where a **Tomcat server** hosts the application.

## Continuous Integration and Deployment
- With every update to the application, Jenkins automates the entire build and deployment process, ensuring continuous integration and delivery.

This setup simplifies the development workflow while enhancing team efficiency.

---

### Technologies Used
- **Docker**
- **Jenkins**
- **Maven**
- **AWS EC2**
- **Tomcat**

#DevOps #CICD #Jenkins #Docker #AWS #Tomcat #Automation #Maven
