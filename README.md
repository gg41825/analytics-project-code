# Analytics Project - Warehouse Allocation & Capacitated VRP Problems


## - Example based on addresses in Aachen:
1. Retrieved Aachen addresses from websites and extracted corresponding zip codes from geometry values.
2. Distance Calculation: Calculated distances between locations using the `geopy.geocoders` library, based on the WGS-84 ellipsoidal model.
3. Demand Generation: Generated realistic demand values (600–20,000 KG), taking vehicle capacity constraints (800–20,000 KG) into account.
4. Vehicle Cost: Estimated based on average compensation rates for each vehicle type.
5. Gate Allocation: Assigned 3 gates for demonstration purposes to reduce computational resource usage.



Note: All confidential data has been removed or regenerated, and columns have been renamed. This visualization displays only aggregated or average values.

```
Steps to run:
1. Run `01_address_preprocess.ipynb`
2. Run `02_warehouse_and_cvrp_gurobi.ipynb`
```