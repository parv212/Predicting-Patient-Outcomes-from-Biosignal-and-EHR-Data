# Predicting-Patient-Outcomes-from-Biosignal-and-EHR-Data

Healthcare is a highly lucrative industry that could benefit significantly, both in regard to patient outcomes and cost savings, from machine learning and predictive modeling. While some progress has been made in this space, including image classification of tumors, natural language processing of electronic health records (EHR), and predictive models for cancer treatments, ample amounts of opportunities remain. 

One challenge to developing highly accurate and generalizable models for healthcare is the lack of large, diverse, and time-aligned datasets. The creators of the VitalDB dataset [1] sought to address this challenge by aggregating information from EHRs and vital sign monitoring systems in order to create a rich dataset that contains highly granular (i.e. 500 Hz) biosignal data with pre-, intra- and postoperative patient outcomes. 

The goal of this project is to develop models that predict several patient outcomes, including patient diagnoses, surgical anesthesia type and duration, ICU length of stay and mortality rate. Inputs will include clinical information from EHRs as well as time series biosignals measured during a patient’s hospital stay. The result of this project is to create several predictive models that, when taken together, inform a patient’s journey through their hospital stay.
