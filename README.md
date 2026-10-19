# AI-Powered Email Drafting and Classification System

**DKTE Society's Textile & Engineering Institute, Ichalkaranji**  
**Department of MCA**  
**Subject:** Generative Artificial Intelligence Lab (`01MCP205`)  
**Practical Examination Question Paper Set - 6**  
**Question:** Q.2 AI-Powered Email Drafting and Classification System (25 Marks)

---

## 📌 Project Overview
An AI-based email assistant developed to help users draft and organize professional emails. The system allows users to customize tone and recipient hierarchy, generates properly formatted drafts, classifies incoming messages into domain categories, and verifies output accuracy against real-world scenarios.

---

## 🎯 Tasks Implemented
- **Task (a):** Accepts email purpose, recipient type (Professor, HR, Registrar, TPO, etc.), and preferred tone (Formal, Polite, Urgent, Semi-formal).
- **Task (b) & (d):** Generates structured emails with:
  - Clear, descriptive Subject line
  - Appropriate Salutation
  - Formatted message body
  - Formal Sign-off
- **Task (c):** Classifies incoming sample emails into 4 categories:
  - 🎓 `Academic`
  - 🏛️ `Administrative`
  - 💼 `Placement`
  - 👤 `Personal`
- **Task (e):** Automated test suite running 3 distinct scenarios:
  1. *Academic:* 2-day medical leave & assignment extension request to Course Professor.
  2. *Administrative:* Bonafide certificate & fee receipt application to Registrar.
  3. *Placement:* On-campus recruitment interview & eligibility inquiry to TPO.

---

## 🚀 How to Run

### 1. Run Automated Test Suite & Verification (Task e):
```bash
python email_assistant.py --test
```

### 2. Run Interactive Menu:
```bash
python email_assistant.py
```
Menu Options:
```text
1. Draft a Professional Email (Tasks a, b, d)
2. Classify an Incoming Email (Task c)
3. Run 3-Scenario Automated Verification Suite (Task e)
4. Exit
```

---

## 📋 Requirements
- Python 3.8+
- Standard Python libraries (`json`, `re`, `urllib`, `os`)
