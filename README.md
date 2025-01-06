# Diabetes-Patient-s-Hospital-Readmission
Analyzed hospital readmission data for diabetes patients across 130 U.S. hospitals using Python. The project focused on identifying factors influencing readmission rates, including demographics, medical history, and hospital-related attributes, to provide actionable insights for healthcare decision-making.
# **Diabetes Patients' Hospital Readmission Analysis**

## **Project Overview**  
Analyzed hospital readmission data for diabetes patients across 130 U.S. hospitals using Python. The project focused on identifying factors influencing readmission rates, including demographics, medical history, and hospital-related attributes, to provide actionable insights for healthcare decision-making.

---

### **Key Steps and Methodologies**  
1. **Data Cleaning & Transformation**:  
   - Addressed missing values (e.g., race, diagnoses) and removed redundant features like `payer_code` and `weight`.  
   - Mapped categorical IDs (e.g., admission source) to readable labels for better interpretability.  

2. **Feature Engineering**:  
   - Created custom variables such as `hospital_stay_type` (Short, Medium, Long) and `diabetes_med_usage`.  
   - Introduced flags for high medication usage and categorized length of stay for better pattern recognition.  

3. **Data Merging**:  
   - Integrated JSON files for admission types, discharge dispositions, and admission sources to enhance dataset richness.  

4. **Visualization & Insights**:  
   - Bar plots, histograms, and box plots were used to explore trends in hospital stays, medication usage, and readmission rates.  
   - Identified that emergency admissions and high medication usage significantly correlated with higher readmission rates.  
   - Found elderly patients (80+) and patients with long hospital stays are at increased risk for readmission.  

---

## **Key Insights**  
- Emergency admissions and high medication usage drive higher readmission rates.  
- Elderly patients and those with long hospital stays need tailored care strategies to reduce readmissions.  
- Gender and race-specific trends suggest disparities in healthcare outcomes, requiring targeted interventions.

---

## **Conclusion**  
This analysis provides actionable insights for healthcare providers to reduce readmission rates, improve patient care, and allocate hospital resources effectively.

