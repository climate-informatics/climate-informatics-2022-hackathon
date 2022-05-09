# climate-informatics-2022-hackathon
This is the hackathon starting kit repository for the Climate Informatics 2022 Conference.

Conference webstie: [https://ncics.org/news/events/ci2022](https://ncics.org/news/events/ci2022)

## Drought prediction challenge

Drought can lead to substantial environmental, societal, and economic impacts and can become more severe 
and prolonged regionally in a changing climate. Being able to accurately predict such events helps to 
mitigate and prepare. This year’s Climate Informatics Hackathon aims to forecast droughts in South Sudan
and Ethiopia. Using the Standardized Precipitation Index (SPI) as a target measure, the challenge is to 
leverage the spatio-temporal modeling power of machine learning to anticipate those dangerous hazards far
in advance to support mitigation efforts.

## Access to JupyterHub environment

Registered conference attendees who attend hackathon can access the JupyterHub environment built on Amazon
Web Services via attendees' GitHub ID.

Access JupyterHub [here](https://oasis.ncics.org).

To access GPU resources for model development, start a **g4dn.xlarge** server when starting up.

## Data

The hackathon uses data from Community Earth System Model (CESM) for the model training and development.

> The National Center for Atmospheric Research (NCAR) Community Earth System Model Large Ensemble (CESM LENS) 
> dataset includes a 40-member ensemble of climate simulations for the period 1920-2100. All model runs were 
> subject to the same radiative forcing scenario: historical up to 2005, and RCP8.5 thereafter. 
> (RCP8.5 - Representative Concentration Pathway 8.5 - refers to the worst-case scenario considered in the 
> Fifth Assessment Report of the Intergovernmental Panel on Climate Change - IPCC). Each of the 40 runs begins
>  from a slightly different initial atmospheric state (created by randomly perturbing temperatures at the 
>  level of round-off error). The data comprise both surface (2D) and volumetric (3D) variables in the atmosphere,
>   ocean, land, and ice domains.
>   
> The total LENS data volume is ~500 TB, and is traditionally accessible through the NCAR Climate Data Gateway (CDG)
>  for download or via web services. A subset (currently ~70 TB compressed) including the most useful variables is 
>  now freely available on AWS S3 thanks to the AWS Public Dataset Program.
> 
> CESM LENS data on AWS: https://registry.opendata.aws/ncar-cesm-lens/
