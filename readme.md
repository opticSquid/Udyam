# 📱 Udyam - AI-powered ERP + CRM for Indian Businesses

**Udyam** is a mobile-first, AI-first full-stack platform that combines ERP (Enterprise Resource Planning) and CRM (Customer Relationship Management) functionality. Designed for Indian business owners, Udyam leverages a powerful AI assistant to provide insights, automation, and control—all from an intuitive Android/iOS app.

---

## 🚀 Key Highlights

- ✅ **AI Assistant (ChatGPT-like)** trained on customer-specific data
- ✅ **ERP Modules**: Sales, Inventory, Invoices, Payments, HR
- ✅ **CRM Modules**: Leads, Support, Campaigns, Customer Data
- ✅ **Mobile-Only**: Designed natively for Android/iOS
- ✅ **Real-Time Dashboards & Analytics**
- ✅ **Multi-Tenant, Scalable, Secure**
- ✅ **LLM, Embeddings, and Vector Search powered AI**

---

## 🎯 Target Audience

- Small and Medium Enterprises (SMEs)
- Indian Traders & Retail Chains
- Service-based Businesses
- Manufacturing Units
- Startups and Agencies

---

## 📦 Tech Stack (Suggested)

| Layer            | Tech Choices                                |
|------------------|----------------------------------------------|
| Mobile Frontend  | Jetpack Compose / Kotlin                      |
| Backend API      | Go / Node.js / Spring Boot                   |
| Database         | PostgreSQL / MySQL                           |
| AI Embeddings    | OpenAI / SentenceTransformers                |
| LLM Engine       | OpenAI GPT / LLaMA / Gemma via Ollama        |
| Vector DB        | Weaviate / Qdrant / Pinecone                 |
| Auth             | OAuth2 / Keycloak / Auth0                    |
| Messaging        | Kafka / RabbitMQ                             |
| Analytics        | Custom Dashboards / Metabase / Grafana       |

---

## 🧠 AI Assistant Capabilities

- Ask natural language questions about your sales, orders, payments, and inventory  
- Take action via chat (e.g., "create a new invoice", "add a customer")  
- Retrieve data summaries and trends  
- AI learns from your CRM and ERP activity over time  
- Integrates structured (DB) and unstructured (notes, PDFs) data

---

## 📲 ERP + CRM Modules

### ERP

- Inventory Management  
- Orders and Invoices  
- Vendor and Supplier Management  
- Employee and HR Module  
- Accounting (in future sprints)

### CRM

- Lead Tracking  
- Customer Interaction History  
- Campaign Management  
- Ticketing System for Support

---

## 🚧 Project Roadmap (For next Quarter April to July - 2025)

# 🗓️ Udyam Project — Q1 Development Plan (April to July)

| Sprint    | Duration              | Focus Area                            | Key Deliverables                                                                 |
|-----------|-----------------------|----------------------------------------|----------------------------------------------------------------------------------|
| Sprint 0  | End of May            | Project Initialization & Planning      | - Git repo setup<br>- `README.md` & docs<br>- Folder structure<br>- Docker Compose base |
| Sprint 1  | Week 1–2 of June      | Infrastructure Setup                   | - Postgres service via Docker Compose<br>- Backend service with health check<br>- CI/CD pipeline (e.g., GitHub Actions)<br>- DB migration tool setup (e.g., Flyway) |
| Sprint 2  | Week 3–4 of June      | Auth & Core Backend                    | - JWT auth APIs<br>- Tenant management<br>- Role-based access control<br>- Integration tests |
| Sprint 3  | Week 1–2 of July      | Android App Scaffolding (Jetpack)     | - Jetpack Compose project setup<br>- Login/signup integration<br>- Navigation and Retrofit<br>- Android build CI |
| Sprint 4  | Week 3–4 of July      | Dashboard & MVP Planning               | - Dummy dashboard data & chart APIs<br>- Android dashboard UI<br>- Finalize MVP scope for Q2<br>- User stories for ERP/CRM modules |

> 📌 **Quarter Objective:** Get infrastructure and CI/CD pipelines ready, establish Android app foundation, and finalize MVP scope for Q2.


---

## 📊 Success Metrics

- AI chatbot query accuracy ≥ 90%  
- Support for ≥ 1000 concurrent users per tenant  
- App response time ≤ 200ms for critical paths  
- AI response time ≤ 2 seconds  
- >95% uptime in production

---

## 🛡️ Security & Compliance

- OAuth2 / JWT-based authentication  
- Role-based access control (RBAC)  
- Data isolation per tenant  
- TLS encryption  
- GDPR-compliant architecture

---

## 💬 Contributing

We are in early stages. If you'd like to contribute:

1. Fork the repository  
2. Clone and set up backend + mobile project  
3. Submit pull requests with clear descriptions

---

## 🧾 License

MIT License. See [LICENSE](./LICENSE) for details.

---

## 🙌 Inspiration

_"Udyam" means enterprise in Hindi—this app is built to empower every Indian entrepreneur to grow their business with the power of AI._

---

## 📧 Contact

For questions, support, or business collaborations:  
**Soumalya** – [soumalyabhattacharya6@gmail.com]