# Dataset Information

## Department for Transport (DfT)

This folder contains raw traffic counts and count point information downloaded for Birmingham and Manchester.

### Datasets
- Birmingham: raw traffic counts and count point information.
- Manchester: raw traffic counts and count point information.

### Original sources
- Birmingham: https://roadtraffic.dft.gov.uk/local-authorities/E08000025
- Manchester: https://roadtraffic.dft.gov.uk/local-authorities/E08000003

Download date: 5 October 2026

Study period: 2020–2025.

The original DfT files include historical records from 2000–2025. The notebook filters these files to retain records for 2020–2025. Coverage is checked separately for each selected count point because some locations do not have observations in every study year.

### Purpose
Raw traffic counts will inform traffic demand and vehicle composition. Count point information will help locate suitable roads and match traffic observations to the selected road networks.

### Licence and attribution
Source: Department for Transport, Road Traffic Statistics.
Contains public sector information licensed under the Open Government Licence v3.0.
Licence: https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/

## OpenStreetMap road geometry

Candidate road-network extracts have been downloaded:

- `birmingham_candidate.osm`: Birmingham candidate area covering Bristol Road, Priory Road and Pershore Road.
- `manchester_candidate.osm`: Manchester candidate area covering Princess Road, Mauldeth Road West and Barlow Moor Road.

Source: https://www.openstreetmap.org/
Download date: 5 October 2026.
Attribution: © OpenStreetMap contributors.
Licence: Open Database Licence (ODbL).
Licence details: https://www.openstreetmap.org/copyright

These extracts will provide road geometry for constructing the SUMO networks. Final junction selection and network validation remain pending.

The extracts represent the map available at download, rather than verified historical road layouts for 2020–2025. Any relevant differences will be documented.

## Secondary data and simulation outputs

The research will use existing DfT traffic counts and OpenStreetMap road geometry as secondary inputs.

SUMO will generate synthetic vehicle trajectories from these inputs together with documented modelling assumptions. These trajectories will be derived simulation outputs, not observed traffic records.

No surveys, interviews or roadside traffic measurements will be conducted. Simulation outputs will be stored separately from the source datasets.
