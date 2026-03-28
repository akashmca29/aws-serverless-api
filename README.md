# 🚀 AWS Serverless REST API

![Architecture](architecture.png)

---

## 📌 Overview
This project demonstrates a serverless REST API using AWS services. It handles client requests, processes backend logic, and stores data in a scalable NoSQL database.

---

## 🏗 Architecture

Client  
↓  
API Gateway  
↓  
AWS Lambda  
↓  
DynamoDB  

---

## 🧰 Services Used

- API Gateway → Handles HTTP requests  
- AWS Lambda → Executes backend logic  
- DynamoDB → Stores data  
- IAM → Security and permissions  
- CloudWatch → Monitoring and logs  

---

## ⚙️ How It Works

1. Client sends API request  
2. API Gateway receives request  
3. Lambda processes the request  
4. Data stored/retrieved from DynamoDB  
5. Response returned to client  

---

## 🔐 Security

- IAM roles restrict Lambda access  
- API Gateway authorization enabled  
- No direct database exposure  

---

## 💰 Cost Optimization

- Pay-per-use (serverless)  
- No idle infrastructure cost  
- Efficient resource usage  

---

## 📈 Scalability

- Auto-scales based on traffic  
- Handles high concurrent users  
- No manual scaling required  

---

## 📂 Project Structure

aws-serverless-api  
│  
├── architecture.png  
└── README.md  

---

## 🧠 Key Learnings

- Serverless architecture design  
- Event-driven systems  
- AWS service integration  
- Cost-efficient backend  

---

## 👨‍💻 Author

Akash  
AWS Certified Solutions Architect – Associate  

GitHub: https://github.com/akashmca29  

---

## ⭐ Conclusion

This project demonstrates building scalable and cost-efficient APIs using AWS serverless architecture without managing servers.
