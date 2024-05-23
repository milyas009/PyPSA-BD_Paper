# PyPSA-BD

## Overview
This repository presents the PyPSA-Earth application tailored to the context of Bangladesh. The PyPSA-Earth model has been adapted with localized power plant data, cost parameters, and regional demand profiles to develop comprehensive scenarios for the future of the Bangladesh Power Sector. The model aims to assist strategic energy planning and policy development by simulating various decarbonization pathways.

## Key Features
- **Localized Data**: Integration of official data from the Bangladesh Power Development Board (BPDB) and other relevant sources to accurately represent the current energy infrastructure.
- **Scenario Analysis**: Development and analysis of multiple future scenarios, including 30% and 41% clean energy targets by 2030 and 2041, respectively, and a net-zero emission scenario by 2050.
- **Detailed Modeling**: Incorporation of regional demand profiles, investment costs, operational costs, and technical constraints specific to Bangladesh.
- **Validation**: Model validation using 2019 data to ensure accuracy and reliability, considering disruptions in subsequent years due to the COVID-19 pandemic.

## Scenarios
1. **Reference Scenario (2019)**: Baseline scenario for model validation, using data from BPDB reports.
2. **MCPP-I (2030)**: Scenario aligned with the Mujib Climate Prosperity Plan (MCPP) targeting a 30% share of clean energy.
3. **MCPP-II (2041)**: Expanded MCPP scenario with 41% clean energy, coal exit, and introduction of battery storage.
4. **Net Zero Emission (2050)**: Ambitious scenario aiming for 100% renewable energy with a mix of solar, wind, nuclear, and advanced storage solutions.

## Model Validation
- **Network Topology and Length**: Validation of transmission network length across various voltage levels against PGCB data.
- **Electricity Consumption**: Comparison of annual electricity demand with various sources to ensure model accuracy.
- **Installed Capacity**: Validation of generation capacity across different sources using BPDB and IRENA data.

## Figures
- **Power Generation Dispatch**: Visualization of the contributions from various energy sources to meet electricity demand
- ![image](https://github.com/FiruzAhamed/PyPSA-BD/assets/122635742/bc96a872-e21f-41a8-93f2-556a265fae74)
- **Geographic Distribution**: Map showing the distribution of generation technologies across Bangladesh
- ![image](https://github.com/FiruzAhamed/PyPSA-BD/assets/122635742/23d84919-b0d6-449c-8b36-824e53306e1e)

## Data Sources
  1. Bangladesh Power Development Board (BPDB)
  2. IRENA 2019
  3. EnerData Country Statistics
  4. Our World in Data
     
## Contact
**Firuz Ahamed Nahid**  
Postdoctoral Researcher  
South and South East Asia Multidisciplinary Applied Research Network on Transforming Societies of Global South (SMARTS)  
[https://smartscenter.ait.ac.th/](https://smartscenter.ait.ac.th/)  
Asian Institute of Technology  
58 Moo 9, Paholyothin Highway, Khlong Luang, Pathum Thani 12120, Thailand  
Email: [firuz@ait.asia](mailto:firuz@ait.asia)
