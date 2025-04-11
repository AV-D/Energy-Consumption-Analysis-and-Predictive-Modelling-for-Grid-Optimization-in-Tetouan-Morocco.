# Energy-Consumption-Analysis-and-Predictive-Modelling-for-Grid-Optimization-in-Tetouan-Morocco.

## Executive Report: Analysis of Tétouan City Energy Consumption

---

### **1. Overview of the Study**
This report presents key findings from an in-depth analysis of energy consumption in Tétouan, Morocco. The dataset used for this analysis contains 52,416 observations recorded at 10-minute intervals, covering electricity consumption across three zones (Quads, Smir, and Boussafou) managed by Amendis. The study aims to uncover trends in electricity demand and identify factors influencing consumption.

---

### **2. Key Findings**

#### **A. Electricity Consumption Trends**
- **Average Power Consumption:** 
  - Zone 1: 32,344 kW
  - Zone 2: 21,042 kW
  - Zone 3: 17,835 kW
- **Peak Demand:** 
  - Zone 1 reached a maximum of 52,204 kW.
  - Zone 2 peaked at 37,408 kW.
  - Zone 3 recorded a maximum of 47,598 kW.
- **Seasonal Variations:** Electricity demand exhibited significant fluctuations influenced by temperature and humidity levels.

#### **B. Environmental Factors Impacting Consumption**
- **Temperature:** Average temperature was $$18.81^\circ C$$, with a range from $$3.25^\circ C$$ to $$40.01^\circ C$$. Higher temperatures correlated with increased electricity usage due to cooling demands.
- **Humidity:** Average humidity was $$68.26\%$$, with higher humidity levels showing a moderate impact on energy consumption patterns.
- **Diffuse Energy Flows:** General diffuse flows (average: $$182.7$$) and diffuse flows (average: $$75.0$$) were analyzed to understand their role in solar energy distribution and its indirect effects on power demand.

#### **C. Temporal Patterns**
- Electricity consumption was higher during working hours and weekdays compared to weekends.
- Seasonal peaks were observed during summer months due to increased cooling needs.

---

### **3. Operational Insights**

#### **A. Energy Distribution by Zones**
- Zone 1 consistently had the highest energy demand, followed by Zones 2 and 3.
- Disparities in consumption between zones suggest varying population densities or industrial activities.

#### **B. Impact of Weather Conditions**
- High temperatures and low wind speeds were associated with increased electricity usage.
- The influence of diffuse solar radiation on heating and cooling demands highlights the importance of integrating renewable energy sources into the grid.

#### **C. Efficiency Opportunities**
- The data indicates potential inefficiencies during peak demand periods that could be addressed through load balancing or infrastructure upgrades.
- Renewable energy integration (e.g., solar) is recommended to offset high energy demands during summer months.

---

### **4. Recommendations**

1. **Infrastructure Enhancements:**
   - Upgrade the electricity distribution network in high-demand areas to prevent overloading.
   - Implement smart grid technologies for real-time monitoring and load management.

2. **Renewable Energy Integration:**
   - Leverage solar energy by capitalizing on Tétouan's diffuse solar radiation levels.
   - Explore incentives for residential and industrial solar panel installations.

3. **Demand-Side Management:**
   - Promote energy efficiency programs targeting peak hours.
   - Encourage the use of energy-efficient appliances among consumers.

4. **Weather-Based Forecasting Models:**
   - Develop predictive models incorporating temperature, humidity, and solar radiation data to optimize electricity supply planning.

---

### **5. Conclusion**
The analysis highlights critical insights into Tétouan's electricity consumption patterns and their dependence on environmental factors. Strategic investments in infrastructure, renewable energy adoption, and demand-side management can enhance the city's energy resilience while meeting growing demands sustainably.
 
## **Technical Report**

### **1. Introduction**
Tétouan City faces growing energy demands due to population growth (1.96% annually) and its Mediterranean climate. With Morocco's reliance on imported oil products and below-average per capita electricity consumption (900 kWh), optimizing energy usage is critical for sustainability.

This report analyzes Tétouan's energy consumption patterns using SCADA data from Amendis to provide actionable insights for improving efficiency and integrating renewable energy solutions.

---

### **2. Methodology**
- **Data Source**: The dataset contains 52,416 observations recorded at 10-minute intervals over multiple years.
- **Data Preprocessing**: Missing values were handled through interpolation; outliers were identified using statistical thresholds.
- **Tools Used**: Python libraries such as Pandas (data manipulation), Matplotlib/Seaborn (visualization), and Scikit-learn (correlation analysis).
- **Analysis Focus Areas**:
  - Temporal trends in energy consumption across zones.
  - Correlations between environmental factors (temperature, humidity, wind speed) and power demand.
  - Impacts of solar radiation metrics (General Diffuse Flows and Diffuse Flows).

---

### **3. Results and Analysis**

#### **3.1 Energy Consumption Trends**
- **Daily Patterns**: Higher demand during working hours; reduced usage at night.
- **Seasonal Variations**: Increased consumption during extreme temperatures in summer (cooling) and winter (heating).

#### **3.2 Environmental Influences**
- Temperature shows a strong positive correlation with power demand ($$r = +0.8$$).
- Humidity has a moderate impact ($$r = +0.4$$), while wind speed has minimal influence ($$r = +0.2$$).
- Solar radiation stabilizes temperature variations but indirectly affects heating/cooling needs.

#### **3.3 Zone-Specific Insights**
- Zone 1 consistently records the highest power usage due to its likely higher population density or industrial activity.
- Zones 2 and 3 exhibit balanced but lower consumption levels.

#### **3.4 Visualizations**
Key visualizations include:
- Line charts showing daily/seasonal trends in power demand across zones.
- Heatmaps illustrating correlations between environmental factors and energy consumption.
- Bar charts comparing zone-wise average power usage.

---

### **4. Recommendations**

#### **4.1 Energy Efficiency Programs**
- Launch initiatives targeting high-consumption areas like Zone 1 to promote energy-efficient appliances.
- Encourage adoption of rooftop solar panels in residential areas to reduce grid dependency.

#### **4.2 Infrastructure Improvements**
- Upgrade the electricity distribution network to handle peak loads effectively.
- Deploy smart grid technologies for real-time monitoring and optimization of electricity flow.

#### **4.3 Renewable Energy Integration**
- Utilize solar radiation data (General Diffuse Flows) to strategically deploy photovoltaic systems.
- Invest in renewable energy projects to reduce reliance on imported oil products.

#### **4.4 Demand Forecasting**
- Develop machine learning models for accurate electricity demand forecasting based on historical trends and environmental variables.
- Implement dynamic pricing strategies to incentivize off-peak electricity usage.

#### **4.5 Cost-Benefit Analysis**
For each recommendation:
- Assess potential cost savings from reduced peak loads or renewable energy adoption.
- Calculate ROI, payback periods, or net present value (NPV) of proposed solutions.

---

### **5. Limitations**
The analysis is subject to the following limitations:
1. Data granularity may not fully capture short-term fluctuations in power demand.
2. External factors like policy changes or economic growth were not considered in this study.
3. Solar radiation metrics require further validation for their impact on renewable energy potential.

---

### **6. Conclusion**
This report highlights critical insights into Tétouan City's energy consumption dynamics and provides actionable recommendations for improving efficiency, managing peak loads, and integrating renewable energy solutions. By addressing these challenges, Tétouan can move toward a more sustainable and resilient energy future.




