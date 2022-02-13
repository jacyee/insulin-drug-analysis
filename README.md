## Phase 2 clinical trial data for Auralin and Novodra Trials
<br>
350 patients for new oral insulin Auralin,half of the patients are being treated with Auralin, and the other 175 being treated with injectable insulin Novodra.
<br>
use HBA1C level change as key metric to determine if Auralin drug is effective enough to reduce blood sugar level for diabetes patients
<br>
<b>patients,treatments, adverse reactions data</b>
<br>
Data schema 
<br>
patients columns:
<br>
patient_id: the unique identifier for each patient in the Master Patient Index (i.e. patient database) of the pharmaceutical company that is producing Auralin
assigned_sex: the assigned sex of each patient at birth (male or female)
given_name: the given name (i.e. first name) of each patient
surname: the surname (i.e. last name) of each patient
address: the main address for each patient
city: the corresponding city for the main address of each patient
state: the corresponding state for the main address of each patient
zip_code: the corresponding zip code for the main address of each patient
country: the corresponding country for the main address of each patient (all United states for this clinical trial)
contact: phone number and email information for each patient
birthdate: the date of birth of each patient (month/day/year). The inclusion criteria for this clinical trial is age >= 18 (there is no maximum age because diabetes is a growing problem among the elderly population)
weight: the weight of each patient in pounds (lbs)
height: the height of each patient in inches (in)
bmi: the Body Mass Index (BMI) of each patient. BMI is a simple calculation using a person's height and weight. The formula is BMI = kg/m2 where kg is a person's weight in kilograms and m2 is their height in metres squared. A BMI of 25.0 or more is overweight, while the healthy range is 18.5 to 24.9. The inclusion criteria for this clinical trial is 16 >= BMI >= 38.
<br>
treatments columns:
<br>
given_name: the given name of each patient in the Master Patient Index that took part in the clinical trial
surname: the surname of each patient in the Master Patient Index that took part in the clinical trial
auralin: the baseline median daily dose of insulin from the week prior to switching to Auralin (the number before the dash) and the ending median daily dose of insulin at the end of the 24 weeks of treatment measured over the 24th week of treatment (the number after the dash). Both are measured in units (shortform 'u'), which is the international unit of measurement and the standard measurement for insulin.
novodra: same as above, except for patients that continued treatment with Novodra
hba1c_start: the patient's HbA1c level at the beginning of the first week of treatment. HbA1c stands for Hemoglobin A1c. The HbA1c test measures what the average blood sugar has been over the past three months. It is thus a powerful way to get an overall sense of how well diabetes has been controlled. Everyone with diabetes should have this test 2 to 4 times per year. Measured in %.
hba1c_end: the patient's HbA1c level at the end of the last week of treatment
hba1c_change: the change in the patient's HbA1c level from the start of treatment to the end, i.e., hba1c_start - hba1c_end. For Auralin to be deemed effective, it must be "noninferior" to Novodra, the current standard for insulin. This "noninferiority" is statistically defined as the upper bound of the 95% confidence interval being less than 0.4% for the difference between the mean HbA1c changes for Novodra and Auralin (i.e. Novodra minus Auralin).


