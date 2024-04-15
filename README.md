# Paper-Operative-Analysis-of-EVCCM-C-D-coordination-
Paper: "Operative Analysis of Electric Vehicle Controlled Charging Management: Centralized - Decentralized coordination"

# Highlights

* Geographic and travel patterns characterize behavioral groups of electric vehicles
* Grouping characterization keeps measures neutrality, serving as base information
* Decentralized charging management is modified under coordination constrains
* Centralized charging management operator coordinates the electric market operation
* Data analysis, mining and synthesis allows the distribution power system analysis

# [Graphical Abstract](.//DB/GA.png)

![Graphical Abstract](.//DB/GA.png)

# [Data Base Presentation](.//DB/DB%20Readme.md)
The present Data Base represents the minimum information data required for verification (under research team consideration). This is shown as practical application based in the next case.

A distribution Network Operator (From now on DNO) is  in charge of power system planning (based mainly in its [IEEE 14 bus power system transmission network](.//DB/Power%20System%20Data/)).

![IEEE 14 Power System](.//DB/Power%20System%20Data/IEEE14BUSunifilar.PNG)

In order to achieve this aim the DNO proyected 3 scenarios of electric vehicle adoption for the medium time horizont.
* Scenario 1: Pessimist adoption (0.08 Market participation: 2000 EVs proyected).
* Scenario 2: Normal adoption (0.1 Market participation: 2500 EVs proyected).
* Scenario 3: Optimist adoption (0.15 Market participation: 3750 EVs proyected).

Based in academic advances, the DNO projected a first option, which require investments in distribution network generation even for its pessimist scenario (As seen in [[1]](https://ingenius.ups.edu.ec/index.php/ingenius/article/view/7272). This option only consider the uncontrolled charging effect and don't seem to be a natural alternative for them as power system policiers, because in the worst case they should manage an investment of $ 1,877,658.44, only related to lack of energy management measures.

Considering their alternatives, they should manage the decentralized and centralized electric vehicle charging management options. The decentralized electric vehicle charging management (DEVCM) alternative is represented by multiple electric vehicle aggregators (EVA), As said in [[2](https://www.researchgate.net/publication/364097345_Electric_Vehicles_Aggregator_Participation_in_Energy_Markets_Considering_Uncertainty_Travel_Patterns)] the EVA is a critical market agent for the decentralized smart charging and discharging management system. The application of this alterntative aliviates the not served energy required for the first 2 scenarios, as seen in [Decentralized Charging Modelling Initial](.//DB/DCM%20Ini/) and describe in this section [documentation](.//DB/DCM%20Ini/DCM%20Ini%20Readme.md) The power flow executed in maximum output from the opptimistic scenario is reported the next [figure](.//DB/DCM%20Ini/Sc3/IEEE%2014validacion/IEEE%2014validacionPSF4.jpg)

![Figure 1: Scenario 3 Maximum MCS output](.//DB/DCM%20Ini/Sc3/IEEE%2014validacion/IEEE%2014validacionPSF4.jpg)

The DNO notice that, even with this management measure (policy required), they could face even more than this electric management, improving the coordination between the EVAs (1 per each load bus bar in power system) and them as operators. Implementing a constrained energy trading proccess for EVAs. As reported in [Centralized Constraint](.//Centralized%20Constraint) Applicating this constraints from DNO as Centralized Electric Vehicle Charging Management (CEVCM) to DEVCM the power system complete the optimal power flow in normal state, as seen in the next [figure](.//DB/Decentralized%20PF%20Constrained/IEEE%2014validacion/IEEE%2014validacionPSF4.jpg). This improve is verified with the absence of not served energy in the power flow.

![Figure 2: Scenario 3 Maximum MCS output constrained](.//DB/Decentralized%20PF%20Constrained/IEEE%2014validacion/IEEE%2014validacionPSF4.jpg). 

[[1] C. W. Villanueva-Machado, J. E. Luyo, A. Rios-Villacorta,  Monte carlo simulation of uncontrolled electric vehicle charging  impact on distributed generation, *Ingenius. Revista de Ciencia y Tecnología* 30 (10) (2023) 120–134.](https://ingenius.ups.edu.ec/index.php/ingenius/article/view/7272).

[[2] Villanueva,C.; Luyo,J.; Delgado, Alexi; Carbajal-Mancilla,Chiara (2019), Electric vehicles aggregator participation in energy markets considering uncertainty travel patterns, *International Journal of Innovative Technology and Exploring Engineering*,   8 (12) 4994-4998](https://www.researchgate.net/publication/364097345_Electric_Vehicles_Aggregator_Participation_in_Energy_Markets_Considering_Uncertainty_Travel_Patterns)]
