# Predictive-Analytics-Course-Project-Logistics
(Network Optimization, Google CoLab, AMPL, Linear Programming, Logistics, Problem Solving)

## Project Description
This predictive analytics project came in three parts. The handwritten mathematical model was required to be handwritten prior to implementing it in AMPL in Colab to solve each of the three parts. There were included markdown cells to complete that required narrative answers. Finally, the completed notebook had to be saved as a PDF for submission. The final PDF export must show mathematical formulations, AMPL code, solver output, network flow tables, and written interpretations.

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


### Part 2: Planning for Expansion
SELA expects demand for relief kits to increase across all current zones. They also need to add a new coverage area: the Desert Response Zone (D6).

The two existing facilities will remain operational, but their current capacity cannot handle the projected future demand. SELA has identified four candidate facilities to absorb the excess demand. Each candidate facility has a monthly capacity and a fixed monthly operating cost. SELA incurs this fixed cost only if they choose to open that specific facility.

<img width="610" height="517" alt="image" src="https://github.com/user-attachments/assets/6d35bbe5-a903-48a5-9ec2-4cd0425b6187" />

<img width="659" height="522" alt="image" src="https://github.com/user-attachments/assets/38dd2264-ec51-4dcd-9cf2-02d4882cff85" />


### Part 3: Scenario and Risk Analysis
Facility expansion is a long-term commitment. SELA leadership wants to test the robustness of the expansion plan against potential disruptions.

In this scenario, a new mutual aid agreement lowers the unit transportation costs from the Coastal and Inland depots to the Coastal and Highland zones. Concurrently, severe road damage adds a routing surcharge on the northern routes traveling to the Urban and Central zones.

<img width="639" height="522" alt="image" src="https://github.com/user-attachments/assets/30db1432-e99f-40d2-8dd7-334defed93be" />

<img width="723" height="211" alt="image" src="https://github.com/user-attachments/assets/6ee586f0-6e34-48ab-83ce-21cc5e4ebfac" />




