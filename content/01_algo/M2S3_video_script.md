# M2S3: Video Narration Script

**Slide 1 – Title & Overview**
Welcome to Module 2, Session 3: Regression Models for predicting hospital length of stay. In earlier sessions, we focused on classification problems. Today we’ll shift to regression, where the goal is to predict a continuous value: how many days a patient will stay in hospital.

**Slide 2 – Why LOS Prediction Matters**
From an operational perspective, hospitals use LOS to plan bed capacity, manage nurse staffing, and coordinate safe discharge. Clinically, it helps us set realistic expectations and line up social work or home-care supports early.

**Slide 3 – Our Data**
We use a small synthetic dataset that looks like a Canadian COVID‑19 inpatient cohort. Each row describes one patient at admission, with features such as age, heart rate, blood pressure, ICU status, and number of comorbidities. Our target is LOS in days.

**Slide 4 – Linear Regression**
Linear regression is essentially about drawing a line of best fit through the data points to minimize the prediction errors. You can read the slope as “for each extra year of age, LOS changes by this many days.”

**Slide 5 – Regression Trees**
Trees provide a more flexible alternative to handle clinical thresholds (like when a lab value crosses a critical line and suddenly increases risk). They split patients into groups using simple if-then rules, which often align well with how clinicians actually think.