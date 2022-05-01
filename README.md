# Mapping Pharmacy Deserts in New York State

This project will look at access to pharmacies in New York State to explore which communities lack access to pharmacies. A study examining "pharmacy deserts" in Chicago found they were more likely to occur in minority communities. Is the same true in New York?

**Data Source/Collection**:

*Pharmacy data*

Approximately 86% of pharmacies participate in the state's [Medication Grant Program](https://nymgp.magellanrx.com), which provides funding for pay for the cost of reimbursing meidcations for mental illness. Data on participating pharmacies is published by the state, as well as a [count](http://www.op.nysed.gov/prof/pharm/pharmcounts.htm#stores) of pharmacies in each county, which was used to arrive at the 86% figure. (Count last updated March 2022; MGP data last updated April 2022 to reflect Q1 2022). Since this data represents such a larger proportion of the state's pharmacies, it can be used for this analysis.

[Download MGP participating pharmacy data](https://nymgp.magellanrx.com/files/NYMGPParticipatingPharmaciesbyCounty.xlsx)

*Demographic data*

Demographic data is sourced from the American Community Survey (ACS) five year 2015-2020 data using the [Census Python package](https://pygis.io/docs/d_access_census.html), with the list of available variables [here](https://api.census.gov/data/2019/acs/acs5/variables.html)
