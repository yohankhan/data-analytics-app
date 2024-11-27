# data-analytics-app

# Data Analytics Application with CI/CD Pipeline

Welcome to the **Data Analytics Application** project! This repository hosts a Python-based data analytics application integrated with a CI/CD pipeline for automated deployment and monitoring. 

---

## **Project Overview**

This project showcases the development and deployment of a data analytics application using modern DevOps tools. The CI/CD pipeline automates building, testing, deploying, and monitoring processes, making the workflow efficient and reliable.

---

## **Technologies Used**

- **Version Control**: GitHub
- **Containerization**: Docker
- **Orchestration**: Minikube (Kubernetes)
- **CI/CD Tool**: Jenkins
- **Testing Tool**: Pytest (Selenium optional for web interface)
- **Operating System**: Windows

---

## **Project Structure**

| **Directory/File**       | **Description**                                             |
|---------------------------|-------------------------------------------------------------|
| `data/`                  | Directory for storing sample datasets (e.g., CSV files).     |
| `src/`                   | Source code directory containing application logic.          |
| `tests/`                 | Directory for automated test scripts.                       |
| `requirements.txt`       | List of Python dependencies.                                |
| `Dockerfile`             | Configuration for Docker containerization.                  |
| `Jenkinsfile`            | CI/CD pipeline configuration for Jenkins.                   |
| `k8s/`                   | Kubernetes manifests for deployment and service setup.       |
| `README.md`              | Project documentation (this file).                          |

---

## **Setup Instructions**

### **1. Clone the Repository**
1. Clone the GitHub repository to your local machine.
2. Navigate to the project directory.

### **2. Set Up Python Environment**
1. Create a virtual environment.
2. Activate the virtual environment.
3. Install dependencies listed in `requirements.txt`.

### **3. Run the Application Locally**
1. Start the application.
2. Access it in your web browser at `http://localhost:5000`.

---

## **Containerization with Docker**

1. Build a Docker image for the application.
2. Run the Docker container to serve the application.

---

## **CI/CD Pipeline with Jenkins**

1. Install Jenkins and necessary plugins (e.g., Docker, GitHub).
2. Configure a Jenkins pipeline job using the `Jenkinsfile` in this repository.
3. Define pipeline stages:
   - Build
   - Test
   - Docker Build
   - Deploy to Minikube

---

## **Deployment with Minikube**

1. Start Minikube to create a local Kubernetes cluster.
2. Apply the Kubernetes manifests from the `k8s/` directory.
3. Access the application using the service exposed by Minikube.

---

## **Testing**

1. Run unit tests using Pytest to verify the analytics logic.
2. (Optional) Use Selenium to test the web interface, if applicable.

---

## **Screenshots**

### Application Interface

![Screenshot 2024-11-26 024653](https://github.com/user-attachments/assets/d346d498-bef7-44b4-8dcb-618485bce422)

### Jenkins Pipeline
![Screenshot 2024-11-22 185550](https://github.com/user-attachments/assets/7902d0b1-440d-4ad7-89c1-8519e8dcdffb)

### Kubernetes Deployment
_(Add a screenshot of the Minikube deployment and service status here.)_
![Screenshot 2024-11-26 023330](https://github.com/user-attachments/assets/11701f48-3d49-4586-aeb8-ac7225c7e113)

---

## **How to Contribute**

We welcome contributions from the community. To contribute:
1. Fork the repository.
2. Create a new feature branch.
3. Commit your changes with meaningful messages.
4. Push your branch and create a pull request.


For any queries or issues, feel free to open an issue in the repository or reach out to the project maintainers.
