# Forest Fire Algerian ML Project

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset Description](#dataset-description)
- [Problem Statement](#problem-statement)
- [Approach](#approach)
- [Technologies Used](#technologies-used)
- [Model Performance](#model-performance)
- [How to Use](#how-to-use)
- [Examples](#examples)
- [Future Enhancements](#future-enhancements)
- [Acknowledgements](#acknowledgements)


## Project Overview
The **Forest Fire Algerian ML Project** aims to predict the likelihood and severity of forest fires in Algeria based on weather conditions and other environmental factors. The model developed can help authorities and environmental agencies take preventive measures to minimize fire risks.

---

## Dataset Description
The dataset consists of 244 instances, which include data from two regions in Algeria:

- **Bejaia Region**: Located in the northeast of Algeria.
- **Sidi Bel-abbes Region**: Located in the northwest of Algeria.

### Dataset Characteristics

- **Time Period**: The data spans from **June 2012 to September 2012**.
- **Instances**: 
  - **122 instances** for each region. 
  - **Fire cases**: 138 instances.
  - **No fire cases**: 106 instances.
- **Attributes**: The dataset has **11 attributes** and **1 target attribute** (class).

### Attribute Information

1. **Date**: Observation date in the format `DD/MM/YYYY`.  
   Includes:
   - Day
   - Month (`June` to `September`)
   - Year (2012)

2. **Temperature (Temp)**:  
   - The maximum temperature at noon, measured in degrees Celsius.  
   - Range: 22 to 42.

3. **Relative Humidity (RH)**:  
   - The relative humidity percentage.  
   - Range: 21% to 90%.

4. **Wind Speed (Ws)**:  
   - Wind speed measured in km/h.  
   - Range: 6 to 29.

5. **Rain**:  
   - Total rainfall in a day, measured in mm.  
   - Range: 0 to 16.8.

6. **Fine Fuel Moisture Code (FFMC)**:  
   - An index from the FWI system that represents moisture content in fine fuels.  
   - Range: 28.6 to 92.5.

7. **Duff Moisture Code (DMC)**:  
   - Represents the moisture content in the duff layer.  

