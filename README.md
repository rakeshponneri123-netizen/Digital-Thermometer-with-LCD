# Digital Thermometer with LCD
**Codtech IT Solutions Internship Project - Project 2**

An embedded hardware conceptual model designed to accurately measure environmental or body temperature using a thermal sensor and display the real-time readings on a Liquid Crystal Display (LCD).

## 📁 Project Submission Files
This folder contains the complete conceptual implementation details:
1. `Project_Report.txt`: Technical framework, components layout, and conversion logic.
2. `Temperature_Dataset.csv`: Sample calibrated data mapping thermal resistance to physical temperature.
3. `UI_and_Hardware_Concepts.txt`: Layout mapping of the final hardware product display interface.

## ⚡ Core Concept & Methodology
The system replaces mercury-based legacy units with a clean, electronic workflow:
- **Sensing:** A thermal transducer measures real-time physical heat and converts it into a small electrical voltage variance.
- **Processing:** A microcontroller samples this analog voltage, runs a quick mathematical correction, and maps it to Celsius or Fahrenheit scales.
- **Output Layer:** Drives a standard physical alphanumeric LCD panel to render user-readable metrics seamlessly.
