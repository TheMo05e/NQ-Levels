# 📊 NQ-Levels Dynamic Chart

NQ Levels for pivot and scalping strategies

---

## 🚀 Live Interactive Chart

Click the link below to view the fully interactive, auto-refreshing chart.

[**VIEW THE LIVE NQ-LEVELS CHART HERE**](https://TheMo05e.github.io/NQ-Levels/NQ_Levels_Chart.html)
---

## 📈 Legend Definitions



### 1. Daily Market Structure Levels


| Level | Definition |
| :--- | :--- |
| **yClose** | NQ closing price at 5:00 PM EST (the prior session's close). |
| **tOpen** | NQ opening price at 9:30 AM EST (the current session's open). |
| **HG** | Halfway between the **yClose** and **tOpen** levels. |
| **CME High** | High level encompassing the CME 95% of days span. |
| **CME Low** | Low level encompassing the CME 95% of days span. |

---

### 2. NQ Gamma Neutral Levels (Index Options)

Synthetic NQ pivots

| Category | Level | Definition |
| :--- | :--- | :--- |
| **(Live)** | **21dte** | Synthetic 21-days-to-expiration (DTE) gamma neutral level. |
| **(Live)** | **7dte** | Synthetic 7-days-to-expiration (DTE) gamma neutral level. |
| **(Live)** | **HG** | Halfway between the **(Live) 21dte** and **(Live) 7dte** levels. |
| **(O.N.)** | **21dte** | The **(Live) 21dte** level measured at 4:15 PM of the previous trading session. |
| **(O.N.)** | **7dte** | The **(Live) 7dte** level measured at 4:15 PM of the previous trading session. |
| **(O.N.)** | **NQ HG** | Halfway between the **(O.N.) 21dte** and **(O.N.) 7dte** levels (4:15 PM measurement). |
| **(Open)** | **21dte** | The **(Live) 21dte** level measured exactly at the 9:30 AM market open. |
| **(Open)** | **7dte** | The **(Live) 7dte** level measured exactly at the 9:30 AM market open. |
| **(Open)** | **NQ HG** | Halfway between the **(Open) 21dte** and **(Open) 7dte** levels (9:30 AM measurement). |

---

### 3. QQQ Gamma Neutral Levels (Dynamically Converted)

From actual QQQ options

| Category | Level | Definition |
| :--- | :--- | :--- |
| **(Live)** | **QQQ 21dte** | QQQ's 21dte gamma neutral level, dynamically converted to NQ futures points. |
| **(Live)** | **QQQ 7dte** | QQQ's 7dte gamma neutral level, dynamically converted to NQ futures points. |
| **(Live)** | **QQQ HG** | Halfway between the **(Live) QQQ 21dte** and **(Live) QQQ 7dte** levels. |
| **(O.N.)** | **QQQ 21dte** | The **(Live) QQQ 21dte** level (converted) measured at 4:15 PM of the previous trading session. |
| **(O.N.)** | **QQQ 7dte** | The **(Live) QQQ 7dte** level (converted) measured at 4:15 PM of the previous trading session. |
| **(O.N.)** | **QQQ HG** | Halfway between the **(O.N.) QQQ 21dte** and **(O.N.) QQQ 7dte** levels (4:15 PM measurement). |
| **(Open)** | **QQQ 21dte** | The **(Live) QQQ 21dte** level (converted) measured exactly at the 9:30 AM market open. |
| **(Open)** | **QQQ 7dte** | The **(Live) QQQ 7dte** level (converted) measured exactly at the 9:30 AM market open. |
| **(Open)** | **QQQ HG** | Halfway between the **(Open) QQQ 21dte** and **(Open) QQQ 7dte** levels (9:30 AM measurement). |
