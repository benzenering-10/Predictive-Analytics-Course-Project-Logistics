# Predictive-Analytics-Course-Project-Logistics
(Network Optimization, Google CoLab, AMPL, Linear Programming, Logistics, Problem Solving)

## Project Description
This predictive analytics project came in three parts. The handwritten mathematical model was required to be handwritten prior to implementing it in AMPL in Colab to solve each of the three parts. There were included markdown cells to complete that required narrative answers. Finally, the completed notebook had to be saved as a PDF for submission.

## Case Study: State Emergency Logistics Agency (SELA) Network Optimization
### Introduction
The State Emergency Logistics Agency (SELA) coordinates public sector emergency response. SELA distributes relief kits from operating facilities to various demand locations across the state. Your objective as an operations analyst is to plan this distribution network to ensure all zones receive their required kits while minimizing the total monthly cost to the agency.

This project requires you to build three models. In Part 1, you will optimize SELA's current network using a transportation linear programming model. In Part 2, you will evaluate a future expansion plan that includes candidate facilities with fixed monthly operating costs. In Part 3, you will re-solve the expansion model under a specific cost change scenario and interpret whether the expansion decision changes.

Use the canonical IDs in all models and tables:

- Existing facilities: E1, E2
- Demand locations: D1, D2, D3, D4, D5, D6
- Candidate facilities: A, B, C, D

### Part 1: Optimizing the Current Network
SELA currently operates two facilities: the Northern Emergency Depot (E1) and the Coastal Emergency Depot (E2). These two depots serve five distinct demand zones. SELA leadership wants to find the absolute lowest cost to allocate the current monthly demand across this existing network.

<img width="566" height="445" alt="image" src="https://github.com/user-attachments/assets/dcfddc96-5f2e-4efa-b591-d89757e3e4c3" />

<img width="556" height="262" alt="image" src="https://github.com/user-attachments/assets/e7a6ed7a-9d09-4e7d-b0f4-08b0b42f76da" />


