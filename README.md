# 🧠 CapstoneBara – AI-Powered Mental Health Support System

> **Demo Portfolio** - This repository showcases the CapstoneBara project without revealing source code.

## 📌 Overview

CapstoneBara is a full-stack mental health platform that empowers users to track their mental well-being and interact with an intelligent, emotionally aware chatbot. Designed for both individuals and healthcare professionals, the system supports early intervention, personalized recommendations, and secure health data management — all within a user-friendly interface.

## ✅ Key Features

- **AI Chatbot**: Built with Deepseek API, LangChain, and Groq to provide real-time, empathetic mental health advice.
- **Health Metrics Dashboard**: Track mood, stress, sleep, and activity trends with interactive visualizations.
- **Personalized Recommendations**: AI-generated tips for stress reduction, mindfulness, and well-being.
- **Secure Authentication**: OAuth 2.0 login and password hashing using PBKDF2.
- **HIPAA/GDPR Compliance**: Data encrypted in transit and at rest.
- **Dual Roles**: Tailored experience for individuals and healthcare professionals.

## 🧱 System Architecture

The platform consists of five main layers:

1. **Frontend (React.js)**
   - Responsive, clean UI for chatbot and health dashboard
   - OAuth login and multi-factor authentication
2. **Backend (Flask)**
   - RESTful APIs for user management, health data, chatbot interactions
   - JWT-based session control
3. **Database (MongoDB)**
   - Flexible document storage
   - Encrypted data at rest, role-based access control
4. **AI Engine**
   - Chatbot powered by Deepseek, LangChain, and BERT for contextual responses
   - Sentiment analysis and personalized health recommendations
5. **Security Layer**
   - AES-256 encryption
   - TLS-secured communication
   - Secure password storage with salting and hashing

## 🛠 Tech Stack

| Layer      | Technologies                                  |
|------------|-----------------------------------------------|
| Frontend   | React.js, HTML5, CSS3, TailwindCSS            |
| Backend    | Python, Flask, REST API, JWT                  |
| Database   | MongoDB (local or Atlas)                      |
| AI Engine  | Deepseek API, LangChain, BERT, Groq           |
| Security   | OAuth 2.0, Werkzeug.security, TLS, AES-256    |

## 🎯 Project Highlights

### User Interface
- Modern, responsive design with intuitive navigation
- Real-time chat interface with AI-powered responses
- Interactive health metrics dashboard with charts and graphs
- Mobile-friendly layout

### Security & Privacy
- End-to-end encryption for sensitive health data
- HIPAA/GDPR compliant architecture
- Secure authentication and authorization
- Role-based access control

### AI Capabilities
- Context-aware chatbot responses
- Sentiment analysis of user inputs
- Personalized health recommendations
- Long conversation memory using LangChain

## 📊 Screenshots & Demo

> **Note**: Live demo and screenshots can be added here. For security reasons, source code is not included in this repository.

## 🗓 Project Timeline

| Phase       | Duration | Activities                          |
| ----------- | -------- | ----------------------------------- |
| Planning    | 2 weeks  | Requirements, wireframes, Jira      |
| Development | 10 weeks | Full-stack build, AI chatbot        |
| Testing     | 4 weeks  | Unit, integration, and security     |
| Deployment  | 1 week   | Cloud setup and onboarding          |
| Maintenance | Ongoing  | Bug fixes, patches, feature updates |

## 👥 Contributors

* **Ngocanh Nguyen** – BS22DSY029
* **Luan Tran** – BS22DSY024
* **Huyen Truong** – BS22DSY032
* **Dung Nguyen** – BS22DSY030
* **Thi Chung** – BS22DSY040

## 🌱 Future Enhancements

* Mobile app (React Native)
* Wearable device integration (e.g., Fitbit)
* Multilingual chatbot support
* Voice assistant for accessibility
* Integration with clinical health records

## 🔐 Security & Compliance

All sensitive data is:
* Encrypted using **TLS** (in transit) and **AES-256** (at rest)
* Secured using **RBAC**, hashed passwords, and salting
* Compliant with **HIPAA** and **GDPR** regulations

## 📝 License

This is a portfolio demonstration. Source code is proprietary and not included in this repository.

---

> **CapstoneBara** is a proactive and scalable solution to the growing demand for digital mental health care. With a secure, evidence-based, and user-focused design, it empowers both individuals and clinicians to manage mental health in real time — with empathy and insight.

## 📧 Contact

For inquiries about this project, please contact the development team.

---

**Note**: This repository is for demonstration purposes only. Source code, configuration files, and sensitive information are excluded for security and intellectual property protection.
