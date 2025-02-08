# Market Peak E-Commerce Website

## **Title Page**

**Project Title:** Market Peak E-Commerce Website\
**Student Name:** [Your Name]\
**Institution:** [Your Institution Name]\
**Course Name:** [Your Course]\
**Instructor's Name:** [Instructor Name]\
**Date of Submission:** [Date]

---

## **Abstract**

This capstone project focuses on deploying a static e-commerce website using Git, Linux, and AWS. It demonstrates proficiency in version control, cloud computing, and web server configuration. The project follows a structured approach, including repository setup, website deployment, and continuous integration for updates. The final implementation ensures a scalable and accessible web presence hosted on AWS.

---

## **1. Introduction**

The **Market Peak E-Commerce Website** project aims to deploy a static website using Git, Linux, and AWS. This project highlights the importance of **version control**, **cloud hosting**, and **continuous deployment** in modern web development. The deployment process involves setting up a Git repository, configuring a Linux server on AWS, and hosting the website on an Apache web server. The project not only showcases technical skills but also enhances understanding of cloud-based infrastructure management.

---

## **2. Objectives**

- Implement version control using Git.
- Host a static e-commerce website on AWS EC2.
- Automate deployments using Git workflows.
- Secure and optimize the server configuration for better performance.

---

## **3. Tools and Technologies Used**

- **Version Control:** Git, GitHub
- **Cloud Services:** AWS EC2
- **Operating System:** Linux (Ubuntu/CentOS)
- **Web Server:** Apache
- **Development Tools:** CLI, SSH
- **Programming Languages:** HTML, CSS, JavaScript (if applicable)

---

## **4. Methodology**

This project follows a structured step-by-step approach:

### **4.1 Version Control with Git**

1. **Create a Local Repository**
2. **Download a Website Template**
3. **Stage and Commit the Website Files**
4. **Push Code to a Remote Git Repository**

### **4.2 AWS Deployment**

1. **Set Up an AWS EC2 Instance**
2. **Connect to the Instance via SSH**
3. **Clone Git Repository on the AWS Server**
4. **Install and Configure Apache Web Server**

### **4.3 Continuous Integration and Deployment (CI/CD)**

1. **Create a Development Branch and Make Changes**
2. **Commit and Push the Changes**
3. **Merge Changes into the Main Branch**
4. **Pull Updates on the AWS Server**
5. **Restart Apache Server to Apply Changes**

---

## **5. Implementation & Execution**

### **5.1 Setting Up Git Repository**

- Initialize a local Git repository.
- Add and commit files to the repository.
- Push the repository to GitHub.

### **5.2 AWS EC2 Instance Setup**

- Launch a new EC2 instance.
- Configure security groups and SSH access.
- Connect to the instance via SSH.

### **5.3 Installing Apache Web Server**

- Update all packages.
- Install Apache (`sudo apt install apache2 -y`).
- Enable and start Apache.
- Configure Apache to serve the website files.

### **5.4 Deploying Website on AWS**

- Clone the Git repository to the EC2 instance.
- Replace default Apache web directory with website files.
- Restart Apache to apply changes.

---

## **6. Results & Testing**

- The website is successfully hosted on AWS.
- The Git repository enables version control and easy updates.
- Continuous integration ensures smooth deployment.
- The website is accessible via the EC2 instance’s public IP.

---

## **7. Challenges & Solutions**

### **Challenges Faced:**

- SSH authentication errors.
- Apache misconfiguration issues.
- Git merge conflicts during updates.

### **Solutions Implemented:**

- Used proper SSH key configurations.
- Ensured correct Apache directory permissions.
- Resolved conflicts by managing Git branches efficiently.

---

## **8. Conclusion & Future Scope**

The **Market Peak E-Commerce Website** project successfully demonstrates cloud deployment, Git-based version control, and continuous integration. Future improvements include:

- Implementing HTTPS for security.
- Automating deployments with CI/CD pipelines.
- Enhancing the website with dynamic content and backend integration.

---

## **9. References**

- AWS Documentation: [https://docs.aws.amazon.com/](https://docs.aws.amazon.com/)
- GitHub Guides: [https://guides.github.com/](https://guides.github.com/)
- Apache HTTP Server Docs: [https://httpd.apache.org/](https://httpd.apache.org/)

Do this in markdown format

