# 🚓 LA Crime Tidal Patterns

**STAT4011 Project** | Analyzing crime pattern shifts for patrol optimization
![Example of one area](./figs/Result_of_Harbor_Area.png)


## 🔍 Quick Overview
This part of project analyzed Los Angeles crime data to discover **"tidal patterns"**—systematic shifts in crime hotspots throughout the day. These patterns help optimize police patrols by predicting where crimes are most likely to occur at different times.

## 📊 Key Insight
- **Daytime**: Crime concentrates in downtown & business areas  
- **Nighttime**: Crime moves to transportation hubs & entertainment districts  
- **Interactive Maps**: For each of LA's 21 areas
  
![Tidal Pattern in LA](./figs/Tidal_Pattern.png)

## 📈 Our Method
1. **Grid-based analysis**: Split each area into equal grids
2. **Smart risk scoring**: 
   ```
   Risk = Weighted(Crime Severity + Historical Frequency)
   ```
3. **Top-5 selection**: For each time period, highlight 5 highest-risk grids

## 🚀 For Police Use
- **Better patrol schedules**: Match officers to predicted crime tides
- **Resource focus**: Concentrate on top 5 high-risk zones per shift
- **Early warning**: Spot unusual patterns
  
## 📁 What's Here
- `visualizations/` ← Interactive HTML maps (21 areas)
- `analysis/` ← Code for risk calculations

  
---
*Data: LA crime records ([2010-2019](https://data.lacity.org/Public-Safety/Crime-Data-from-2010-to-2019/63jg-8b9z/about_data) & [2020-2025](https://data.lacity.org/Public-Safety/Crime-Data-from-2020-to-Present/2nrs-mtv8/about_data)) | Course: STAT4011 Statistical Project*
