---
section_id: Algorithm Architectures
nav_order: 3
title: Regression Models
nav: Regression Models
---

This section explores how to predict hospital length of stay (a continuous outcome) using regression models, with a focus on non-linearity, clinical thresholds, and fairness.

* **Data type:** Synthetic COVID-19 tabular EHR (calibrated to CIHI patterns)
* **Model type:** Linear regression and regression trees

## Presentation

<iframe src="[<iframe src="https://utoronto-my.sharepoint.com/personal/samantha_unger_mail_utoronto_ca/_layouts/15/Doc.aspx?sourcedoc={75ddc51a-3218-4e68-b7db-57a902126f56}&amp;action=embedview&amp;wdAr=1.7777777777777777" width="476px" height="288px" frameborder="0" title="PowerPoint Viewer">This is an embedded <a target="_blank" href="https://office.com">Microsoft Office</a> presentation, powered by <a target="_blank" href="https://office.com/webapps">Office</a>.</iframe>]" width="476px" height="288px" frameborder="0" title="PowerPoint Viewer">This is an embedded Microsoft Office presentation, powered by Office.</iframe>

Download the presentation [here](M2S3_slides.html)  
Download the video narration script [here](M2S3_video_script.md)

## Hands-On Exercise

In this exercise, you will analyze a synthetic dataset calibrated to Canadian CIHI COVID-19 hospitalizations. You will build, test, and compare a Linear Regression model and a Decision Tree Regressor.

* Download the Jupyter Notebook [here](M2S3_regression_los.ipynb)
* Download the Synthetic Dataset [here](covid_los_synthetic.csv)

## Resources

* [TeachYourselfCS - Conceptual Foundations](https://teachyourselfcs.com/)
* [Google Machine Learning Crash Course - Linear Regression](https://developers.google.com/machine-learning/crash-course/linear-regression)

{% capture text %}Note: When starting the hands-on exercise, ensure the synthetic dataset CSV is saved in the exact same folder as your Jupyter notebook so the code runs smoothly!{% endcapture %} 
{% include alert.html text=text color=secondary %}
