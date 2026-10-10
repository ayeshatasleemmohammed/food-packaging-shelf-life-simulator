# Food Packaging Shelf-Life Simulator

An interactive Excel-based tool for estimating food packaging shelf life by modelling oxygen transport through packaging films and oxygen consumption by the food.

## Overview

Food shelf life depends on several factors, including packaging material properties, film thickness, package dimensions, storage temperature, and the rate at which the food consumes oxygen.

This project provides a simple, interactive Excel tool to explore how these parameters influence oxygen levels inside a food package over a 30-day period. It connects sustainable food packaging concepts with practical calculations and data visualization.

## Features

- **Material Selection:** Choose different conventional plastic and biodegradable packaging materials using a drop-down list.
- **Dynamic Calculations:** Automatically update calculations when the packaging material, film thickness, or package dimensions change.
- **Oxygen-Level Simulation:** Track changes in package oxygen concentration over 30 days by considering oxygen entering through the packaging film and oxygen consumed by the food.
- **Temperature Warnings:** Flag storage temperatures that exceed the specified material temperature limit.
- **Low-Oxygen Alerts:** Identify when the calculated oxygen concentration reaches zero.
- **Data Visualization:** Generate a graph showing how oxygen levels change over the simulation period.

## How It Works

The simulator combines two key processes:

1. **Oxygen permeation:** Oxygen passes through the packaging film into the package. The rate depends on the material's oxygen permeability, film thickness, package dimensions, and the oxygen concentration difference across the film.
2. **Oxygen consumption:** The food consumes oxygen during storage, reducing the oxygen available inside the package.

The balance between oxygen entering the package and oxygen consumed by the food determines the predicted oxygen-level profile over time.

The simulator uses these calculations to estimate shelf life and visualize the change in oxygen concentration.

## How to Use

1. Download the Excel workbook from this repository.
2. Open it in Microsoft Excel.
3. Select a packaging material from the available drop-down list.
4. Enter or adjust the required parameters, such as film thickness and package dimensions.
5. Review the calculated results and any temperature or oxygen-level warnings.
6. Examine the 30-day graph to observe how the oxygen concentration changes over time.
7. Change the inputs to compare different packaging scenarios.

## Tools and Technologies

- Microsoft Excel
- Excel formulas and automated calculations
- Data validation and drop-down lists
- Charts and data visualization
- Conditional formatting and warning indicators

## Applications

- Exploring the influence of packaging material selection on oxygen levels.
- Comparing conventional plastic and biodegradable packaging options.
- Understanding the relationship between oxygen permeation and food respiration.
- Demonstrating the application of mass-transfer concepts in sustainable food packaging.

## Limitations

This tool provides a simplified, model-based estimate. Actual food shelf life depends on additional factors, including microbial growth, moisture transfer, food composition, storage conditions, and the integrity of the packaging.

The predicted shelf life should not be treated as a validated food-safety determination. The accuracy of the results depends on the assumptions and input data used in the workbook.

## Future Scope

Potential extensions include incorporating experimental data, additional food-quality indicators, and more detailed models of oxygen transport and food deterioration.

## Author

**Ayesha Tasleem**  
B.Tech Chemical Engineering

---

*This project was developed to apply chemical engineering and sustainable food packaging concepts through an interactive Excel simulation.*
