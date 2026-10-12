# Report Catalog

## **[LPS001 - Tropical Storm Arthur (June 2026)](./2026/LPS001%20-%20Tropical%20Storm%20Arthur/Tropical%20Storm%20Arthur%20-%206-20-26.pdf)**

### Architect's Post-Mortem

> *"Overall, we were able to capture some high value telemetry from this storm system. Ultimately the infrastructure began degrading just before impact; however, most of the stations continued to capture storm data. I am looking forward to what the next storm system brings and more importantly, the Regulus Project is in a much better position to capture the next event."*  
> — **Charles Harding**

### Executive Summary
Between **June 15, 2026, and June 20, 2026**, Tropical Storm Arthur impacted the facilities envelope and ambient environment. The Regulus Projects contributing stations captured detailed environmental telemetry—including barometric pressure variance, total rainfall accumulation, wind vector behavior, and interior envelope impacts—providing valuable insights into localized atmospheric degradation and structural resilience.

| Metric | Recorded Value | Notes |
| :--- | :--- | :--- |
| **Min Barometric Pressure** | `997.65 hPa` | Atmospheric degradation peaked on June 17 |
| **Max Barometric Pressure** | `1004.25 hPa` | Observed elevation during rainfall events |
| **Max Wind Speed** | `43.22 mph` | Sustained gust recorded June 17 |
| **Total Rainfall** | `4.79 in` | Aggregated across active sensors |

---

## **[LPS002 - Low Pressure System 002](./2026/LPS002%20-%20Generic%20Low%20Pressure%20System%202/LPS002%20-%20Storm%20Report.pdf)**

**Audit Window:** October 2, 2026 – October 7, 2026  
**Primary Impact:** Facilities Envelope Hydrology & Moisture Intrusion  
**Architect's Note:** This was the first report since the stations were calibrated. Therefore, the pressure hike to 1013 was the adjustment in reported values from raw values (approx. 998) to the pressure at sea level in comparison to LPS001 is expected. 

### Key Observations & Telemetry
* **Peak Environmental Metrics:** Recorded a minimum pressure of **1013.21 mb**, maximum sustained wind of **24.18 mph**, and **3.78 in (96.02 mm)** total rainfall.
* **Pre-System Rainfall Dynamics:** Moisture and precipitation preceded the core barometric pressure drop, impacting the property during a primary high-pressure driver.
* **Basement Intrusion Event:** Water seepage along the west wall overwhelmed extraction capacity, driving relative humidity from a **30% baseline to peak near 50%** before manual puddle mitigation stabilized evaporation rates.

### Hardware & Infrastructure Progress
* **Second-Generation (G2) Mesh Deployment:** Successfully tested G2 station design with zero lost packets or clock drift across a 5-day continuous overcast window.
* **System Improvements over LPS001:** Resolved power depletion (Icarus station) and Wi-Fi range limitations observed during Tropical Storm Arthur by upgrading radio links and power profiles.


### Executive Summary
Between **October 2, 2026 – October 7, 2026**, this low pressure system impacted the facilities envelope and ambient environment. The Regulus Projects contributing stations captured detailed environmental telemetry—including barometric pressure variance, total rainfall accumulation, wind vector behavior, and interior envelope impacts — providing valuable insights into localized atmospheric degradation and exposing some weaknesses in the envelope of the structure.

| Metric | Recorded Value | Notes |
| :--- | :--- | :--- |
| **Min Barometric Pressure** | `1013.21 mb` | Calibrated value to sea level. |
| **Max Barometric Pressure** | `1019.87 mb` | Calibrated value to sea level. |
| **Max Wind Speed** | `24.18 mph` | Very minor wind. |
| **Total Rainfall** | `3.78 in (96.02 mm)` | Aggregated across active sensor |

---

## **[LPS003 - Hurricane Isaias](./2026/LPS003%20-%20Hurricane%20Isaias.pdf)**

**Audit Window:** October 9, 2026 – October 11, 2026  
**Primary Impact:** Facilities Envelope Hydrology, Wind Exposure & Infrastructure Resilience  
**Architect's Note:** *"Several features of the envelope were tested and compromised. We will be taking active measures in mitigating the risks exposed by this event."* — **Charles Harding**

### Key Observations & Telemetry
* **Peak Environmental Metrics:** Recorded a minimum pressure of **1003.0 mb**, maximum pressure of **1016.98 mb**, maximum wind speed of **51.5 mph**, and total rainfall of **2.77 in (70.35 mm)**.
* **Envelope & Moisture Intrusion:** Significant water intrusion occurred via the west and north basement walls due to groundwater saturation/hydrostatic pressure. Additional water entered through the crawlspace vents (windblown rain) and the fireplace.
* **Relative Humidity Anomalies:** Basement relative humidity (Kelvin station) spiked from a 30% baseline to nearly 50% during peak rainfall.
* **Infrastructure Resilience:** Property lost internet access on 10/09/2026. Backed up by UPS and G2 stations, observation continuousness remained unaffected. First-generation stations experienced clock drift due to lost internet sync, whereas second-generation stations maintained high resolution without drift.

### Executive Summary
Between **October 9, 2026, and October 11, 2026**, Low Pressure System 003 (Hurricane Isaias) impacted the facilities envelope primarily with excess winds and rain. Contributing stations captured critical telemetry detailing barometric pressure drops, rainfall intensity, wind vector dynamics, and envelope water intrusion under severe weather conditions.

| Metric | Recorded Value | Notes |
| :--- | :--- | :--- |
| **Min Barometric Pressure** | `1003.0 mb` | Pressure drop observed during system impact |
| **Max Barometric Pressure** | `1016.98 mb` | Pre-storm/post-storm recovery baseline |
| **Max Wind Speed** | `51.5 mph` | Recorded at rooftop station Polaris |
| **Total Rainfall** | `2.77 in (70.35 mm)` | Aggregated rainfall across event window |

---

## Disclaimer

*These reports and the associated datasets were curated based on data observed in 2026. The information contained herein is intended solely for scientific research and experimental purposes and should not be construed as an authoritative source of meteorological record.*

**© 2026 Charles Harding / The Regulus Project**