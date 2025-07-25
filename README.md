# AWS-hosted Virtual Classroom and Learning Platform


## 📌 Project Overview

This project demonstrates how to build and deploy a secure, scalable virtual classroom using the Flask web framework and AWS cloud services. The platform allows students to register, log in, and access educational content, while administrators can manage course materials — all hosted entirely on the cloud.

## 🚀 Key Technologies

- **Backend:** Python, Flask  
- **Frontend:** HTML, CSS, JavaScript, Bootstrap  
- **Cloud Services:**  
  - Amazon EC2 – Hosting the Flask web app  
  - Amazon S3 – Storing and serving course content  
  - Amazon RDS (MySQL) – User data and course metadata  
- **Tools:** Git, GitHub, MySQL Workbench, Boto3  

---

## 🛠️ Features

- ✅ User registration and login functionality  
- ✅ Admin upload and update of course materials  
- ✅ Students can view and download course resources  
- ✅ Content stored in S3 with secure access  
- ✅ Responsive web design for seamless UX  
- ✅ Fully deployed on AWS infrastructure  

---

## 🧱 Architecture Overview

1. **EC2 Instance:** Hosts the Flask web server  
2. **S3 Bucket:** Stores PDFs/videos and delivers via signed/public URLs  
3. **RDS (MySQL):** Handles user information and file metadata  
4. **Flask + Boto3:** Integrates backend with AWS services  
5. **GitHub:** Source code version control and deployment  

---

## 🧪 Project Workflow

### 1. AWS Account Setup
- Sign up and configure AWS Console

### 2. Create S3 Bucket
- Upload files and configure permissions

### 3. RDS Instance Setup
- Launch MySQL instance and create necessary tables

### 4. Launch EC2
- Install required packages and configure environment

### 5. Develop Flask App
- Build routes: `/register`, `/login`, `/content`
- Use Jinja2 templates and connect to S3 and RDS

### 6. Deploy on EC2
- Clone from GitHub and run Flask/Gunicorn server

---

## 📺 Demo

🎥 [Click to Watch Project Demo]( https://drive.google.com/file/d/10JM5KMI7mR-At2NKgv_TT78yJa1jRmFf/view?usp=sharing )

---

## 👨‍💻 User Scenarios

### 👩 Alice (Student)
- Registers → Logs in → Accesses course content from S3

### 👨 Admin
- Uploads PDFs/videos to S3 → Updates metadata in RDS

### 👨‍🎓 Bob (Student)
- Downloads materials through secure links on content page

---

## ⚠️ Challenges Faced

- Learning IAM and AWS service configuration  
- Managing credentials and permission scopes  
- Troubleshooting RDS and EC2 networking issues  
- Flask integration with `boto3` SDK  

---

## ✅ Final Outcome

The project successfully delivers a fully functional virtual classroom built on AWS and Flask. It demonstrates real-world cloud computing skills and showcases seamless integration between web technologies and cloud platforms.

---

## 📚 References

- [AWS Account Setup](https://youtu.be/CjKhQoYeR4Q?si=ui8Bvk_M4FfVM-Dh)  
- [AWS EC2 Setup](https://www.youtube.com/results?search_query=aws+ec2+oneshot)  
- [Amazon RDS MySQL](https://www.youtube.com/results?search_query=rds+oneshot)  
- [MySQL with Flask](https://www.youtube.com/results?search_query=mysql+connector+for+rds)  
- [GitHub Integration](https://www.youtube.com/results?search_query=clone+github+repository)  
- [AWS Cost Management](https://youtu.be/OKYJCHHSWb4?si=aY3DQl1v26CfZxXA)  

---

## 🙌 Acknowledgements

This project is a part of the **Smart-Internz** aws-hosted virtual classroom and learning platform project, completed under the guidance of **D Y Patil Agriculture and Technical University, Talsande**.


