# Mini-Stock-Advisor
# 📊 Mini Stock Advisor (Rule-Based System)

This project implements a **Rule-Based Mini Stock Advisor** using a simple 10-day stock dataset.  
The logic is implemented using **R in Google Colab**, and the system generates **BUY / SELL / HOLD** signals based on daily percentage changes.

---

## 📌 Project Features

### ✔ 1. Percentage Change Calculation  
Daily percent change is computed using:

\[
\text{percentage\_change} = \frac{\text{Close} - \text{Open}}{\text{Open}} \times 100
\]

---

## ✔ 2. Signal Generation (Rule-Based)

### **BUY Signal** (if ANY is true)
- Daily price increases more than **+2%**
- Today **and** yesterday both have **positive** change

---

### **SELL Signal** (if ANY is true)
- Daily price decreases more than **–2%**
- Today **and** yesterday both have **negative** change

---

### **HOLD Signal**
- Percentage change between **–2% and +2%**
- No BUY or SELL rule triggered

---

## 📘 Technologies Used
- **R Programming**
- **Google Colab**
- **rpy2 (to run R code in Colab)**
- **Matplotlib equivalent R plots** (barplot, hist, scatter)

---

## 📂 Files in This Repository
