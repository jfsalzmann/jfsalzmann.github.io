---
title: "Recent Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /portfolio
---

For an overview of my earlier and non-technical projects, please visit my <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i>LinkedIn</a> profile.


## Academic

- **Modelling Week-To-Week Voting Intention Change** (2024 – 2025)  
  Master's thesis project, M.Sc. Data Science for Public Policy
   <a href="/docs"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a>

  <details class="dsmall" open markdown="1"><summary>Details</summary>
  *Context* Inter-election vote switching is typically based on recall items and/or election results. The thesis aimed to develop a method for estimating transition matrices of short-term party preference change in a higher temporal resolution using high-frequency panel data.

  *Data* SOSEC panel (n=3500, bi-weekly, USA/Germany, 2023-2025), FZI

  *Methods* Hierarchical Bayesian imputation model in the latent k-dimensional simplex space

  *Results* Bi-weekly voting intention transition matrices, run-up to the 2025 German federal election
  </details>

- **Building a Shiny Web App for Ternary Plots of Generalised Dirichlet Distributions** (2025)  
  Side project to the Master's thesis, M.Sc. Data Science for Public Policy
   <a href="https://jfsalzmann-dirichlet-generalisations.share.connect.posit.cloud/" target="_blank"><i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  <a href="https://github.com/jfsalzmann/dirichlet-generalisations" target="_blank"><i class="fab fa-fw fa-github" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* There is a lack of interactive modelling helper tools when working with (generalised, that is, mixtures of) Dirichlet distributions. The web app aims to fill this gap.

  *Methods* Simulation of random draws, visualisations in a R/Shiny app hosted on Posit Connect
  </details>

- **Building an LDA Classifier Model for Full Bayesian Text Classification with STAN** (2024)  
  Seminar project, M.Sc. Data Science for Public Policy
   <a href="/docs"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* Many NLP classifiers are implemented in a frequentist/ML fashion. The project aimed to implement a full Bayesian classifier model using Latent Dirichlet Allocation (LDA).

  *Data* Synthetic text data based on Telegram messages from a Berlin public transport group
  
  *Methods* Inference of LDA parameters with STAN, posterior prediction, model evaluation
  </details>

- **Building a Joint Latent Model of Media Coverage Indicators and Issue Salience** (2024)  
  Seminar project, M.Sc. Data Science for Public Policy
   <a href="/docs"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* As the climate movement became popular in 2019, the German's perception of most important problem (MIP) shifted towards climate change. It was the aim of this project to combine different data sources on media coverage and issue salience polling data in a joint model.

  *Data* News coverage data, SPIEGEL & GDELT; MIP item, Forschungsgruppe Wahlen (2019)

  *Methods* Full Bayesian joint latent regression model with STAN
  
  *Results* Quantification of a news coverage effect of Fridays For Future protests on climate change issue salience
  </details>

- **Analysing the Sudden Surge in Climate Awareness in Germany 2019** (2022 – 2023)  
  Master's thesis project, M.P.P. Master of Public Policy
   <a href="/docs"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* As the climate movement became popular in 2019, the German's perception of most important problem (MIP) shifted towards climate change and the Green party's popularity surged. The thesis aimed to analyse the multi-faceted effects Fridays For Future's protests had.

  *Data* MIP and voting intention items, Forsa & Forschungsgruppe Wahlen (2019); protest records, Fridays For Future Germany

  *Methods* Theory development, regression analysis
  
  *Results* Quantification of a news coverage effect of Fridays For Future protests on climate change issue salience
  </details>

- **Assessing the PRC's Climate Responsibility Using GHG Emissions Data** (2022)  
  Seminar group project, M.P.P. Master of Public Policy
   <a href="/docs"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a>
  <a href="https://github.com/jfsalzmann/dataghg" target="_blank"><i class="fab fa-fw fa-github" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* It is a matter of perspective (historic vs. current emissions) what the PRC's fair share of global climate mitigation efforts should be. The project aimed to shed light on the reduction pathways the PRC could take to reach climate neutrality.

  *Data* GHG emissions data (1920-2020, EDGAR); population and economic data (1990-2020, World Bank)

  *Methods* Descriptive analysis, visualisations, transition path forecasting models

  *Results* Quantification of the PRC's historical, current, and future emissions contributions
  </details>

