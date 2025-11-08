Energy Mix Optimization Model

This project focuses on developing a cost-efficient and sustainable power system planning model using Linear Programming. The primary goal is to identify an optimal mix of solar power, gas-based generation, and battery storage systems to reliably meet a specified hourly power demand while minimizing total investment and operational expenses. The model considers practical challenges such as fluctuating renewable availability, battery efficiency constraints, and the need to maintain power balance at every hour.

A 24-hour dispatch schedule is integrated into the model to ensure realistic energy flow behavior throughout the day and night. The system prioritizes renewable usage by enforcing a minimum renewable energy share of 75%, which directly contributes to reducing dependence on fossil fuels. Battery storage enhances reliability by storing excess solar output during peak production hours and supplying stored energy when solar availability declines.

The implementation is done in Python using the Pyomo optimization framework. Multiple solver backends, including Gurobi, CBC, and GLPK, are supported to provide flexibility and performance benchmarking across commercial and open-source solvers. Data handling is performed using pandas, and visualizations of results are generated using matplotlib.

Insights from the model indicate that a combination of high solar power capacity and sufficient battery storage is the most cost-effective strategy, while gas generation remains a secondary and supportive source for reliability. This approach ensures cleaner power generation and enhances long-term sustainability by reducing emissions and fossil fuel dependency.

This repository includes source code for optimization, utility functions for loading data and exporting results, placeholder folders for input datasets and generated outputs, and optional Jupyter notebooks for further experimentation. Anyone interested in renewable integration, smart energy systems, or optimization modeling can explore, run, and extend this project to support real-world decision making.
