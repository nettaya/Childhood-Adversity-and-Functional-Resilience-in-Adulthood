# SISE2601 Project Data Description


## Description

This repository contains data related to the SISE2601 Project. The data has been
 processed and cleaned to create additional variables related to different types of distress.

## Data Structure

The dataset consists of the following columns:

- `physical_vars`: Variables related to physical distress.
- `mental_vars`: Variables related to mental distress.
- `environmental_vars`: Variables related to environmental distress.
- `financial_vars`: Variables related to financial distress.
- `education_vars`: Variables related to education.
- `service_vars`: Variables related to military service.
- `health_vars`: Variables related to health.
- `social_vars`: Variables related to social interactions.

## Column Descriptions

Here is a description of the columns:

- `physical_vars`: Variables related to physical distress.
  - `phisical_abuse_history_in_boardingschool`: Beatings of boarding school students.
  - `sexual_abuse_boarding_school_children`: Sexual harassment/assault from boarding school students.
  - `abuse_boarding_school_stuff`: Physical or sexual harm by boarding school staff.
  - `adult_Inappropriate_sexual_behavior`: Forced sexual contact by parent/adult.
  - `parental_violence`: Presence of parental violence.

- `mental_vars`: Variables related to mental distress.
  - `sudden_death_relative`: Sudden/unexpected death of a relative before age 18.
  - `verbal_violence_adult_scared`: Fear of being physically harmed by parent/adult.
  - `self_riskevent`: Involvement in a life-threatening event.
  - `bad_Family_relationships`: Feeling unimportant or uncared for by family.
  - `living_with_drugs_user_or_drinking_problem`: Living with a person with drug use 
     or drinking problem.

- `environmental_vars`: Variables related to environmental distress.
  - `witnessed_violence_against_mother`: Witnessing mother or caregiver being beaten or attacked.
  - `living_with_drugs_user_or_drinking_problem`: Living with a person with drug use 
     or drinking problem.
  - `witnessed_life_threatening_event`: Witnessing a life-threatening accident.
  - `relative_has_been_in_prison`: Household member having been in prison.
  - `family_bad_mental_health`: Presence of family members with poor mental health.

- `financial_vars`: Variables related to financial distress.
  - `financial_fam_distress`: Severe financial hardship in the family.
  - `highest_degree`: Highest diploma or degree received.
  - `professional_training`: Attendance of professional training courses after high school graduation.

- `education_vars`: Variables related to education.
  - `secondary_education`: Attendance of educational institution since high school graduation.
  - `lack_of_essentialsandprotection_parentdrunk`: Lack of food, clean clothes, or protection 
    when parents are drunk.

- `service_vars`: Variables related to military service.
  - `is_currently_serving_army`: Service or current service in the IDF.

- `health_vars`: Variables related to health.
  - `health_condition`: General state of health.
  - `chronic_medical_condition`: Presence of any health or physical problem.

- `social_vars`: Variables related to social interactions.
  - `often_phonecall_friends`: Frequency of phone calls with friends.
  - `friends_leisure_time`: Frequency of leisure time with friends.
  - `get_advice_from_relative`: Seeking advice from trusted individuals.

- `financial_vars`: Variables related to financial distress.
  - `jobs_num`: Number of jobs.
  - `full_time_job`: Whether the job is full-time.
  - `national_insurance`: Receipt of allowance from the National Insurance.
  - `gross_income`: Total gross income last month.
  - `cover_household_expenses`: Success in covering household expenses.
  - `forgoing_medical_treatment_financial_difficulties`: Giving up medical treatment due to financial 
     difficulties.
  - `employment_status`: Job status.

- Additional derived columns:
  - `physical_distress`: Average score of normalized physical distress variables.
  - `mental_distress`: Average score of normalized mental distress variables.
  - `environmental_distress`: Average score of normalized environmental distress variables.
  - `financial_distress`: Average score of normalized financial distress variables.
  - `education_group`: Average score of normalized education variables.
  - `service_group`: Average score of normalized service variables.
  - `health_group`: Average score of normalized health variables.
  - `social_group`: Average score of normalized social variables.
  - `financial_group`: Average score of normalized financial variables.

## Column Values

- Categorical variables (e.g., `physical_vars`, `mental_vars`, `environmental_vars`, 
`financial_fam_distress`, `professional_training`, `lack_of_essentialsandprotection_parentdrunk`, 
`service_vars`, `chronic_medical_condition`, `full_time_job`, `national_insurance`,
 `forgoing_medical_treatment_financial_difficulties`):
  - 1: Yes
  - 2: No

- `highest_degree`:
  - 1: Graduated from elementary school or middle school, including those who attended high school 
        and did not graduate
  - 2: High school graduation certificate
  - 3: Matriculation certificate
  - 4: High school graduation certificate that is not an academic certificate
  - 5: First academic degree B.A. or a Maccabi degree
  - 8: Another certificate
  - 9: Didn't get any certificate

- `secondary_education`:
  - 1: Studied in the past
  - 2: Currently studying, including on vacation/study break
  - 3: Did not study at an educational institution at all

- `health_condition`:
  - 1: Very good
  - 2: Good
  - 3: Reasonable

- `often_phonecall_friends`:
  - 1: Not at all
  - 2: Low
  - 3: Moderate
  - 4: Very high

- `friends_leisure_time`:
  - 1: Not at all
  - 2: 1-9 times
  - 3: 10 times or more

- `get_advice_from_relative`:
  - 1: Always or often
  - 2: Sometimes, occasionally
  - 3: Rarely
  - 4: Almost never
  - 5: Never

- `jobs_num`:
  - 1: 1 job
  - 2: 2 jobs

- `gross_income`:
  - 1: Up to 2,000 NIS
  - 2: 2,001-3,000 NIS
  - 3: 3,001-4,000 NIS
  - 4: 4,001-5,000 NIS
  - 5: 5,001-6,000 NIS
  - 6: 6,001-7,500 NIS
  - 7: 7,501-10,000 NIS
  - 8: 10,001-12,000 NIS
  - 9: Over 12,000 NIS

- `employment_status`:
  - 1: Employee
  - 2: Self-employed
  - 3: Unemployed
  - 4: Student

physical_distress
Average score of physical distress variables (normalized to a scale of 0-1)

mental_distress
Average score of mental distress variables (normalized to a scale of 0-1)

environmental_distress
Average score of environmental distress variables (normalized to a scale of 0-1)

financial_group
Average score of financial variables for grouping purposes (normalized to a scale of 0-1)

social_group
Average score of social variables for grouping purposes (normalized to a scale of 0-1)

health_group
Average score of health variables for grouping purposes (normalized to a scale of 0-1)

service_group
Average score of military service variables for grouping purposes (normalized to a scale of 0-1)

education_group
Average score of education variables for grouping purposes (normalized to a scale of 0-1)

## Data Source

The data was collected from a survey conducted as part of the SISE2601 Project. We were 
asked to provide information related to different types of distress they have experienced.



