# Customer-Support-Ticket-Analyzer-Python-
Python project analyzing customer support tickets — text cleaning, priority analysis, and sentiment insights

# 📝 Customer Support Ticket Analyzer (Python Project)

**Tools:** Python | Dictionaries | Text Cleaning | String Methods | Loops & Functions  
**Domain:** Customer Service | Text Analytics | Data Processing  

---

## 📊 Project Overview
Customer support teams handle numerous tickets daily. This project builds a **Python-based Ticket Analysis System** to:
- Store and manage ticket data
- Clean and normalize issue descriptions
- Analyze ticket priorities
- Extract insights from customer feedback
- Identify sentiment patterns and vocabulary trends

---

## 🎯 Problem Statement
The goal was to help support teams quickly identify:
1. High-priority tickets requiring urgent resolution  
2. Common issues and recurring complaints  
3. Positive vs negative sentiment in customer feedback  
4. Vocabulary trends for future sentiment scoring models  

---

## 📂 Dataset
Preloaded dictionary of 10 tickets with attributes:
- **Ticket_No** – Auto-incremented ID  
- **Customer_Name** – Name of the customer  
- **Issue_Description** – Raw text feedback  
- **Priority** – High / Medium / Low  

New tickets can be added interactively with validation.

---

## 🔧 Python Techniques Used
- **Data Structures**: Dictionaries, Lists, Appending new entries  
- **Text Cleaning**:  
  - Lowercasing  
  - Punctuation removal  
  - Space normalization  
  - Slang replacement (“ok” → “okay”)  
- **Functions & Loops**:  
  - Auto-increment ticket numbers  
  - Priority validation  
  - Keyword search (e.g., “poor”, “good”, “slow”, “excellent”)  
- **Analysis**:  
  - Priority distribution (High/Medium/Low)  
  - Longest issue description  
  - Unique vocabulary extraction  

---

## 📊 Key Insights
- ⚠️ **40% of tickets are High Priority**, requiring urgent resolution.  
- ❌ Negative words like *“slow”*, *“poor”* appear multiple times, signaling performance gaps.  
- ✅ Positive feedback exists (*“good”*, *“excellent”*), but less frequent than complaints.  
- 📖 Vocabulary snapshot shows **26 unique words**, balancing positive and negative sentiment.  
- 🏆 Longest issue description: *“slow response very poor service”* (Ticket 2, Meera).  

---

## 📌 Conclusion
This Python project demonstrates how **basic text cleaning, keyword analysis, and priority classification** can provide actionable insights for customer support teams.  
Findings highlight the need to **improve response speed and service quality**, while leveraging positive feedback for training and motivation.

---

## 👨‍💻 Author
**Vishnu Prasath**  
📧 mvishnuprasath20@gmail.com  
🌐 GitHub: [VishnuPrasath-M](https://github.com/VishnuPrasath-M)  
💼 LinkedIn: [m-vishnu-prasath](https://linkedin.com/in/m-vishnu-prasath)

---

## 🏷️ Tags
#Python #TextAnalytics #CustomerSupport #DataCleaning 
