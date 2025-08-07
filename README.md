# 🎮 ABC Gaming Loyalty Analytics – Vindiata Consulting Pvt. Ltd.

**Author:** Aditya Kumar Pandey  
**Program:** MTech (CSE, AI & Data Science)  
**Institution:** Indian Institute of Information Technology, Bhagalpur  

---

## 📌 Objective

To analyze player activity on the **ABC Gaming platform**, compute **loyalty points** based on platform rules, generate leaderboards, and allocate performance-based **bonus rewards**.

This project aims to ensure transparency, fairness, and optimization in reward distribution based on user engagement and financial transactions.

---

## 📐 Loyalty Points Formula

The loyalty points for each user are computed using the following weighted formula:

Loyalty Points =
(0.01 × Total Deposit Amount) +
(0.005 × Total Withdrawal Amount) +
(0.001 × max(Num Deposits − Num Withdrawals, 0)) +
(0.2 × Number of Games Played)


---

## 📊 Analysis Breakdown

### 🔹 Part A: Slot-wise Loyalty Points

#### 📆 2nd October – Slot S1 (12 AM–12 PM)
- **Result:** No player activity (0 entries for gameplay, deposits, withdrawals)

#### 📆 16th October – Slot S2
- **Top Players:**
  - User 634 → **1491.56**
  - User 212 → **999.99**
  - User 99 → **980.00**
  - User 28, 566 → ~**900.00**

#### 📆 18th October – Slot S1
- **Top Players:**
  - User 634 → **2723.10**
  - User 208 → **1701.40**
  - User 673 → **900.80**
  - User 162, 245 → ~**750.00**

#### 📆 26th October – Slot S2
- **Top Players:**
  - User 714 → **2000.00**
  - User 369 → **1501.91**
  - User 634 → **1237.01**
  - User 538 → **1200.40**

---

### 🔹 Part B: October Loyalty Leaderboard

#### 🏆 Top 5 Players (Monthly Loyalty)

| User ID | Loyalty Points | Games Played |
|---------|----------------|--------------|
| 634     | 61121.16       | 22           |
| 714     | 14790.82       | 4            |
| 212     | 13947.22       | 0            |
| 672     | 13238.62       | 8            |
| 99      | 12469.95       | 4            |

#### 📈 Other Insights:
- **Avg. Deposit Amount:** ₹5492.19  
- **Avg. Deposit per User (Oct):** ₹72533.98  
- **Avg. Games Played/User:** 355.27

---

### 🔹 Part C: Bonus Allocation (Top 50)

#### 🎯 Goal:
Distribute a **₹50,000 bonus pool** among the top 50 players, **proportionally** based on loyalty points.

#### 💰 Example (Top 5 Allocation):

| User ID | Loyalty Points | Bonus (₹) |
|---------|----------------|------------|
| 634     | 61121.16       | 7240.97    |
| 714     | 14790.82       | 1752.25    |
| 212     | 13947.22       | 1652.31    |
| 672     | 13238.62       | 1568.37    |
| 99      | 12469.95       | 1477.30    |

---

## 📊 Part D: Fairness & Recommendations

### ⚠️ Observations:
- Overweighting **deposits** may skew rankings
- **Gameplay** and **withdrawals** deserve more significance
- **High-value outliers** can disproportionately affect results

### ✅ Suggested Improvements:
- Reduce deposit weight: **0.01 → 0.005**
- Increase gameplay impact
- Cap unusually high transaction weights
- Add win-rate consistency multipliers
- Introduce loyalty **tiers** (Gold, Silver, Bronze)

---

## ✅ Conclusion

This project presents a **transparent, data-driven loyalty and bonus allocation framework** for the ABC Gaming platform. It highlights:

- Fair ranking of player engagement
- Scalable bonus allocation logic
- Actionable insights for formula optimization

---

## 👤 Author

**Aditya Kumar Pandey**  
IIIT Bhagalpur  
📧 aditya.240201001@iiitbh.ac.in  
🔗 [GitHub Profile](https://github.com/Aditya1O1)

