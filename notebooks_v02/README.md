# notebooks_v02

This folder is the cleaned, narrative version of the exploratory notebook workflow.

## Recommended order

1. `00_environment_check.ipynb`
2. `01_study_area.ipynb`
3. `02_urban_form_inputs.ipynb`
4. `03_building_height_enrichment.ipynb`
5. `04_prepare_solweig_inputs.ipynb`
6. `05_run_solweig.ipynb`
7. `06_thermal_network.ipynb`
8. `07_heat_conditioned_accessibility.ipynb`
9. `08_poc_visualisation.ipynb`
10. `09a_fetch_mobile_phone_data_R.ipynb` — R kernel
11. `09b_mobile_phone_data.ipynb`
12. `10_hot_reference_day_comparison.ipynb`
13. `11_urban_form_thermal_accessibility.ipynb`
14. `12_heat_accessibility_mobility_link.ipynb`
15. `13_poc_story_and_visual_summary.ipynb`

## What changed from the exploratory notebooks

- duplicated/debugging cells were removed;
- the two building-height notebooks were consolidated;
- R data acquisition is separated from Python analysis;
- hard-coded local Mac paths were removed from Python notebooks;
- the exact stop-snapping/graph-cleaning sequence from the validated accessibility analysis was preserved;
- interpretation cells distinguish proof-of-concept findings from citywide claims;
- notebook 13 is a reporting/synthesis notebook rather than a recomputation notebook.

## Important PoC caveats

- the SOLWEIG domain covers only a small part of Sevilla;
- the meteorology uses a PVGIS EPW typical meteorological year;
- the downstream thermal network currently uses cell-wise daily maximum UTCI;
- λ is a sensitivity parameter, not a behaviorally calibrated coefficient;
- mobile-phone analysis covers a much larger spatial extent than the thermal PoC.
