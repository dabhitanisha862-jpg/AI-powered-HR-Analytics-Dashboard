# AI-powered-HR-Analytics-Dashboard
"Interactive Power BI HR Analytics Dashboard using built-in AI machine learning visuals (Key Influencers & Decomposition Tree). Programmatically identifies primary drivers of employee attrition (Age ≤ 21, Overtime, Low Income) and maps operational turnover risk profiles across company departments."
## 🤖 Advanced Machine Learning & AI Insights Page
To move beyond historical descriptive reporting, the dashboard leverages native Power BI AI/ML visualization capabilities (**Key Influencers** and **Decomposition Trees**) to isolate the true root causes driving employee turnover (`Attrition = Yes`).

![AI Insights Preview](AI_Insights.PNG)

### 📊 Statistical Key Influencers (ML Driver Analysis)
The Key Influencers visual computes the relative risk multiplier for various employee attributes. The top statistical triggers that increase the likelihood of attrition are:

1. **Sum of Age is 21 or less (3.57x Multiplier):** Younger employees are the single highest flight-risk cohort. The dashboard's ML-generated age bins show that attrition in this group sits well above the organization's baseline average of **15.01%**.
2. **OverTime is Yes (2.96x Multiplier):** Employees regularly logging overtime are nearly 3 times more likely to leave, signaling potential burnout trends.
3. **Sum of YearsAtCompany is 1 or less (2.71x Multiplier):** Early tenure onboarding churn is highly significant.
4. **JobRole is Sales Representative (2.68x Multiplier):** Specifically highlights high role-based volatility within the sales function.
5. **Sum of MonthlyIncome is 2800 or less (2.60x Multiplier):** Compensation gaps below this threshold strongly influence a departure decision.
6. **JobRole is Laboratory Technician (1.65x Multiplier):** R&D operational roles showing elevated turnover baseline risks.

---

### 🌲 Root-Cause Breakdown (Decomposition Tree)
The right-hand side of the canvas features an interactive **AI Decomposition Tree** that dynamically breaks down the total **Count of Attrition (1,480 total tracked instances)** into organizational branches to isolate volume hotspots:

* 🔬 **Research & Development:** 967 Attrition Cases
* 💼 **Sales:** 450 Attrition Cases *(Matches the 450 employee scope from the main dashboard overview)*
* 👥 **Human Resources:** 63 Attrition Cases

---

## 💡 Strategic Data-Driven Recommendations
Based on the machine learning outputs from this screen, HR leadership should focus on three immediate target actions:
* **Overhaul Early Onboarding:** Introduce dedicated mentorship frameworks within the first year (YearsAtCompany ≤ 1) to cushion early-stage attrition.
* **Overtime Interventions:** Establish systemic work-hour caps or implement automatic wellness flags for roles reporting excessive overtime hours.
* **Targeted Retention in R&D and Sales:** Deploy targeted compensation benchmarks or career-progression tracking for Laboratory Technicians and Sales Representatives under the $2,800 monthly income threshold.
