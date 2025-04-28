# Financial Analysis Summary
## Companies: Microsoft, Apple, Tesla
## Time period: 2022 - 2024

  <img src="https://i.imgur.com/i1WCFtB.png"/>

# Key Findings
## Revenue
df['Revenue Growth (%)'] = df.groupby('Company')['Total Revenue'].pct_change() * 100
1. **Microsoft**:
  - Revenue gre by 6.9% between 2022-2023, and 15.7% between 2023-2024. This reflects strong year over year performance
2. **Tesla**:
  - Slowed growth in 2024, 1%, compared to 2023, 18.8%
3. **Apple**:
  - Revenue dipped in 2023, -2.8%, but recovered in 2024, 18.8%.

## Net Income
df['Net Income Growth (%)'] = df.groupby('Company')['Net Income'].pct_change() * 100
1. **Microsoft**:
  - Net Income surged by 21.8% in 2024, detailing improved profitability.
 2. **Tesla**:
  - Net Income fell sharply in 2024 by 52.23%, alluding to cost challenges
 3. **Apple**:
  - Steady decline in net income during 2024 by 3.3%, possibly due to rising expenses.

## Conclusion
- Microsoft is the strongest performer, citing consistent growth, while Tesla faces profitability issues despite stable revenue. Apple on the other hand shows resilience but needs to address declining net income
