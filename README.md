# World-Bank-Renew-Energy
Analysis of World Bank data on renewable energy consumption as a percentage of total energy consumption
In this notebook, we will be working with the Renewable Energy Consumption (% Of Total Final Energy Consumption) dataset from the World Bank. We will perform analysis on this data using visualizations with Plotly Express and JupyterDash (the Dash web application library adapted for use in Jupyter notebooks)

 **Attribution**

[The World Bank](https://datacatalog.worldbank.org)

**Dataset Name**: [Renewable Energy Consumption (% of Total Final Energy Consumption)](https://databank.worldbank.org/reports.aspx?source=2&series=EG.FEC.RNEW.ZS)

**Data Source**:
World Bank, Sustainable Energy for All (SE4ALL) database from the SE4ALL Global Tracking Framework led jointly by the World Bank, International Energy Agency, and the Energy Sector Management Assistance Program.

The dataset (zipped file) can be downloaded in csv or Excel format. I downloaded and saved the csv version to my Google drive, to which I have provided a link in the notebook.

[Zipped data file download link from Worldbank](https://datacatalog.worldbank.org/%23)

The World Bank has its own visualisation tool for this data, but I did not find it very satisfactory. Therefore we'll visualise it ourselves in this notebook.

[World Bank's visualisation tool](https://databank.worldbank.org/reports.aspx?source=2&series=EG.FEC.RNEW.ZS&country=)

The Workd Bank doesn't state explicitly what are counted as  renewable energy sources in this dataset, but from the descriptions for other World Bank datasets, they seem to include geothermal, solar, tides, wind, biomass, biofuels, and hydroelectric. 

It will be interesting to see which countries use more renewable energy, and what kind of trend can be discerned in different regions.
