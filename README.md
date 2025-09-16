# Customer Support & Booking AI Agent (n8n + OpenAI + Notion/Sheets)

### Problem
Handling customer queries and bookings manually is time-consuming and inconsistent. Customers expect instant replies and smooth booking experiences.

### Solution (n8n Workflow)
This workflow automates customer support and booking by:
- **Chat Input**: Accepts customer queries via WhatsApp/Telegram/Email.
- **AI Classification**: OpenAI node understands intent (FAQ vs Booking).
- **Booking Flow**: Collects details (date, service, customer info).
- **Database Logging**: Stores booking info in Notion/Google Sheets.
- **Escalation**: Routes complex issues to a human agent if confidence is low.

### Result
- Faster response times (instant FAQ replies).
- Automated booking confirmations.
- Seamless escalation for unresolved queries.

---

### ⚙️ Stack
- **n8n** (automation workflow)
- **OpenAI Chat Model** (intent classification, responses)
- **WhatsApp/Telegram/Email** (customer input)
- **Notion / Google Sheets** (store bookings & logs)

---

### 🚀 How to Run (Demo)
1. Import `workflow.json` into n8n (sanitized, no credentials included).
2. Configure credentials: Messaging app + OpenAI + Notion/Google Sheets.
3. Send a customer query or booking request.
4. Workflow automatically handles intent → replies or books → logs data.

---

### 📂 Repo Structure
```
/  
├── README.md              # Documentation  
├── workflow.json          # Sanitized n8n export (no secrets)  
├── /screenshots           # Workflow diagram & sample logs  
└── LICENSE                # MIT License  
```

---

### 🖼️ Screenshots
- Workflow diagram
- Example booking entry in Notion/Sheets

---

### 🔒 Notes on Credentials & Safety
- This repo **does not include** any credentials.
- Configure API keys and tokens within n8n before running.
- Replace placeholder IDs/links with your own.
