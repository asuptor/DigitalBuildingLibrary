# DigitalBuildingLibrary
Repository for the research paper, "Supporting the EU mission '100-climate neutral cities': using urban building energy modeling for zero-emission building retrofit scenarios at district scale." <br />

Proceedings of Building Simulation 2023: 18th Conference of IBPSA, September 2023. <br />
Authors: Suppa, A.R. & Corrado, V. <br />
DOI: [https://doi.org/10.1007/s12273-025-1301-3](https://doi.org/10.26868/25222708.2023.1663)
<br />
<br />

The Building Material Library contains a digital implementation of the Italian residential building archetypes in TABULA (Corrado et al. 2011). The work uses assemblies detailed in Italian technical report UNI/TR 11552 (UNI 2014) to match TABULA values, adjusting thicknesses as required, and programming these into JSON files using Honeybee [(Ladybug Tools 2023)](https://www.ladybug.tools/)
<br />

In addition to the baseline condition as per TABULA, the research simulates energy conservation measures (ECMs), based on the nearly-zero energy building (nZEB) standards of the Italian Interim-Ministerial Decree 26
June 2015 for the case study climate zone (Italian zone ‘E’) (Italian Republic 2015).
<br />

The files are based on four main building types: apartment block (AB), multi-family house (MF), terraced house (TH), and single-family house (SF).
<br />

The JSON files can subsequently be used for energy simulations using URBANopt/EnergyPlus.
<br />

The following files are included:
1. Grasshopper script (.gh) containing programming of baseline (TABULA) construction set and resulting JSON files - AB & MF building types.
2. Grasshopper script (.gh) containing programming of baseline (TABULA) construction set and resulting JSON files - TH & SF building types.
3. Grasshopper script (.gh) containing programming of nZEB construction set and resulting JSON files - AB & MF building types.
4. Grasshopper script (.gh) containing programming of nZEB construction set and resulting JSON files - TH & SF building types.
5. Excel file (.xlsx) with all calculations for opaque cladding assemblies.
