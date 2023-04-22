# Dams_Survival_Analysis

This repository contains the required information to reproduce the findings associated to the study: "How often do large dams fail? 
Past, present and future", submited to be considered as a research article.

The dataset is structured as follows:

1- WRD_rmduplicates.xlsx: Dataset consisting of the world register of dams dataset from ICOLD (version updated 2020) in which the duplicates 
between dam failures and standing dams have been elliminated to create a survival analysis dataset. This material is available upon purchase 
(publicly) from the ICOLD webpage. Please add the world register of dams in the main folder and rename it as WRD_rmduplicates.xlsx

2- ICOLD_failures_full.xlsx: Dataset containing large dam failures registered in history until 2018 provided by ICOLD (version updated 2019).
This material is available upon purchase (publicly) from the ICOLD webpage. Please add the ICOLD failures bulleting in the main folder and rename it
ICOLD_failures_full.xlsx

3- GDP_ppp_WRD.xlsx: List of all countries purchase party power gross domestic product in international USD (2018). Extracted from the public
records of the World Bank economic data repository.

4- LargeDamFailures2018_2022.xlsx: Dataset of all known (to the authors) large dams failures in the period 2018-2022. This has been manually
collected by the authors based on press, technical reports and literature. It is used to test the validity of our dam failure future predictions.

5- SurvivalAnalysis_sub.ipynb: Python scripts with the routines to replicate the findings in the article based on these datasets.
