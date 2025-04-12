### **Dataset Description:**

This **synthetic dataset** represents **20,000 records** of **Tuberculosis (TB)** patients in **Bangladesh**. It aims to simulate **real-world clinical, diagnostic, and treatment data** based on the **guidelines** and **standards** set by the **World Health Organization (WHO)**, the **National Tuberculosis Control Programme (NTP) of Bangladesh**, and the **Centers for Disease Control and Prevention (CDC)**.

This dataset is designed to reflect the variety of factors that impact **TB diagnosis**, **treatment**, and **outcomes**, with a focus on understanding **drug resistance**, **co-morbidities**, and the **geographic distribution** of TB cases across Bangladesh.

---

### **Dataset Features and Structure**:

#### **1. Patient Demographics**:
- **Patient ID**: Each record is uniquely identified with a **Patient ID** ranging from 1 to 20,000.
- **Age**: The **age** of each patient, ranging from **0 to 100 years**. This allows for the analysis of **age-related risk factors** for TB.
- **Gender**: Patient gender is categorized as **Male**, **Female**, or **Other**, providing insight into gender-based differences in TB incidence and treatment outcomes.
- **Region**: The dataset includes the geographic classification of patients, categorized into **Urban** and **Rural** regions. This allows for an exploration of how **location** impacts TB diagnosis, treatment adherence, and outcome.
- **Occupation**: Occupational categories include **Farmer**, **Laborer**, **Student**, **Worker**, and **Other**, as certain occupations may increase the risk of TB exposure or impact the likelihood of accessing healthcare.

#### **2. Clinical and Diagnostic Data**:
- **Symptoms**: Patients report symptoms including **Cough**, **Fever**, **Weight loss**, and **Night Sweats**. These symptoms are classified according to severity (Mild, Moderate, Severe) and can be used to explore symptom patterns among TB patients.
- **Sputum Smear Test**: This diagnostic test result is captured as **Positive** or **Negative**. The sputum smear is one of the most common methods for diagnosing TB.
- **GeneXpert Test**: The result of the **GeneXpert MTB/RIF test**, which is used to diagnose **drug-resistant TB** and determine the presence of **Mycobacterium tuberculosis**. The result is **Positive** or **Negative**.
- **Chest X-ray Results**: **Chest X-rays** are categorized as **Normal** or **Abnormal** to reflect radiological findings common in TB patients, with **Abnormal** results indicating the presence of TB-related lung damage.

#### **3. Treatment Information**:
- **Treatment Start Date**: The dataset captures the **number of days** since the patient started treatment. This helps model the progression of the disease and treatment timeline.
- **Treatment Type**: Patients are classified based on their treatment regimen:
  - **DOTS (Directly Observed Treatment, Short-course)**: The most common and widely recommended treatment for drug-sensitive TB.
  - **Drug-resistant TB treatment**: Treatment regimen for patients diagnosed with multi-drug-resistant TB (MDR-TB) or extensively drug-resistant TB (XDR-TB).
- **Duration of Treatment**: The treatment duration is simulated to range from **6 to 24 months**, which is consistent with WHO guidelines for TB treatment, including the extended treatment for drug-resistant TB cases.
- **Adherence Level**: The level of adherence to treatment is categorized as **Low**, **Moderate**, or **High**, which can be a critical factor in determining TB treatment success and relapse rates.
- **Drug Resistance**: A **Yes/No** value that indicates whether the patient has been diagnosed with drug-resistant TB, a growing concern globally and in Bangladesh.

#### **4. Clinical Outcomes**:
- **Treatment Outcome**: The dataset categorizes treatment outcomes into four main categories based on WHO guidelines:
  - **Cured**: The patient has completed treatment successfully and is considered free of TB.
  - **Failed**: The patient’s treatment did not succeed, indicating persistent infection.
  - **Lost to Follow-up**: The patient dropped out of treatment before completion.
  - **Death**: The patient passed away due to TB or complications related to the disease.
