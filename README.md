# Investigating High Traffic Indicators on Westbound I-94

This project analyzes hourly traffic data collected between 2012 and 2018 along the westbound I-94 corridor near Minneapolis-St. Paul. By uncovering the factors that contribute to high traffic volume, this project aims to support better planning, safety, and efficiency on this critical highway.

---

## 📌 Table of Contents

1. [Introduction](#introduction)
2. [Objective](#objective)
3. [Stakeholders](#stakeholders)
4. [Use Case](#use-case)
5. [Why I-94?](#why-i-94)
6. [Dataset Overview](#dataset-overview)
7. [Key Insights](#key-insights)
    - [Time-Based Indicators](#time-based-indicators)
    - [Weather Indicators](#weather-indicators)
    - [Holiday Patterns](#holiday-patterns)
8. [Conclusion](#conclusion)
9. [Future Directions](#future-directions)
10. [How to Run](#how-to-run)

---

## 🛣️ Introduction

Interstate 94 (I-94) is a major transportation artery through the American Midwest, stretching 1,585 miles from Billings, Montana, to Port Huron, Michigan. The stretch between Minneapolis and St. Paul is particularly known for its heavy traffic.

---

## 🎯 Objective

To identify key factors that influence high traffic volume on westbound I-94 using data from 2012 to 2018. This includes analyzing time-of-day trends, weather conditions, and holiday impacts on traffic patterns.

---

## 👥 Stakeholders

- **Transportation agencies** – to implement data-driven traffic mitigation strategies.
- **Urban planners** – to optimize future infrastructure design.
- **Logistics companies** – to streamline delivery routes.
- **Commuters** – to better anticipate peak congestion times.

---

## 💼 Use Case

This project can be used to:

- Predict periods of high traffic volume.
- Reveal the effects of weather, time, and holidays on congestion.
- Support smarter decisions in urban mobility, logistics, and public planning.

---

## 🌆 Why I-94?

- **Strategic Connectivity**: Links major Midwestern cities like Minneapolis, Milwaukee, and Chicago.
- **Economic Impact**: Facilitates high-volume freight movement.
- **Congestion Hotspot**: The Minneapolis–St. Paul segment is notorious for westbound traffic congestion.

---

## 🗃️ Dataset Overview

- **Source**: [Metro Interstate Traffic Volume dataset](https://archive.ics.uci.edu/ml/datasets/Metro+Interstate+Traffic+Volume) by John Hogue (UCI ML Repository).
- **Timeframe**: 2012–2018
- **Scope**: Hourly westbound traffic volumes near Minneapolis-St. Paul
- **Features Include**:
  - Time (hour, day of week, month)
  - Weather (temperature, precipitation, weather type)
  - Holiday indicator

---

## 📊 Key Insights

### ⏰ Time-Based Indicators

- **Daytime traffic** is significantly higher than nighttime.
- **Peak hours**: Morning (6 AM) and evening (5 PM), especially on weekdays.
- **Fridays** show particularly high traffic volume.
- **Weekend traffic** is more evenly distributed, peaking around midday.
- **Seasonal patterns**: Highest traffic occurs from March to October.

### 🌧️ Weather Indicators

- **Overall weak correlation** between weather and traffic volume.
- Certain adverse weather types (e.g., light snow, thunderstorms) surprisingly coincide with **high traffic averages**, indicating that traffic continues despite poor conditions.

### 🗓️ Holiday Patterns

- **Lower average traffic** on most U.S. holidays.
- **New Year’s Day** is an exception, with the **highest average traffic volume**.
- **Memorial Day** and **Independence Day** show elevated traffic, but with more variability.
- **Thanksgiving** and **Christmas** see relatively **lower volumes**, possibly due to early travel or fewer commuters.

---

## ✅ Conclusion

This analysis highlights key indicators of high traffic on westbound I-94:

- Time-based factors (hour, day, month) have a strong influence on traffic patterns.
- Weather plays a lesser role but shows surprising exceptions during certain conditions.
- Holiday traffic tends to dip—except for New Year's Day and a few other key dates.

These insights provide a data-driven foundation for improving traffic flow, enhancing infrastructure planning, and supporting daily commute decisions.

---

## 🔭 Future Directions

To build on this work, future analysis could explore:

- **Real-time data integration** for live predictions.
- **Accident reports and roadwork data** to refine traffic estimations.
- **Vehicle type segmentation** for more granular insights.
- **Geospatial analysis** to detect location-specific congestion hotspots.

---

## 🚀 How to Run

To explore the project locally:

1. **Clone the repository**:

   ```
   git clone https://github.com/yourusername/i94-traffic-analysis.git
   cd i94-traffic-analysis
   ```
