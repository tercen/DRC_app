# DRC_app

##### Description

`DRC_app` is an application for the analysis of dose response curves using a 4 parameter dose response model. This app implements the DRC fit operator.

##### Details

* The PamApp should be used with linear Signals (i.e. no log transformation of the signals)
* The concentration (dose) must be provided in logM (i.e. 1 uM = -6, 10 uM = -5 etc.). Use the Excel sheet below to calculate LogM values for your concentrations (uM to LogM)
  - [LogM calculations.xlsx](https://tercen.com/pamgene/f/4629c134b09c53160ea461e75f8da7dc)
* Note that both the fitting procedure and rendering of high res output can take some processing time.

The input data is the [DRC dataset](https://tercen.com/r/4629c134b09c53160ea461e75f7ff2b8)

This workflow has 2 operators:

* [mean_operator](https://github.com/tercen/mean_operator)
* [DRC4 fit operator](https://github.com/tercen/DRC_fit_operator)

This workflow has 2 views:

* Modulation Profiles
* Modulation Heatmap

##### See Also

[DRC_app](https://github.com/tercen/DRC_app)
