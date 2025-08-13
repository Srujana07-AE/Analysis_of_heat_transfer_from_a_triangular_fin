# Analysis_of_heat_transfer_from_a_triangular_fin

## 📌 Problem Statement
A triangular fin with a **base temperature** of **356 K** loses heat by conduction and convection to surrounding air at **294 K**.  
The fin has a **heat transfer coefficient** of **95 W/m²·K**.  
Due to its geometry, the **cross-sectional area tapers linearly** from the base to the tip.  

The objective is to determine the **temperature at the two corner tips** of the fin’s free end.

## Given Data
- **Base temperature (T_base)**: 356 K  
- **Ambient temperature (T_∞)**: 294 K  
- **Heat transfer coefficient (h)**: 95 W/m²·K  
- **Fin type**: Triangular, linearly tapering cross-section  
- **Unknowns**:  
  - Temperature at corner tip 1 (**T1**)  
  - Temperature at corner tip 2 (**T2**)

##  Objectives
- Model the triangular fin geometry in **ANSYS DesignModeler**
- Apply material properties and boundary conditions
- Simulate **combined conduction and convection**
- Extract **T1** and **T2** at the free end

## Tools & Software
- **ANSYS Workbench**  
  - **DesignModeler** – geometry creation  
  - **Steady-State Thermal** solver – simulation  
- **Units**: SI (m, K, W)


## 📂 Repository Structure
