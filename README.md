**Project overview**

This repository hosts an interactive, statewide geospatial dashboard examining the spatial distribution of smoking and vaping retail outlets surrounding public schools across North Dakota. The project quantifies environmental exposure by measuring proximity between school locations and nearby tobacco- and vape-related retailers, with a focus on policy-relevant distance thresholds commonly used in tobacco control and zoning regulations.

**Scientific motivation**

The retail tobacco environment is a well-established structural determinant of youth smoking and vaping initiation. While prior work has often relied on retailer density at coarse geographic scales, fewer studies have systematically evaluated school-centered proximity exposure at a statewide level, particularly in rural and mixed urban–rural settings such as North Dakota. This project addresses that gap by providing fine-grained, school-level spatial metrics that are directly interpretable for public health planning and policy.

**Data sources**

a. Public schools: Statewide public school listings for North Dakota, geocoded to latitude/longitude.

b. Smoking and vaping retailers: Retail locations identified using Google Places API queries, including smoke shops, tobacco retailers, and vape shops, validated through keyword-based classification.

c. Geographic boundaries: State and sub-state boundaries used for contextual visualization.

**Methods**

For each public school, great-circle distances are calculated to all identified smoking and vaping retail outlets. Primary exposure metrics include:

- Distance to the nearest smoking/vaping retailer (meters)

- Number of retailers within fixed buffer zones (e.g., 300 m, 500 m, 1,000 m)

- School-level exposure profiles stratified by school type (elementary, middle, high)

- All spatial computations are conducted using population-agnostic distance measures to ensure reproducibility and policy interpretability.

**Visualization**

Results are displayed using an interactive web-based map built with Leaflet/Folium. The dashboard allows users to:

- View statewide patterns of retailer proximity to schools

- Explore individual school-level exposure metrics

- Toggle distance buffers and layers for contextual comparison

The site is deployed as a static web application via GitHub Pages to enable public access and transparent dissemination.

**Interpretation**

This analysis characterizes environmental availability and spatial exposure, not individual behavior or causal effects. Findings are intended to support tobacco control policy discussions, zoning evaluations, and school-centered prevention planning.

- Intended audience

- Public health practitioners

- Tobacco control programs

- School administrators

- Policy makers

- Researchers in spatial and environmental epidemiology

**Methods-forward summary**

This project applies spatial epidemiology methods to quantify proximity-based exposure to smoking and vaping retailers around public schools across North Dakota. By anchoring exposure metrics at the school level and using standardized distance thresholds, the analysis generates policy-relevant indicators that are directly actionable for tobacco control and youth prevention strategies in both urban and rural contexts.

## **Access dashboard at: https://aidea1.github.io/nd-school-tobacco-proximity/**

**Citation:** Geospatial analysis of smoking and vaping retailer proximity to public schools across North Dakota.
