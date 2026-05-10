<img align="right" src="https://visitor-badge.laobi.icu/badge?page_id=luizbonato.luizbonato" />

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=32&center=true&vCenter=true&width=580&height=70&duration=4000&lines=Luiz+Eduardo+Bonato;Integration+%26+Automation+Engineer;" />
</h1>

<p align="center">
  Back-end developer focused on <strong>ERP integrations, workflow automation, and structured observability</strong>.<br/>
  I build systems that connect enterprise platforms — SAP B1, Salesforce, WMS — and keep them running reliably in production.
</p>

<br/>

<div align="center">
  <a href="mailto:luizeduardo.bonato@outlook.com">
    <img src="https://img.shields.io/badge/Email-333333?style=for-the-badge&logo=microsoft-outlook&logoColor=white" />
  </a>
  <a href="https://www.linkedin.com/in/luizbonato/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://luizbonato.github.io/portfolio/Index.html" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=todoist&logoColor=white" />
  </a>
</div>

---

## 🔧 Tech Stack

<div align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,js,docker,java,sqlite,grafana,git,github,postman,vscode&perline=10" />
</div>

<br/>

**Orchestration & Automation**

![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**ERP & Enterprise Integrations**

![SAP](https://img.shields.io/badge/SAP_Business_One-0FAAFF?style=flat-square&logo=sap&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)
![REST API](https://img.shields.io/badge/REST_APIs-FF6C37?style=flat-square&logo=postman&logoColor=white)

**Database**

![SAP HANA](https://img.shields.io/badge/SAP_HANA-0FAAFF?style=flat-square&logo=sap&logoColor=white)

**Observability**

![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

**In progress**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)

---

## 🏗️ What I Build

**ERP automation pipelines** — n8n workflows (self-hosted, Docker) handling Purchase Orders, Delivery Notes, Credit Notes, Stock Transfers, Landed Costs and Material Revaluation against SAP B1 Service Layer. Built with error handling, retries, idempotency and structured logging with execution IDs.

**Bidirectional CRM integrations** — Salesforce ↔ SAP B1 sync with custom objects, status updates and payload normalization via DTOs.

**WMS connectivity** — WYMS integration for shipment tracking, product endpoints and expedition workflows.

**External platform connectors** — LogComex (customs import), BankPlus (bank slips), PTAX API (FX rates).

**HANA SQL** — CTEs, `PARTITION BY`, `UNION ALL` and complex joins across SAP transactional tables (`ORDR`, `OINV`, `OPDN`, `ORIN`, `OSHP`, `ONCM`, `OPOR` and others) for business reporting and integration logic.

**Structured observability** — Grafana dashboards consuming n8n webhook data via Infinity plugin, JSONL logs, sanitized payloads and email alerts.

---

## 📡 Integration Surface

```
SAP Business One (Service Layer)
  └── PurchaseOrders · PurchaseDeliveryNotes · CreditNotes
  └── StockTransfers · LandedCosts · MaterialRevaluation

Salesforce        ←→   bidirectional sync
WYMS (WMS)        →    shipment & product data
LogComex          →    customs & import tracking
BankPlus          →    bank slip generation
PTAX API          →    FX rate consumption

Observability: Grafana (Infinity) ← n8n webhooks → JSONL logs
```

---

## 🎯 Where I'm Headed

Currently expanding into Java back-end development (Santander/DIO bootcamp) to deepen fundamentals and build the services I integrate with.

Areas of focus: REST API design · microservices · automated testing · clean architecture.

---

## 📊 GitHub Stats

<div align="center">
  <img width="390" src="https://streak-stats.demolab.com/?user=luizbonato&theme=react&border_radius=10" />
  <img width="390" src="https://github-readme-stats.vercel.app/api?username=luizbonato&count_private=true&show_icons=true&theme=react&rank_icon=github&border_radius=10" />
  <br/><br/>
  <img width="390" src="https://github-readme-stats.vercel.app/api/top-langs/?username=luizbonato&layout=compact&theme=react&border_radius=10" />
</div>
