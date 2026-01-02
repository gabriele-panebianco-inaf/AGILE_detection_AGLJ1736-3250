# AGILE_detection_AGLJ1736-3250
AGILE Data, Maps and Notebooks on the detection of AGL J1736-3250.
The Notebooks require `agilepy` for execution (https://agilepy.readthedocs.io/en/latest/).

The data of Table 2 and Table 3 of the paper are stored in the `reference` directory and contain the time intervals of the 19 flares analysed, and the gamma-ray flux estimated with Maximum Likelihood Estimation (MLE) approach.

### Data Download
The repository contains the `notebooks/download.ipynb` notebook that can be used to downlaod the AGILE-GRID data.
The notebook creates a configuration file inside the `configuration` directory, it downloads the AGILE LOG and EVT data within the `data` directory.

### Data Analysis
The repository contains the `notebooks/analysis.ipynb` notebook that uses the downloaded data to create the AGILE maps, plots and perform Maximum Likelihood Estimation of the flux of AGL J1736-3250.
The maps and the results are stored within the `results` directory and include:
- `maps`: Counts Map, Exposure Map, Gas Map, Intensity Map.
- `mle`: results of the Maximum Likelihood estimation of the model.
- `sources_library`: regionn file with the model hypothesis.
- `lc`: Light Curves with 6h, 4h, 2h bins.
- `plots`: plots of the maps and light curves.


### Contacts
Further information on AGILE data analysis can be found at: https://agilepy.readthedocs.io/en/latest/
Contacts for the analysis:
- Andrea Bulgarelli: `andrea.bulgarelli@inaf.it`
- Gabriele Panebianco: `gabriele.panebianco@inaf.it`
