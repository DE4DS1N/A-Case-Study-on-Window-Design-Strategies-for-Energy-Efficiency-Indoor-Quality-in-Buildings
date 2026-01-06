# Numerical Investigation of Window Design Strategies for Energy Efficiency and Thermal–Visual Comfort in Buildings

This repository contains the simulation framework, methodology, and findings for a case study on window design optimization in hot and humid climates, specifically focusing on Bangladesh. The research evaluates the trade-offs between solar heat gain, cooling loads, and visual comfort across different geometric window configurations.

## Authors
- **Tahmid Talukder**
- **Md. Mahmodul Alam** (Corresponding Author: mahmod@ese.kuet.ac.bd)
- **Pronab Debnath**
- **Fahim Tanvir**
- **Nazmush Sakib**
- **Ahbab Faiyaj Haque**
- **Md. Hasan Ali**

*Department of Energy Science and Engineering, Khulna University of Engineering & Technology (KUET), Khulna-9203, Bangladesh*

## Project Overview
Window design is a critical factor in building energy performance. This study utilizes **DesignBuilder (v7.0.2)** and the **EnergyPlus** engine to perform annual simulations on a five-story institutional building (New Academic Building, Block D, KUET).

### Key Parameters Investigated
- **Window Shapes:** Rectangular (Baseline), Arched, Palladian, and Bay.
- **Glazing Types (6mm Single Glazed):** Clear, Blue, Green, Bronze, and Grey.
- **Climate Data:** Jashore, Bangladesh (ASHRAE Climate Zone 1A).
- **Metrics:** Annual cooling demand, lighting load, solar heat gain, Predicted Mean Vote (PMV), and Spatial Illuminance Distribution.



## Methodology
The research follows a five-step simulation workflow:
1. **Building Selection & Geometry:** 3D modeling of a 4920 m² institutional building.
2. **Input Parameter Definition:** Setting envelope materials, internal loads (occupancy/lighting/equipment), and HVAC split-system parameters.
3. **Simulation Execution:** Running 20 unique cases (4 shapes × 5 glazing types).
4. **Performance Evaluation:** Analyzing the balance between energy savings and indoor comfort (Thermal and Visual).
5. **Optimization:** Identifying the "Global Optimal" configuration.

## Key Findings
- **Optimal Configuration:** The **Palladian window with Green glazing** was the most efficient, reducing annual energy use by **8.56%** compared to the baseline.
- **Poorest Performer:** **Bay windows with clear glass** exhibited the highest energy consumption due to increased solar heat gain from a larger surface area.
- **IEQ Trade-offs:** Tinted glass reduces cooling loads but increases lighting energy consumption.
- **Thermal Comfort:** Palladian shapes consistently provided better thermal comfort (lower PMV) by passively moderating solar penetration.



## Simulation Software
- **Engine:** EnergyPlus
- **Interface:** DesignBuilder
- **Weather Data:** EPW (EnergyPlus Weather) format for Jashore, 2023.
