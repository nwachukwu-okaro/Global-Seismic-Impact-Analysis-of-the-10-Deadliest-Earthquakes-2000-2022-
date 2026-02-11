# Global-Seismic-Impact-Analysis-of-the-10-Deadliest-Earthquakes-2000-2022-
# Project Overview
This geospatial project identifies and visualizes the ten most lethal earthquakes recorded between 2000 and 2022. By overlaying catastrophic events with global fault line data, the map illustrates the direct relationship between tectonic boundaries and human vulnerability.

Tool Used : QGIS

# 2. Key Objectives
Lethality Mapping: Isolate the top 10 events by total fatalities to highlight areas of highest humanitarian risk.

Tectonic Context: Overlay significant fault lines to visualize the seismic triggers behind these disasters.

Comparative Analysis: Use proportional symbology to contrast the scale of loss across different geographic regions (e.g., Haiti vs. Japan).

# 3. Step-by-Step Technical Approach
**Phase I:** Data Acquisition & Filtering
Sourcing: Leveraged the USGS/NOAA Significant Earthquake Database containing records of events with high socio-economic impact.

Temporal Filtering: Focused the analysis on a 22-year window (2000–2022) to capture modern seismic trends.

Selection: Ranked events by "Total Deaths" to identify the top 10 specific case studies.

**Phase II:** Geospatial Layering & Analysis
Fault Line Integration: Added a global "Faults" layer to provide a structural geological framework for the points of interest.

Spatial Join: Ensured earthquake epicenters were accurately projected relative to nearby urban centers (e.g., Port-au-Prince, Bam, Kathmandu).

**Phase III:** Symbology & Cartography
Proportional Symbols: Designed a graduated circle system to represent "Death Rate/Total Deaths," with three distinct tiers:

Large (500,000 range): Representing extreme events like Haiti.

Medium (50,000 range): Representing major disasters like the Sichuan or Pakistan earthquakes.

Small (5,000 range): Representing localized but significant lethal events.

Annotation & Labeling: Created custom callouts for each of the 10 sites, listing the location name and the specific death toll for clarity.

# 4. Critical Insights
The "Ring of Fire" & Tectonic Plates: High mortality rates in Indonesia, Japan, and China align perfectly with major subduction zones and fault systems.

Infrastructure Vulnerability: The map reveals that the highest death toll (Haiti: 316,000) occurred in a region with high urban density and vulnerable infrastructure, despite having a lower magnitude than some less lethal offshore events.

Regional Clusters: Indonesia appears multiple times (Sumatra, Java, Sulawesi), marking it as a critical zone for disaster preparedness research.
