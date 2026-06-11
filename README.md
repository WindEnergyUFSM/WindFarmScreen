# WindFarmScreen

An automated, open-source Python framework designed to streamline and standardize wind energy site screening, terrain complexity assessment, and preliminary campaign planning. By integrating open-access geographic and meteorological data with industry-standard assessment logic, the pipeline accelerates due diligence and optimizing site monitoring campaigns.

---

## Key Capabilities

* **Automated Data Acquisition:** Seamless pipeline execution that fetches digital elevation models (DEM) from Terrarium and historical meteorological data from OpenMeteo based on coordinate inputs.
* **Terrain Complexity Mapping:** Automates sector-wise terrain slope and complexity evaluations strictly adhering to **IEC 61400-1**, **IEC 61400-12-1**, and **IEC 61400-50-2/3** standards.
* **LiDAR Uncertainty Estimation:** Calculates site-specific Type B uncertainty for Ground-Based LiDAR (GBL) campaigns per **IEC 61400-50-2**, outputting detailed sector-wise terrain-induced uncertainty metrics.
* **Wake Loss Screening:** Incorporates an integrated layout-scale aerodynamic preview across large wind turbine generator (WTG) fleets utilizing **PyWake**.
* **Cross-Validation Tools:** Includes built-in comparison utilities to map and correlate preliminary PyWake screening outputs against industry-standard commercial tools like WindPRO.

---

## Technical Limitations & Context

* **Screening-Level Accuracy:** The wake analysis component is built for preliminary screening and relative comparison of WTGs during campaign planning. 
* **Model Variances:** In highly complex terrain, users should expect relevant errors and variations between PyWake and WindPRO results. The framework is optimized for selecting and ranking turbine locations rather than absolute Annual Energy Production (AEP) legal signing.

---

## Installation

### Prerequisites
* Python 3.9+
* `pip` or `conda`

### Setup
Clone the repository and install the required dependencies.
