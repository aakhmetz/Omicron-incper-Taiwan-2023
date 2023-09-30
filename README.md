# Incubation period of Omicron variant based on Taiwan data, December 2021 - January 2022

Supporting material for Akhmetzhanov AR, Cheng HY, Dushoff J. Incubation-period estimates of Omicron (BA. 1) variant from Taiwan, December 2021-January 2022, and its comparison to other SARS-CoV-2 variants: a statistical modeling, systematic search and meta-analysis. *medRxiv*. 2023:2023-07. ([doi:10.1101/2023.07.20.23292983](https://doi.org/10.1101/2023.07.20.23292983))

## I. Abstract
The COVID-19 pandemic has seen several variants of concern, including the Omicron variant which emerged in October 2021. To effectively formulate effective public health strategies and understand disease spread, accurate estimates of the incubation periods of these variants are important. Existing estimates often conflict due to biases caused by dynamic epidemic growth and selective inclusion of cases. Using data from Taiwan, where disease incidence remained low and contact tracing was comprehensive during the first months of the Omicron outbreak, this study aims to accurately estimate the incubation period of the Omicron (BA.1) variant incubation period. For the analysis of Omicron BA.1 cases reported between December 2021 and January 2022, we reviewed the first 100 contact-tracing records. Of these, 69 had information that was helpful. Data on exposure and symptom onset dates were fitted into a Bayesian mixture model using gamma, Weibull, and lognormal distributions as candidates for estimating the incubation-period distribution. The mean incubation period was estimated at 3.5 days (95% credible interval: 3.1–4.0 days), with no clear differences based on vaccination status or age stratification. This estimate aligns closely with the pooled mean of 3.4 days (3.0–3.8 days) obtained from a meta-analysis of other published studies on Omicron subvariants (BA.1/2, BA.4/5). Omicron’s relatively shorter incubation period, compared to previous SARS-CoV-2 variants, implies its potential for rapid spread but also opens the possibility of shorter quarantine periods. A continuous update of incubation period estimates, based on available data, is necessary in order to develop guidelines that can reduce the socioeconomic costs associated with COVID-19. 

## II. Code scripts
* [A. Main analysis.ipynb](https://nbviewer.org/github/aakhmetz/Omicron-incper-Taiwan-2023/blob/main/scripts/A.%20Main%20analysis.ipynb)
* [B. Assembling the figures.ipynb](https://nbviewer.org/github/aakhmetz/Omicron-incper-Taiwan-2023/blob/main/scripts/B.%20Assembling%20the%20figures.ipynb)

## III. Output

<img width="600" src="https://github.com/aakhmetz/Omicron-incper-Taiwan-2023/assets/2173206/c2753677-3823-475b-8cc3-e6cf3129941e">

## Additional details
* The folder **data** contains all data used for our analysis.

---------
**Thank you for your interest to our work!** 

Few words of caution: We would like to note that our code is not supposed to work out of box, because the links used in the notebooks were user-specific as well as the password for our computation cluster was hidden. Our main intent was to show the relevance of the methods used in our paper.
