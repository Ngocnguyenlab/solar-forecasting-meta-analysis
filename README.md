# solar-forecasting-meta-analysis
A meta analysis of solar forecasting based on skill score
  <p align="center">
...
  </p>
</p>


<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary><h2 style="display: inline-block">Table of Contents</h2></summary>
  <ol>
    <li><a href="#Abstract">Abstract</a></li>
    <li><a href="#Methodology">Methodology</a></li></li>
    <li><a href="#Database">Database</a></li></li>
    <li><a href="#Findings">Findings</a></li></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#citing-us">Citing US</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
    <li><a href="#license">License</a></li>
  </ol>
</details>


<!-- ABSTRACT -->
## Abstract

Skill score validates a forecast by comparing its accuracy to a reference model. This relative measurement accounts for the variability of the forecast situation and is recommended as a standard metric of accuracy measurement for solar forecasting. We conduct the first meta-analysis of deterministic solar forecasting based on 4,687 skill score observations extracted from literature, using multivariate adaptive regression spline modelling, partial dependence plots, and linear regression. The marginal impacts on skill score of ten factors were quantified, including climate zone, forecast horizon, inputs, forecast models, resolution of forecasts, train and test data length, type of forecasts (i.e., solar resource or PV output forecasting), and publication date. 

The analysis shows the non-linearity and complex interaction between variables in the database. Forecast horizon has a central impact and dominates other factors’ impacts. Skill score increases with horizon for intra-day and intra-hour, but decreases with horizon for day-ahead forecasts. Climate zone variables have statistically significant correlation with skill score. For intra-hour, historical data and spatial temporal information of power system and its neighbours are highly helpful. For intra-day, sky and satellite images show the most important role, which can be combined with any other inputs. For day-ahead, NWP variables and locally measured meteorological data are very efficient. All forecast models were compared. Ensemble–hybrid models achieve the most accurate forecasts for all horizons. Hybrid models show superiority for intra-hour while image-based methods are the most efficient for intra-day forecasts. The choice of reference model matters. Skill score is highest when referenced against persistence model and lowest against the convex combination of smart persistence and climatology models. Resolution of 30 minutes seems the most difficult to forecast. Skill score decreases with the length of test data, especially for intra-hour and intra-day forecasts. More training data can enhance skill score. However, “over-fitting” is observed when there is too much training data (> 2000 days). There has been a substantial improvement in solar forecast accuracy, especially in recent years. More improvement is observed for intra-hour and intra-day than day-ahead forecasts.

!-- METHODOLOGY -->
### Methodology

An exhaustive search for literature was conducted. Then the literature was screened using well-defined criteria.

<!-- Teaser Image 1 -->
<br />
<p align="center">
    <img src="https://github.com/Ngocnguyenlab/solar-forecasting-meta-analysis/blob/main/images/Fig1.png" alt="Logo">
  
  </a>

  <p align="center">
 
 The database was analyzed using statistical methods such as multivariate adaptive regression spline modelling, partial dependence plots, and linear regression.


<!-- CONTACT -->
## Contact

Thi Ngoc Nguyen (nguyen@b-tu.de)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

This work has been realized in the framework of the public research project FOCCSI (Forecast Optimization by Correction and Combination methods for System Integration; 03ET4056) funded by the German Federal Ministry for Economic Affairs and Energy. 


## Citing us

To cite the database: Thi Ngoc Nguyen, & Felix Müsgens. (2022). A database of skill scores on solar forecasting [Data set]. Zenodo. https://doi.org/10.5281/zenodo.7274381

To cite our findings: Nguyen, T.N. and Müsgens, F., 2022. A Meta-Analysis of Solar Forecasting Based on Skill Score. arXiv preprint arXiv:2208.10536. https://doi.org/10.48550/arXiv.2208.10536


