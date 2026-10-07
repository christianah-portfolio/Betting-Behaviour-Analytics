# Betting Addiction Among Nigerians Dashboard

**An interactive Excel dashboard that compares betting habits, addiction scores, and financial debt across six Nigerian cities and six betting platforms.**

![Betting Addiction Dashboard](https://github.com/christianah-portfolio/Betting-Behaviour-Analytics/blob/main/01_betting_dashboard.png)

---

## Project Overview

**Brief Description**
An interactive Excel dashboard analysing betting behaviour, addiction scores, and financial debt for 2,000 bettors across six cities and six betting platforms.

**Tools & Skills Used**
Excel, Power Query, Pivot Tables, Pivot Charts, Slicers, KPI Cards, Data Cleaning, Data Storytelling.

**Project Goals**
To explore how betting habits and addiction levels differ by city and platform, and to show how common financial debt is among bettors.

**Results**
Over 60% of bettors reported financial debt. The average addiction score was 5.54 out of 10, with Ibadan the highest city (5.72) and Bet9ja users betting most often (13.49 bets a week) and scoring highest on addiction among platforms (5.68).

---

## Business Problem

Betting can lead to money problems and harm to work and relationships. To plan awareness or support programmes, it helps to know where betting is heaviest, which platforms are linked to higher addiction scores, and how many bettors are in debt. I built one dashboard to answer three questions:

1. How often do people bet, and how high are their addiction scores?
2. Do the numbers differ by city or by betting platform?
3. How common is financial debt, and who is affected?

---

## Key Findings

| Finding | Detail |
|---|---|
| Financial debt is common | **1,204 of 2,000** bettors (**60.2%**) reported financial debt |
| Men and women are almost equally affected | Of the 1,204 bettors with debt, **610** are men (50.7%) and **594** are women (49.3%) |
| Addiction scores sit near the middle of the scale | The average was **5.54 out of 10** |
| Ibadan and Lagos have the highest addiction scores | Ibadan **5.72**, Lagos **5.70**; the lowest were Kano (5.35) and Enugu (5.36) |
| Bet9ja stands out on both measures | Highest average bets per week (**13.49**) and highest addiction score (**5.68**) among platforms; SportyBet had the lowest addiction score (5.31) |
| Weekly betting is similar across cities | Enugu **13.50**, Lagos 13.46, Kano 13.43, down to Port Harcourt at **12.29** |

On average, bettors placed **13.12 bets a week**. The differences between cities and platforms are small, so they should be read as patterns to watch and not as strong conclusions.

---

## Recommendations

1. **Make awareness and support programmes broad.** With 6 in 10 bettors reporting debt, and small differences between groups, wide-reaching programmes are likely to help more than narrow targeting.
2. **Prioritise Ibadan and Lagos** when choosing where to start, since they have the highest addiction scores.
3. **Look more closely at Bet9ja users.** They bet most often and score highest on addiction, so they are a sensible group to study further.
4. **Collect more data before drawing firm conclusions.** Ask about causes, such as income and time spent betting, because the dashboard shows patterns but not reasons.

---

## Dashboard

The dashboard is built in Excel and includes:

- **KPI cards:** average weekly bets, total bettors (2,000), average addiction score
- **Bet platform analysis:** average weekly bets and addiction score by platform
- **Financial debt analysis:** debt status (yes or no) and the gender of bettors with debt
- **Region analysis:** average weekly bets and addiction score by city
- **Slicers** to filter the whole dashboard by city and betting platform

![Betting Addiction Dashboard](https://github.com/christianah-portfolio/Betting-Behaviour-Analytics/blob/main/01_betting_dashboard.png)
---

## Dataset

A dataset of **2,000 bettors** with 17 columns and no missing records:

- **Profile:** age group, gender, city, monthly income
- **Betting habits:** average bets per week, average bet amount, hours spent betting per week, years betting, most used betting app
- **Impact:** addiction level (1 to 10), financial debt, effect on work, strained relationships, awareness of risk, whether they have stopped betting before

The six cities are Abuja, Enugu, Ibadan, Kano, Lagos, and Port Harcourt. The six platforms are 1xBet, Bet9ja, BetKing, Betway, NairaBet, and SportyBet.

---

## Approach

1. **Explored** the dataset to understand each column and what it measures.
2. **Cleaned and prepared** the data by eliminating duplicates, trimming hidden spaces, and standardizing text casing to ensure data integrity.
3. **Summarised the data** with Pivot Tables, and turned each summary into a Pivot Chart.
4. **Built KPI cards** for average weekly bets, total bettors, and average addiction score.
5. **Added slicers** for city and platform, and connected them to every chart so the whole dashboard filters together.
6. **Wrote the findings and recommendations** from what the charts show.

---

## Limitations

- The differences between cities and platforms are small, so they do not prove that one city or platform causes more addiction.
- The addiction score is a single number from 1 to 10, and the dashboard does not show how it was measured.
- The data shows patterns but not causes.

---

## Project Files

```
betting-behaviour-analytics/
├── README.md
├── dashboard/
│   └── Betting_Addiction_Dashboard.xlsx
└── dashboard-pages/
    └── 01_betting_dashboard.png
```