- **Relapse**: Indicates whether the patient experienced a **relapse** of TB after completing the treatment.
- **Mortality**: A binary value indicating whether the patient died due to TB or complications arising from the disease.

#### **5. Co-morbidities**:
- **Diabetes**: A binary value indicating whether the patient has **Diabetes**, which is a known risk factor for TB progression and poorer outcomes.
- **HIV**: A binary value indicating whether the patient has **HIV**. Co-infection with HIV and TB is common, and HIV status significantly affects TB prognosis and treatment outcomes.
- **Chronic Lung Disease**: Indicates whether the patient has other chronic lung diseases such as COPD, which can complicate TB treatment.
- **Malnutrition**: Malnutrition is a common risk factor for TB progression, and it’s important for understanding patient vulnerabilities.

#### **6. Social and Environmental Factors**:
- **Smoking Status**: Classifies patients as **Non-smoker**, **Smoker**, or **Ex-smoker**. Smoking significantly increases the risk of TB progression and complications.
- **Alcohol Consumption**: Indicates whether the patient is a **Non-drinker**, **Drinker**, or **Ex-drinker**. Alcohol consumption can impact TB treatment adherence and health outcomes.
- **Living Conditions**: Classifies the patient’s living conditions as **Poor**, **Average**, or **Rich**, which can influence access to healthcare and treatment adherence.
- **Access to Healthcare**: Indicates whether the patient has **access to healthcare services** (Yes/No). Healthcare access is a key determinant in early TB detection and treatment success.

#### **7. Geographic Data**:
- **City**: Represents the patient’s city of residence, with categories like **Dhaka**, **Chittagong**, **Khulna**, **Rajshahi**, and **Sylhet**. These cities have varying levels of healthcare infrastructure and TB burden.
- **Region Code**: A numeric value representing the administrative regions in Bangladesh. There are **64 regions** in Bangladesh, and this variable allows for regional analysis of TB distribution.

---

### **Dataset Use Cases**:
This dataset is designed for use in research and analysis related to:
- **Epidemiological Studies**: Understanding the geographic distribution and risk factors for TB in Bangladesh.
- **Predictive Modeling**: Building machine learning models to predict TB treatment outcomes based on demographic, clinical, and treatment data.
- **Public Health Research**: Identifying correlations between co-morbidities, treatment adherence, and TB outcomes.
- **Health Systems Analysis**: Studying the impact of healthcare access and living conditions on TB outcomes.

---

### **References**:
This dataset is based on the following official guidelines and sources:

1. **World Health Organization (WHO)**, **Global Tuberculosis Report 2022**, [WHO Global Tuberculosis Report](https://www.who.int/teams/global-tuberculosis-programme/tb-reports).
2. **National Tuberculosis Control Programme (NTP) Bangladesh**, **Annual Report 2022**, [NTP Bangladesh Annual Report 2022](https://www.ntp.gov.bd/wp-content/uploads/2024/01/Annual-Report-2022.pdf).
3. **Centers for Disease Control and Prevention (CDC)**, **Clinical Guidance for Tuberculosis Treatment**, [CDC Tuberculosis Clinical Guidelines](https://www.cdc.gov/tb/hcp/clinical-guidance/index.html).

---

### **Conclusion**:
This dataset is a valuable resource for researchers, healthcare professionals, and data scientists interested in understanding **Tuberculosis (TB)** in **Bangladesh**. It provides a broad range of **clinical, demographic**, and **social** factors that impact **TB diagnosis**, **treatment**, and **outcomes**. The dataset is particularly useful for studying **drug-resistant TB**, **co-morbidities**, and the **impact of healthcare access** on TB outcomes.

If any researcher wants to publish a research paper on this dataset, they must contact the author "NISHAT VASKER".Without author's permission, this dataset research output is strictly not usable and legal actions will be taken because this dataset contains sensitive medical data.
