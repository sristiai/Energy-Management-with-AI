# Energy optimization system using AI
This project designs and simulates an energy system to supply district heating and electricity to a residential area in Schwandorf, Germany. It integrates multiple energy sources including rooftop photovoltaic systems, air-source heat pumps, thermal and battery storage, and backup systems like boilers and combined heat and power (CHP) units. The system aims to achieve cost-effective and environmentally sustainable energy solutions while adhering to German regulations limiting fossil fuel usage to a maximum of 35%.

<p align="center">
  <img width="644" alt="emi" src="https://github.com/user-attachments/assets/12733dcf-de81-4a25-b172-919f9a52e1ea" />
</p>

---

## Objectives
- Efficiently meet thermal and electrical energy demands.
- Optimize system performance under different scenarios.
- Minimize CO₂ emissions and operational costs.
- Ensure compliance with German energy regulations.

---

## Key Features
- **Renewable Integration:** Utilizes rooftop PV systems and heat pumps for sustainable energy generation.
- **Backup Systems:** Incorporates high-efficiency boilers and CHP units with limited fossil fuel usage.
- **Optimization Framework:** Employs Python and OEMOF toolbox for scenario analysis and cost optimization.

---

## Scenarios Analyzed
1. **Baseline Model:** No constraints on fossil fuel usage.
2. **Fossil Fuel Constraint:** Limits fossil fuel usage to 35%.
3. **Renewable Integration:** Combines fossil fuel constraints with increased renewable electricity.

---

## Results Summary
- **Scenario 1:** Lowest cost but highest CO₂ emissions.
- **Scenario 2:** Most cost-effective but higher environmental impact.
- **Scenario 3:** Most sustainable with lowest CO₂ emissions but higher costs.
