# 🎮 AWS Serverless Tic Tac Toe Game

A cloud-powered **Tic Tac Toe** game built using **AWS Serverless Architecture** — designed for scalability, reliability, and zero server management.  
This project integrates key AWS services like **API Gateway**, **Lambda**, **S3**, and **IAM** to deliver a seamless gaming experience fully on the cloud. ☁️

---

##  Project Overview

This project demonstrates how traditional web applications like Tic Tac Toe can be reimagined using **serverless technologies**.  
All backend logic and data handling are event-driven and automatically scaled by AWS, eliminating the need for infrastructure management.

---

##  AWS Services Used

### **1. Amazon API Gateway**
- Acts as the secure entry point for all game interactions.  
- Routes player actions such as making moves or checking game state.  
- Provides request validation, throttling, and traffic management for smooth gameplay.

### **2. AWS Lambda**
- Executes serverless backend logic for game operations.  
- Handles move validation, winner detection, and state updates.  
- Automatically scales and runs only when triggered — ensuring high efficiency and low cost.

### **3. Amazon S3**
- Stores game state data and static assets (HTML, CSS, JS).  
- Provides durable, scalable, and secure object storage.  
- Enables fast and reliable access to game resources.

### **4. AWS IAM (Identity and Access Management)**
- Manages secure communication between AWS services.  
- Implements **least privilege access** for Lambda, API Gateway, and S3.  
- Ensures strong security boundaries within the architecture.



