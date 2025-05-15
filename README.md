# Lyft_DS_CLTVAnalysis_forDrivers
This project is independently created using publicly available data. It is not affiliated with or endorsed by Lyft
This project explores and analyzes Lyft's driver behavior data to estimate Driver Lifetime Value (LTV) and uncover the factors that impact it. The goal is to empower Lyft with actionable insights for improving driver retention, targeting high-value drivers, and boosting revenue — all through the lens of data science + business strategy.

🧠 Cluster Analysis & Strategic Personas

Using K-Means clustering, we segmented drivers into distinct behavioral clusters based on lifetime value, ride engagement, and time-based activity patterns:
| Cluster | Driver Persona           | Characteristics                                                                                                   |
| ------- | ------------------------ | ----------------------------------------------------------------------------------------------------------------- |
| **1**   | 💎 **Excellent Drivers** | Highest total LTV, most rides, long active duration, consistent performance and strong earnings.                  |
| **2**   | 🟢 **Good Drivers**      | Strong ride activity and earnings, slightly below Cluster 1. High potential for growth with the right incentives. |
| **0**   | 🟡 **Fair Drivers**      | Moderate ride frequency and engagement. Represent a large segment with room for improvement.                      |
| **3**   | 🔴 **Low-Value Drivers** | Short driving duration, low ride counts and earnings. Often churn early or show inconsistent patterns.            |

💡 Actionable Recommendations

📍 1. Retain the Elite (Cluster 1)
Prioritize retention strategies (loyalty perks, exclusive bonuses) to retain high-performing drivers. They generate outsized LTV and represent Lyft’s best assets.

📍 2. Nurture the Good & Fair (Cluster 2 & 0)
Introduce targeted nudges, coaching, and ride incentives to improve performance. These segments have the potential to move into the top tier with appropriate support.

📍 3. Recover At-Risk Drivers (Cluster 3)
Identify the pain points behind low engagement. Consider onboarding redesigns, early incentives, or re-engagement campaigns to prevent early drop-off.

📍 4. Personalized Incentives
Use clusters to design performance-based bonuses. For example, high-frequency night drivers may respond well to late-night surge pricing boosts.

📍 5. Dynamic Pricing Based on Cluster Mix
Integrate cluster personas into zone-based dynamic pricing, optimizing supply-demand balance by prioritizing high-value drivers in key areas.

📍 6. Monitor & Re-cluster Periodically
Behavior evolves. Establish a cadence (e.g., monthly or quarterly) to recompute clusters and dynamically update engagement strategies.

✨ Business Value

This analysis goes beyond clustering — it defines clear, action-ready personas, each mapped to high-impact retention and monetization strategies Lyft can implement.
