## Jose Ernesto Sandoval Hernandez

I build optimization-based controllers for energy systems, and the measurement systems that
let them run outside a model. MSc Mechanical Engineering, Purdue University (Ray W. Herrick
Laboratories). Interests: model predictive control, system identification, building controls
and demand flexibility.

[LinkedIn](https://www.linkedin.com/in/jsahe) · [Google Scholar](https://scholar.google.com/citations?user=cL2oeXIAAAAJ&hl=en) · ernestosandovalhdez@gmail.com

---

### Code

| Project | What it shows | Result |
|---|---|---|
| [**Wind, solar and battery sizing for an industrial load**](https://github.com/jose-sandoval/wind-solar-battery-sizing) · MATLAB | Component-level PV, wind and battery models, with a year-long 5-minute simulation for every configuration | 14 turbines, 9,500 PV modules, 5.5 MWh: **$81.2M saved over 10 years, 3.98-yr payback** |
| [**Low-GWP refrigerants for a cold-climate heat pump**](https://github.com/jose-sandoval/low-gwp-heat-pump-refrigerants) · EES | ASHRAE load calculation, variable-speed compressor model, coil sizing, full-cycle performance | **HSPF 12.4 / SEER 15**; R-1234ze(E) has the highest heating COP at low ambient temperature |
| [**Wind supply sizing for a blue-ammonia plant**](https://github.com/jose-sandoval/ammonia-plant-wind-sizing) · MATLAB | Wind-farm sizing against grid supply, plus plant techno-economics | **80 MW optimum** cuts electricity cost 28%; LCOA **$256/t** |

### Research and other work (described, no code)

**Multi-zone predictive control for residential HVAC**, MSc thesis, 2024–2026, advised by Prof. Kevin J. Kircher.
I designed, commissioned and ran a two-layer supervisory MPC (24-hour horizon, CVXPY) for a
variable-speed heat pump in an occupied 2,240 ft² house through a full heating season. I
identified a 5R2C thermal model from 50,000+ sensor readings (0.07–0.10 °C RMSE on held-out
data) and built the instrumentation for $1,708. Results: **11.5% less weather-normalized
heating energy** (95% CI 1.5–21.2%) against the manufacturer baseline, and **71% lower
comfort-tracking error**. [Thesis, DOI 10.25394/PGS.32751594](https://doi.org/10.25394/PGS.32751594).
Journal article in preparation.

**The Future Below: Renewable-Powered Underground Data Hubs**, Springer, 2026, pp. 243–250.
A five-author feasibility study siting an underground data center against wind, solar and
inactive-mine data; my part was the techno-economics and renewable integration. Underground
chilled-water cooling cut cooling load 3.33× (23.6 → 7.1 kW). Eleven Vestas V110 turbines at
a 46.98% capacity factor cover a 10 MW center's 87.6 GWh/yr.
[DOI 10.1007/978-3-032-07974-9_21](https://doi.org/10.1007/978-3-032-07974-9_21).

**Self-sustained Rankine-cycle pump prototype**, senior capstone with Constellation Energy, 2024. Lead design engineer on a five-person team.
I designed, built and tested a prototype that uses controlled pressure transients to recover
thermal energy, over 50+ hours of testing: about 5% thermal energy recovery, with all
functional and safety targets met. The analysis and results contributed to a patent
application filed by the sponsor, on which the sponsoring engineer is the named inventor.

**GaAs concentrator solar cells**, research internship, The University of Tokyo, 2023.
Temperature- and irradiance-dependent I-V characterization of 50+ cells. Efficiency fell
0.4% per 10 °C, showing that cell temperature, not concentration, drove the losses.

### Tools

Python (CVXPY) · MATLAB · EES · OpenLCA · Zigbee sensor networks · time-series databases
