# 💳 Payment Rule Engine

A Spring Boot based rule engine that converts natural language into structured payment rules.

## 🚀 Features
- Natural language rule parsing (NO AI)
- Advanced regex-based parser
- Chatbot UI
- REST API
- Multi-condition support (amount, time)

## 🧠 Example Input
Block transactions above 5000 after 10 PM

## 📊 Output
{
  "ruleType": "limit_control",
  "conditions": {
    "amount": ">5000",
    "time": "22:00-23:59"
  },
  "action": "block"
}

## 🛠 Tech Stack
- Java 17
- Spring Boot
- Maven
- HTML/CSS/JS

## ▶️ Run Locally
mvn spring-boot:run

Open:
http://localhost:8080

## 📌 Future Enhancements
- Database integration
- Rule management UI
- Fraud detection engine
