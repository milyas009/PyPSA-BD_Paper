# PyPSA-BD

## Overview
This repository presents the [PyPSA-Earth](https://github.com/pypsa-meets-earth/pypsa-earth.git) application tailored to Bangladesh. The PyPSA-Earth model has been adapted with localized power plant data, cost parameters, and regional demand profiles to develop comprehensive scenarios for the future of the Bangladesh Power Sector. The model aims to assist strategic energy planning and policy development by simulating various scenarios, including decarbonization pathways.

## Key Features
- **Localized Data**: Integration of official data from the Bangladesh Power Development Board (BPDB), Power Grid Bangladesh PLC (PGCB), and other relevant sources to accurately represent the current energy infrastructure.
- **Scenario Analysis**: Develop and analyze multiple future scenarios, including 30% and 40% clean energy targets by 2030 and 2041, respectively, and a decarbonized scenario by 2050.
- **Validation**: Model validation using 2019 data to ensure accuracy and reliability, considering disruptions in subsequent years due to the COVID-19 pandemic.

## Data Sources
  1. [Bangladesh Power Development Board (BPDB)](https://bpdb.portal.gov.bd/site/page/c4161d54-5b85-4917-a8d2-68a2d1b26dd4/%E0%A6%AE%E0%A6%BE%E0%A6%B8%E0%A6%BF%E0%A6%95-%E0%A6%AC%E0%A6%BE%E0%A6%B0%E0%A7%8D%E0%A6%B7%E0%A6%BF%E0%A6%95-%E0%A6%AA%E0%A7%8D%E0%A6%B0%E0%A6%A4%E0%A6%BF%E0%A6%AC%E0%A7%87%E0%A6%A6%E0%A6%A8)
  2. [Power Grid Bangladesh PLC](https://pgcb.gov.bd/)
  3. IRENA 2019
  4. EnerData Country Statistics
  5. Our World in Data

## How to Replicate the Model
1. Follow the installation procedure given here - [PyPSA-Earth](https://github.com/pypsa-meets-earth/pypsa-earth.git)
2. Use the config files provided for different scenario
3. Use custom power plant, cost, load data
4. Set the scenario objectives
5. Read the ]documents] (https://pypsa.readthedocs.io/en/latest/index.html) for customization of the model as required
