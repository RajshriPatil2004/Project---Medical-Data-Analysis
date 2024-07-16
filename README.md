# Project: Medical-Data-Analysis
1. Problem Analyze the patients past data containing vital signs to extract insights which separates the survivor and non-survivor patients.
2. Data The dataset which was used for analysis here is taken from the mimic website. But the dataset is not in the correct format which we want, after some manipulation we get the data ready for the analysis.
3. Approach
To protect patient confidentiality date and time is shifted to future that's not the actual time so from shifted time column we create an extra column hours which tells us the time passed in hours since first observation in ICU.
After all manipulation our final dataset contain vital signs values for each observation of patients with time in separate column and also the label fo Death(0 or 1) in another column.
There are two options to deal with missing values
