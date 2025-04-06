# 🛒 Smart Shopping AI – Hyper-Personalized Product Recommendations

This project was built for the Accenture Hackathon 2025 under the problem statement **"Smart Shopping: Data and AI for Personalized E-Commerce."** It presents a multi-agent system that delivers **hyper-personalized product recommendations** using AI and long-term memory.

---

## 🔍 Problem Statement

In the competitive e-commerce world, personalized product recommendations are key to customer satisfaction and business growth. This project builds a multi-agent AI system that understands browsing behavior, predicts preferences, and optimizes recommendations in real-time.

---

## 🧠 Our Multi-Agent AI System

| Agent Type         | Description |
|--------------------|-------------|
| **Customer Agent** | Tracks user behavior (browsing, clicks, search history) and stores it in SQLite for long-term personalization. |
| **Product Agent**  | Monitors and ranks products based on ratings, sales, and popularity. |
| **Recommendation Agent** | Combines collaborative filtering + content-based filtering to suggest personalized products using machine learning. |

---

## 🏗️ Tech Stack

- Python
- Flask / Streamlit (Web App)
- SQLite (Database for long-term memory)
- Pandas, Scikit-learn, NumPy (ML stack)
- HTML/CSS/Bootstrap (for UI if Flask used)

---

## ⚙️ How to Run

1. **Clone the repo**  
```bash
git clone https://github.com/YourUsername/smart-shopping-ai.git
cd smart-shopping-ai
# Hackathon
