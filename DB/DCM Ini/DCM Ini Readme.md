# Decentralized Charging Management Flow Initial

This directory contained the first  decentralized  charging management implementation. This fila has 2 different kinds of subdirectories:

* Data bases of EV characterization from Monte Carlo Simulation. (PCarBusResults...)
* Results from power flow optimization per scenario (Sc...)

This information allows centralized managers to commit the energy traded in energy market by Electric Vehicle Aggregators. The scenarios 1 and 2 didn't present not serve energy participation in power flow performance. Even the maximum output of the second escenario (which has 2500 EV characterized) is still in normal operation condition see the figure of [Scenario 2: Max MCS output Power Flow](https://github.com/cwvillanuevam/Paper-Operative-Analysis-of-EVCCM-C-D-coordination-/blob/main/DB/DCM%20Ini/Sc2/IEEE%2014validacion/IEEE%2014validacionPSF4.jpg).

![Scenario 2: Max MCS output Power Flow](https://github.com/cwvillanuevam/Paper-Operative-Analysis-of-EVCCM-C-D-coordination-/blob/main/DB/DCM%20Ini/Sc2/IEEE%2014validacion/IEEE%2014validacionPSF4.jpg?raw=true)

But even for the minimum Monte Carlo Simulation output, the power flow operation require not served energy to be executed. This exceution is shown in the [Scenario 3: Min MCS output Power Flow](.//Sce3/IEEE%2014validacion/IEEE%2014validacionPSF3.jpg).

![Scenario 3: Min MCS output Power Flow](.//Sc3/IEEE%2014validacion/IEEE%2014validacionPSF3.jpg).
