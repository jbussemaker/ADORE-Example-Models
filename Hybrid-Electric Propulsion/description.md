# Hybrid-Electric Propulsion Architecture Optimization

This model was created to demonstrate the implementation of a realistic architecture optimization problem implemented in ADORE. The design problem includes choices for:
- The number of propellers (1 to 5 per wing)
- For each propeller, the source of its mechanical power: electric motor, gas turbine, or both (hybrid)
- The amount of propeller blades (3 or 4), applied to all propellers
- If any of the mechanical power sources for the propellers needs electricity, a choice on the source of the electric power: batteries, gas turbine, or both (hybrid)
- If the mechanical power is hybrid: the mechanical Degree of Hybridization for each of the 7 mission segments
- If the electrical power is hybrid: the electrical Degree of Hybridization for each of the 7 mission segments
- Time coefficient to bias the inner optimization loop towards flight-time minimization

[Mahmoud Fouda, Eytan J. Adler, et al., "Automated Hybrid Propulsion Model Construction for Conceptual Aircraft Design
and Optimization", 33rd Congress of the International Council of the Aeronautical Sciences (ICAS), Stockholm, Sweden,
September 2022.](https://www.researchgate.net/publication/363405270_Automated_hybrid_propulsion_model_construction_for_conceptual_aircraft_design_and_optimization)

[Bussemaker, J.H., Sánchez, R.G., Fouda, M., Boggero, L. and Nagel, B., 2023, July. Function-Based Architecture Optimization: An Application to Hybrid-Electric Propulsion Systems. In INCOSE International Symposium (Vol. 33, No. 1, pp. 251-272).](https://elib.dlr.de/196233/)
