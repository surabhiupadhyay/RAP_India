# RAP_India

#### Contributors
**Team Lead**  Jennifer Marlon, Ph.D. **Team Members** Deepika Pingali, Surabhi Upadhyay, Emine Senkardesler, Pratyush Tripathy, Okikiola Michael Alegbeleye

Developed for the I-GUIDE Summer School on "Spatial AI for Extreme Events and Disaster Resilience" (August 4-8, 2025)

####  📊 Variables

**🎯 Dependent Variable**  
- *Survey-Based Drought Vulnerability Outcome*  
  (e.g., perceived flood risk, perceived drought risk)

**🔍 Covariates / Independent Variables**

**🧍 Individual-Level:**  Age, Gender, Education, Caste  

**🌐 District-Level**  
- News Media Webscraping for Floods
- VIIRS Nighttime Radiance 
- Alpha Earth Embeddings
- ERA5 Climate Data:  
  - Monthly Precipitation  
  - Monthly Temperature
  
#### 🤖 Modeling Scenarios
  
**Model 1:** Baseline model using only *individual-level demographic variables*  
(*Age, Gender, Education, Caste*)

**Model 2:** Includes *Model 1 + district-level physical features*  
(*VIIRS Radiance, ERA5 Precipitation & Temperature, News Mentions*)

**Model 3:** Model 1 + *Alpha Earth Embeddings* 

**Model 4:** Advanced model integrating *Alpha Earth Embeddings* with all other covariates
