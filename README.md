# 📚 ReadHub – Cloud-Native Intelligent Bookstore Analytics

ReadHub is a modern, cloud-native platform designed to transform raw bookstore and customer data into actionable business insights. Built on Microsoft Azure with a Lakehouse architecture, it supports both real-time and historical data processing for scalable and intelligent analytics.

---

## 🎯 Objectives

- Integrate diverse structured and semi-structured data sources
- Transform and organize data using Lakehouse layers (Bronze, Silver, Gold)
- Enable real-time dashboards, ML models, and personalized APIs

---

## 💡 Purpose & Mission

- **Purpose**: Deliver data-driven insights to empower smarter decision-making
- **Mission**: Provide a unified, scalable, and secure data platform for business intelligence and AI

---

## 🧩 Architecture Phases

1. **Phase 1 – Initial Design**: Basic ingestion and data flow
2. **Phase 2 – Refinement**: Layered architecture and schema validation
3. **Phase 3 – Final Architecture**: Full orchestration and automation

---

## 🗃️ Data Sources

- Customer Profiles (user history and preferences)
- Sales Transactions (purchase records)
- Web Logs (site navigation and activity)
- Book Metadata (title, genre, ratings)
- User Reviews (feedback and sentiment)

---

## 🏗️ Lakehouse Layers

- **Bronze Layer**: Ingest raw data via Azure Data Factory and Event Hubs
- **Silver Layer**: Curate and normalize data with Delta Lake
- **Gold Layer**: Summarize data using Synapse SQL for BI and ML

---

## 🔄 Pipeline Orchestration

- Master pipeline executes daily at 12:05 AM
- Sub-pipelines: Sales, Metadata API, Reviews, Web Logs
- Orchestrated using dependency chaining

---

## ❗ Failure Handling

- Retry attempts: 3
- Retry interval: 1 hour
- Persistent issues are logged for manual resolution

---

## 📊 Deliverables

- **Dashboards (Power BI)**:
  - Sales Trends
  - Customer Segments
  - Campaign Effectiveness
  - Sentiment Analysis

- **APIs**:
  - Personalized Book Recommendations
  - Behavior Analytics

- **Reports**:
  - Weekly Campaign Performance
  - User Engagement Metrics

---
