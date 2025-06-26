# Public Report – Moira  
## Module 14: Hypothesis Validation Through a PoC

### Sprint 6: Project Planning and Initial TAPI  
This stage focused on formalizing the validation strategy through a structured Proof of Concept (PoC). A detailed execution plan was created, outlining activities, goals, and validation criteria for both technical and analytical feasibility. The TAPI (Thesis, Activities, Progress, Impact) framework was applied to maintain clarity and alignment throughout the next sprints.

### Sprint 7: Partner Engagement and Data Collection Setup  
A small business (Epipi) was selected as the pilot partner for the PoC. Conversations were held to understand its sales and marketing dynamics. Internal sales data was requested, while social media data, especially from Instagram and TikTok, was collected through custom scripts and manual efforts, considering API limitations.

### Sprint 8: Data Integration and Exploratory Analysis  
During this sprint, the collected data was cleaned, standardized, and integrated into a unified weekly dataset. Exploratory Data Analysis (EDA) was conducted to identify temporal patterns, correlations between engagement metrics and revenue, and the presence of potential predictive signals from social media content.

### Sprint 9: Model Execution and Comparative Forecasting  
Three forecasting models were developed and tested: a baseline using only internal sales data, a model using social media features directly, and a residual-based model leveraging external signals. These models were evaluated using MAE, RMSE, and MAPE, highlighting the limits and possible gains of social data integration in demand forecasting.

### Sprint 10: Results Analysis and Next Steps  
The results were analyzed in depth, revealing that while social media data helped reduce absolute errors, high proportional errors persisted. A new SME from a different sector, more mature in operations, was approached to host the next PoC cycle. In parallel, MVP planning began, outlining the architecture of a web application capable of ingesting spreadsheet data and integrating with Instagram’s API.
