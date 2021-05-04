| Field name | 	Type | 	Description | 
| --- |	 --- |	 --- |
| batch_date | 	Date | 	Date when they entry was extracted from the data warehouse. | 
| test_name | 	String | 	Name of the COVID-19 test, used to infer its sensitivity and specificity. | 
| swab_type | 	String (Nasopharyngeal, Oropharyngeal, Nasal) | 	COVID-19 test sample collection area. | 
| covid19_test_results | 	String (Positive, Negative) | 	COVID-19 test results. | 
| age | 	Int | 	Noise-added patient age. | 
| high_risk_exposure_occupation | 	Boolean | 	Whether patient in a profession with a high risk of exposure. | 
| high_risk_interactions | 	Boolean | 	Whether patient may have been exposed through contact with a known infected person. | 
| diabetes | 	Boolean | 	Whether patient has diabetes. | 
| chd | 	Boolean | 	Whether patient has coronary heart disease. | 
| htn | 	Boolean | 	Whether patient has hypertension. | 
| cancer | 	Boolean | 	Whether patient has cancer. | 
| asthma | 	Boolean | 	Whethe patient has asthma. | 
| copd | 	Boolean | 	Whether patient has chronic obstructive pulmonary disease. | 
| autoimmune_dis | 	Boolean | 	Whether patient has an autoimmune disease. | 
| smoker | 	Boolean | 	Whether patient is a smoker. | 
| temperature | 	Float | 	°C | 
| pulse | 	Int | 	Heart rate measured as the number of heartbeats per minute (bpm). | 
| sys | 	Int | 	Systolic blood pressure measured in units of millimeters of mercury (mmHg). | 
| dia | 	Int | 	Diastolic blood pressure measured in units of millimeters of mercury (mmHg). | 
| rr | 	Int | 	Respiratory rate measured in breaths per minute. | 
| sats | 	Int | 	Oxygen saturation (cka "sat") measured as the percentage of hemoglobin binding sites in the bloodstream occupied by oxygen. | 
| rapid_flu_results | 	String (Positive, Negative) | 	Rapid flu test result if administered. | 
| rapid_strep_results | 	String (Positive, Negative) | 	Rapid strep test result if administered. | 
| ctab | 	Boolean | 	Whether the lung exam is normal, that is, lungs clear to auscultation bilaterally. | 
| labored_respiration | 	Boolean | 	Whether patient is experiencing abnormal respiration characterized by increased effort to breathe. | 
| rhonchi | 	Boolean | 	Whether patient is experiencing rhonchi, which is a coarse rattling sound like snoring, usually caused by secretion in a bronchial tube. | 
| wheezes | 	Boolean | 	Whether patient is experiencing wheezing, which is a high-pitched whistling sound made while breathing. | 
| days_since_symptom_onset | 	Int | 	Patient reported days from symptom onset. | 
| cough | 	Boolean | 	Whether patient has cough symptoms. | 
| cough_severity | 	String (Mild, Moderate, Severe) | 	Severity of cough as reported by patient | 
| fever | 	Boolean | 	Whether patient has fever. | 
| sob | 	Boolean | 	Whether patient has shortness of breath. | 
| sob_severity | 	String (Mild, Moderate, Severe) | 	Severity of shortness of breath. | 
| diarrhea | 	Boolean | 	Whether patient has diarrhea. | 
| fatigue | 	Boolean | 	Whether patient is experiencing fatigue. | 
| headache | 	Boolean | 	Whether patient is experiencing a headache. | 
| loss_of_smell | 	Boolean | 	Whether patient is experiencing loss of smell. | 
| loss_of_taste | 	Boolean | 	Whether patient is experiencing loss of taste. | 
| runny_nose | 	Boolean | 	Whether patient has a running nose. | 
| muscle_sore | 	Boolean | 	Whether patient has sore muscles. | 
| sore_throat | 	Boolean | 	Whether patient has a sore throat. | 
| cxr_findings | 	String | 	Observations about the lungs and chest as seen on the chest radiograph. | 
| cxr_impression | 	String | 	Summary of the clinically relevant chest radiograph finding(s). | 
| cxr_label | 	String (Negative, Significant, Critical) | 	Categorized label based on cxr_impression. | 
| cxr_link | 	String (url) | 	Link to the dagnostic quality radiology images, with annotations and report. | 
| er_referral | 	Boolean | 	Whether patient was referred to ER (true), or sent home (false). | 
| WBC | 	Int | 	White blood cell count (per mcL). | 
| Hgb | 	Int | 	Hemoglobin concentration (per mcL). | 
| Plt | 	Int | 	Platelet count (per mcL). | 
| Na | 	Float | 	Blood sodium levels measured in mEq/L. | 
| K | 	Float | 	Blood potassium levels measured in mEq/L. | 
| Cl | 	Float | 	Blood chloride levels measured in mEq/L. | 
| CO2 | 	Float | 	Blood CO2 levels measured in mEq/L. | 
| BUN | 	Float | 	Blood Urea Nitrogen measured in mg/dL. | 
| Cr | 	Float | 	Creatinine levels measured in mg/dL. | 
| Troponin | 	Float | 	Troponin levels measured in ng/ML. | 
| D-dimer | 	Float | 	D-dimer levels measured in ng/mL. | 
| Ferritin | 	Float | 	Blood ferritin levels measured in ng/mL used to measure iron deficiency, it is also an acute phase reactant | 
| Pro-calcitonin | 	Float | 	PCT levels measured in ng/mL used for the diagnosis of sepsis or other serious bacterial infections. | 
| INR | 	Float | 	International normalized ratio. | 
| BNP | 	Float | 	B-type natriuretic peptide levels measured in pg/mL. | 
| Fibrinogen | 	Float | 	Fibrinogen levels in blood plasma (mg/dL). | 
| Gluc | 	Float | 	Blood glucose concentration, measured in mmol/L. | 
| A1C | 	Float | 	Percentage of glycated hemoglobin. | 
| CRP | 	Float | 	Concentration of C reactive protein in blood plasma (mg/L). | 
| HCQ | 	Boolean | 	Whether hydroxychloroquine was administered. | 
| chloroquine | 	Boolean | 	Whether chloroquine was administered. | 
| azithromycin | 	Boolean | 	Whether the antibiotic drug azithromycin was administered. | 
| remdesivir | 	Boolean | 	Whether remdesivir was administered. | 
| lopinavir/ritonavir | 	Boolean | 	Whether the combination of lopinavir and ritonavir were administered. | 
| tocilizumab | 	Boolean | 	Whether tocilizumab, aka atlizumab was administered. | 
| ACEi | 	Boolean | 	Whether patient was taking any "ACE inhibitor" medication class prior to presentation. | 
| statin | 	Boolean | 	Whether patient was taking any "statin" medication class prior to presentation. | 
| admitted_to_icu | 	Boolean | 	Whether patient has been admitted to the ICU. | 
| mech_ventilation | 	Boolean | 	Whether mechanical ventilation was used. | 
| ECMO | 	Boolean | 	Whether an extracorporeal membrane oxygenation machine was used. | 
| LOS | 	Int | 	Length of stay in days, subtract day of admission from the day of discharge. | 
| ARDS | 	Boolean | 	Whether patient is diagnosed with acute respiratory distress syndrome. | 
| shock | 	Boolean | 	Whether patient is diagnosed with shock, an acute circulatory failure. | 
| acute_kidney_injury | 	Boolean | 	Whether patient is diagnosed with acute kidney injury. | 
| secondary_pneumonia | 	Boolean | 	Whether patient is diagnosed with secondary bacterial pneumonia, following an initial presentation of viral pneumonia. | 
| recovery | 	Boolean | 	Whether patient survived to discharge (excluding patients discharged to hospice). | 
| death | 	Boolean | 	Whether patient died while in hospital, or was sent to hospice care. | 
