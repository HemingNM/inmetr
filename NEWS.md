# inmetr 0.0.2.9000

- [x] remove dependence on plyr
- [x] `import_bdmep()` supports a vector of stations IDs allowing to data import from multiple meteorological stations.
- [x] change the name of the first argument of `import_bdmep()` from `id` to `ids` to emphasize the new feature.
- [ ] get stations metadata from [here]("http://www.inmet.gov.br/webcdp/climatologia/normais/imagens/normais/planilhas/Relac_Est_Meteo_NC.xls")
- [ ] add function to provide daily data.
- [ ] add function to write csv files of station data.
- [ ] fix note about zenodo


# inmetr 0.0.2

- fixed issue (#1, @sillasgonzaga)

- `import_bmep()` has a new argument `verbose` to print if the status of connection is ok.  