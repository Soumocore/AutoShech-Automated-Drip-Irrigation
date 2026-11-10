# AutoShech: automated, low-cost drip irrigation

A soil-moisture-controlled drip irrigation prototype designed for small farms and domestic use, built as a group capstone project at Adamas University (2022–2024). The design is meant to be paired with solar power.

**Project report:** [`report/AutoShech_Capstone_Report.pdf`](report/AutoShech_Capstone_Report.pdf)

## How it works
A soil-moisture sensor is read by an Arduino Uno. When moisture falls below a set threshold, the Arduino switches a relay that turns the water pump on. When moisture is restored, the pump switches off. An LCD shows the soil status and pump state.

## Components (about Rs 3,320 in total)
Arduino Uno, soil-moisture sensor, 5V relay module, 6–12V water pump (~100 L/h), 16x2 I2C LCD, jumper wires, 9V battery.

## What was tested
- **Soil tests:** absorption, texture and pH of five soil samples from the university campus. All samples were close to neutral pH (about 7).
- **Plant trial:** a garden croton sapling in campus soil, followed over about 12 weeks. The report records healthy leaves, even moisture with no pooling, and water use rising from about 50 to 65 mL/day as the plant grew.

## Figures
- [Working mechanism and design](figures/working_mechanism_and_design_report_p6.png)
- [Model and project progress](figures/model_and_progress_report_p7.png)
- [Prototype testing](figures/prototype_testing_report_p8.png)
- [Final product and growth data](figures/final_product_and_growth_data_report_p11.png)

## Limitations (stated honestly)
- The trial was a single plant with no side-by-side comparison against manual or conventional irrigation, so **water savings were not measured**. The 50–70% savings quoted in the report come from published studies, not from this prototype.
- Control is simple threshold logic on one sensor. It does not use machine learning.
- Solar power and fertigation are part of the design vision, not features that were tested.

## Future plans (from the report)
Remote monitoring web app, emitter unclogging mechanism, patent application and market research.

## My role
[Describe what you personally did, for example design, assembly, testing, soil analysis or reporting.]

## Team
Group project by a team of 23 B.Tech Biotechnology students, Adamas University. Team names are omitted from this copy of the report.
