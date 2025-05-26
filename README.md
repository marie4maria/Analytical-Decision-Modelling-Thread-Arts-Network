#  🧵 Analytical-Decision-Modelling-Thread-Arts-Network

A business modeling and optimization project focused on maximizing profit for a small custom calendar business: **Thread Arts Network**. The company produces three calendar types—**Basic**, **Portrait**, and a new high-margin **Resin** line—and needed to decide the best production strategy under limited resources. We developed mathematical models to help the business make data-driven decisions about product mix, advertising, and capacity.

---

## 🎯 Business Objective

- **Minimum Profit Goal:** $500/month
- **Time Constraint:** 40 hours/month for production
- **Product Requirements:**
  - At least 5 Basic Calendars per month
  - No more than 10 Portrait Calendars
  - Resin Calendars limited to 2 per month
- **Non-Negativity:** All production levels must be ≥ 0

---

## 🧮 Model Formulation

**Decision Variable:**  
- `X1`, `X2`, `X3`: Number of Basic, Portrait, and Resin calendars to produce

**Objective Function:**  
- Maximize total profit:  
  `max Σ [(Pi - mi)Xi - (ai × A)] for i ∈ {1, 2, 3}`  
  Where:
  - `Pi`: Price
  - `mi`: Material cost
  - `ai`: Number of ads
  - `A`: Cost per ad ($10)

**Constraints:**  
1. Profit ≥ $500  
2. Total production time ≤ 40 hours  
3. Produce ≥ 5 Basic Calendars  
4. Produce ≤ 10 Portrait Calendars  
5. Produce ≤ 2 Resin Calendars  
6. Basic production ≥ Portrait production  
7. Xi ≥ 0 (non-negativity)

---

## 📊 Model Results

### 🔹 Model 1:
- **Profit:** $624  
- **Basic Calendars:** 8  
- **Portrait Calendars:** 8  
- **Resin Calendars:** 0  
- **Time Used:** 40 hours

### 🔹 Model 2:
- **Profit:** $631  
- **Basic Calendars:** 7  
- **Portrait Calendars:** 7  
- **Resin Calendars:** 1  
- **Time Used:** 40 hours

---

## ✅ Recommendation

- **Adopt Model 2:** Higher overall profit despite added complexity from Resin Calendar production
- **Diversify Marketing:** Increase advertising to attract more customers and scale revenue
- **Explore Scaling:** Extend production time to enable higher-margin item output (e.g., more Resin calendars)

---

## 🔧 Tools Used

- Linear Programming (Optimization modeling)
- Excel Solver
- Scenario Analysis & Product Mix Strategy

---

## 👥 Team

- Matt Nordwick  
- **Mary John**  
- Yi-Ting Liu  
- Pratheek NS

---

## 📌 Key Insights

- A diversified product mix yields higher profits than focusing only on simpler items
- Introducing a premium product, even in small quantities, adds significant value
- Proper constraints and resource planning can guide small businesses toward smarter, scalable strategies

---

> _“Smart modeling helps even small businesses make big decisions.”_
