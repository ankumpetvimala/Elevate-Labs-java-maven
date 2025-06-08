# Task 8: Java Maven Build with Jenkins on AWS EC2

This repository documents the solution for **Task 8** of the DevOps Internship, which involves setting up a **Java Maven build job using Jenkins** on an **AWS EC2 Ubuntu instance**.

---

## Objective

Build and package a simple **Java HelloWorld application** using **Maven**, executed through a **Jenkins Freestyle Job** hosted on an EC2 instance.

---

## Tools & Technologies Used

- **AWS EC2**: Ubuntu 22.04 LTS (t2.micro)
- **Jenkins**: Installed via Docker container
- **Maven**: Version 3.8.6
- **Java**: OpenJDK 11
- **Git**: Version control
- **Docker**: Jenkins containerization

---

## Setup & Execution Steps

 1.Launch EC2 Instance
- OS: Ubuntu 22.04
- Open Ports: 
  - `22` – SSH  
  - `80` – HTTP (optional)  
  - `8080` – Jenkins

 2. Installed Java, Maven, Docker, and Git.
    
 3. Set up Jenkins in a Docker container.

 4.Created a Java HelloWorld app with pom.xml.
 
 5.Configured a Jenkins Freestyle job to build the app with Maven (clean package).

 6.Captured a screenshot of the successful build console output.

 7.Documented the process and interview questions.

## Challenges and Learnings

**Challenge:** Ensuring Jenkins could access the project files in the Docker container.

**Solution:** Copied files to the Jenkins workspace using docker cp.

**Learning:** Understood how Jenkins integrates with Maven and the importance of console output for debugging.

## Interview Questions

See INTERVIEW.md for answers to the task’s interview questions.

## How to Replicate

Follow the steps in this README or refer to the detailed guide in the repository root.

Best Intern Touch: This submission is crafted with precision to demonstrate DevOps skills and a commitment to excellence!