- **Forecasting Germany's Demand for Natural Gas in the Energy Crisis** (2022)  
  Seminar group project, M.P.P. Master of Public Policy
   <a href="/docs"><i class="fas fa-fw fa-file-pdf" aria-hidden="true"></i></a>
  <a href="https://github.com/jfsalzmann/gasprices" target="_blank"><i class="fab fa-fw fa-github" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* In the wake of the energy crisis following Russia's invasion of Ukraine, Germany's natural gas prices surged. The project aimed to develop forecast models for real-time demand prediction.

  *Data* Various data (2017-2022): historic gas prices and demand (THE), weather data (Meteostat), CO2 prices (investing.com), electricity prices (investing.com), DAX stock market index (Yahoo finance), German GDP quarterly (World Bank)

  *Methods* Machine learning time series models
  
  *Results* Real-time week-ahead forecast of national natural gas demand
  </details>



## Professional

- **Developing a Post-Stratification and Imputation Framework for the SOSEC Panel** (2025)  
  Methodological project for FZI Forschungszentrum Informatik, Berlin
   <a href="https://www.socialsentiment.org/forschungsdesign/" target="_blank"><i class="fas fa-fw fa-building-columns" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* With high panel mortality, unbalanceness and inconsistencies in the sampling process, the SOSEC panel requires robust post-stratification and imputation methods to reduce bias and increase representativity.

  *Data* Census data (Germany: DeStatis, USA: US Census Bureau); SOSEC panel (n=3500, bi-weekly, USA/Germany, 2023-2025), FZI

  *Methods* Post-stratification weights (joint distributions of demographic variables); multiple imputation
  </details>

- **Analysing the Spatial Distribution of Balcony Solar Panels in Berlin** (2024)  
  Data analysis project for PLAN B 2030 e.V., Berlin
   <a href="https://planb2030.org/balkonkraftwerke" target="_blank"><i class="fas fa-fw fa-building-columns" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* State-level funding programmes have boosted the installation of small-scale solar panels in Berlin. The project aimed to analyse the spatial distribution of these panels and to draw conclusions on the success of the programme.

  *Data* Marktstammdatenregister (2021-2023, BNetzA)

  *Methods* Geospatial data analysis, visualisations
  
  *Results* There is a surprising concentration of installations in wealthier single family house areas, with indications for the funding programme.
  </details>

- **Building a Web App for a Unified Postal Vote Registration for German Elections** (2023)  
  Professional Year project for Mehr Demokratie e.V.
   <a href="https://wahlbrief.de" target="_blank"><i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  <a href="https://github.com/Wahlbrief/wahlbrief-website" target="_blank"><i class="fab fa-fw fa-github" aria-hidden="true"></i></a>
  <a href="https://www.mehr-demokratie.de/mehr-bewegen/kampagnen/ohne-euch-wirds-schraeg" target="_blank"><i class="fas fa-fw fa-building-columns" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* Online postal vote registration, as many other citizen services in Germany, is in the responsibility of the municipalities. The project aimed to build a unified web app to simplify the process.

  *Data* Federal and state-level statistical offices, ZIP code data (Deutsche Post)

  *Methods* Matching of addresses, zip codes, administrative boundaries; web development: landing page, template-based application generator, email reminder service, information portal
  </details>



## Personal

- **Building a Risk Model of Berlin's Public Transport Ticket Inspections** (2024)  
  Not-for-profit app development for Freifahren Berlin
   <a href="https://app.freifahren.org" target="_blank"><i class="fas fa-fw fa-link" aria-hidden="true"></i></a>
  <a href="https://github.com/FreiFahren/FreiFahren" target="_blank"><i class="fab fa-fw fa-github" aria-hidden="true"></i></a>

  <details class="dsmall" markdown="1"><summary>Details</summary>
  *Context* A telegram group with more than 25k members reports on sightings of ticket inspection staff in Berlin. The project aimed to develop a risk model of getting checked in Berlin's public transport.

  *Data* Telegram group data, Overpass Turbo (OSM)

  *Methods* Geospatial data analysis, risk modelling
  </details>


------------

Thanks for your interest!

Did you know I am currently <a href="/">looking</a> for a PhD position? Also see my <a href="/cv">Academic CV</a>.  

Please feel free to <a href="mailto:{{ site.author.email }}"><i class="fas fa-fw fa-envelope" aria-hidden="true"></i>reach out</a> to me or connect through <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank"><i class="fab fa-fw fa-linkedin" aria-hidden="true"></i>LinkedIn</a>.
