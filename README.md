# Flood and Drought Risk Analysis Perception (RAP) Framework for India

## **Contributors**
- **Team Lead:** Jennifer Marlon, Ph.D.  
- **Team Members:** Deepika Pingali, Surabhi Upadhyay, Emine Senkardesler, Pratyush Tripathy, Okikiola Michael Alegbeleye  

**Developed for:** *I-GUIDE Summer School on "Spatial AI for Extreme Events and Disaster Resilience"*  
**Date:** August 4–8, 2025  

## **Data and Model Cards**
- [I-GUIDE Data Card DC01 – ERA5 Climate Data](https://github.com/surabhiupadhyay/RAP_India/raw/main/Model-and-Data-Cards/I-GUIDE%20Data%20Card_DC01.docx)
- [I-GUIDE Data Card DC02 – Alpha Earth Embeddings](https://github.com/surabhiupadhyay/RAP_India/raw/main/Model-and-Data-Cards/I-GUIDE%20Data%20Card_DC02.docx)
- [I-GUIDE Data Card DC03 – VIIRS Nighttime Data](https://github.com/surabhiupadhyay/RAP_India/raw/main/Model-and-Data-Cards/I-GUIDE%20Data%20Card_DC03.docx)
- [I-GUIDE Model Card MC01 – RAP Framework Model](https://github.com/surabhiupadhyay/RAP_India/raw/main/Model-and-Data-Cards/I-GUIDE%20Model%20Card_MC01.docx)

---

## **Variables**

### **Dependent Variable**
- **Survey-Based Drought Vulnerability Outcome**  
  *Examples:* Perceived flood risk, perceived drought risk  

### **Covariates / Independent Variables**

#### **Individual-Level**
- Age  
- Gender  
- Education  
- Caste  

#### **District-Level**
- **News Media Webscraping for Floods**  
- **VIIRS Nighttime Radiance**  
- **Alpha Earth Embeddings**  
- **ERA5 Climate Data:**  
  - Monthly Precipitation  
  - Monthly Temperature  

---

## **Modeling Scenarios**

### **Model 1: Baseline**
- Uses only individual-level demographic variables:  
  *Age, Gender, Education, Caste*

### **Model 2: Demographics + Physical Features**
- Includes **Model 1 variables** + **District-level physical features**:  
  *VIIRS Radiance, ERA5 Precipitation & Temperature, News Mentions*

### **Model 3: Demographics + Alpha Earth Embeddings**
- Includes **Model 1 variables** + **Alpha Earth Embeddings**

### **Model 4: Full Integrated Model**
- Combines **all covariates**:  
  *Demographics + District-level physical features + Alpha Earth Embeddings*

## **Machine Learning Methods**
- **Random Forest** 
- **XGBoost**
- **Logistic Regression**
