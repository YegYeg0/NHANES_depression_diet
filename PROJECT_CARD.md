# Project Card

## Dataset and scope 

Dataset: National Health and Nutrition Examination Survey (NHANES)

Cycle: August 2021–August 2023

Files: DEMO_L, SLQ_L, PAQ_L, BPXO_L, and BMX_L

Identifier for merging: SEQN

Initial analytic population: NHANES participants aged 18 years and older, subject to availability of the required measurements.

## Temporary title

The Impact of Lifestyle on Cardiovascular Health

## Main statistical question

How do sleep duration and physical activity levels associate with systolic blood pressure in adults(20 years old and above), and do these associations differ across BMI categories?
## Unit of observation

One NHANES participant, represented by `SEQN`. The analytical dataset will contain at most one row per participant.

## Main variables

- `DPQ010`–`DPQ090`: nine depression-screening symptom items.
- `phq9_score`: derived sum of valid symptom-item scores, subject to codebook verification.
- `DR1TSUGR`: total sugars in grams from the first dietary recall day.
- A first-day dietary weight and appropriate survey design variables.
- Age and selected demographic or socioeconomic variables for descriptive summaries and later analyses.
- `DR1TKCAL`: first-day energy intake in kilocalories, subject to codebook verification.

## Variable roles

- **Systolic blood pressure (mmHg):** Response variable - Quantitative, continuous.
- **Usual sleep duration:** Explanatory variable - Quantitative, recorded in hours.
- **Physical activity:** Explanatory variable - Depends on the selected activity measure.
- **BMI:** Grouping or explanatory variable - Quantitative, continuous; may also be categorized.
- **Age:** Demographic variable - Quantitative, recorded in years.
- **Sex recorded in NHANES:** Demographic variable - Categorical.

## Type of study

Primarily associational and comparative.

## Initial hypothesis

Sleep duration and physical activity may be associated with systolic blood pressure, and the observed associations may differ across BMI categories.

## Initial limitations

1. NHANES is observational, so associations cannot by themselves establish causation or temporal order.
2. Sleep and physical activity are self-reported and may be affected by recall or reporting error.
3. Missing measurements may reduce the number of participants included in the analysis.
4. NHANES uses a complex sampling design, so population-level estimates require appropriate weights and survey-design considerations.
