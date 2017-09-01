# demos

Contains demonstrations for a subset of Smart-DS tools.

## Contents

[demo_sssmatch_applied_to_rts_gmlc.ipynb](demo_sssmatch_applied_to_rts_gmlc.ipynb) - Demonstrates the [sssmatch](https://github.com/Smart-DS/sssmatch) CLI for browsing [NREL Standard Scenarios](https://www.nrel.gov/analysis/data_tech_baseline.html) data and using a selection from that data to create a new generation mix for an existing transmission system model. The demonstration is done using the [RTS-GMLC](https://github.com/GridMod/RTS-GMLC) model.

[demo_R2PD_applied_to_rts_gmlc.ipynb](demo_R2PD_applied_to_rts_gmlc.ipynb) - Demonstrates the [R2PD](https://github.com/Smart-DS/R2PD) CLI and backend tools for downloading and formatting wind and solar power and forecast data. This demonstration is also done using the [RTS-GMLC](https://github.com/GridMod/RTS-GMLC) model. In addition to pulling wind and solar data for the RTS-GMLC model as-is, it demonstrates how to use the outputs of sssmatch to obtain wind and solar data that corrsponds to a new sssmatch generation mix.
