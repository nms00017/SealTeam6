===================================================================
GSCM-430: FINAL PROJECT - PHASE 1
PROJECT TITLE: GLOBAL FREIGHT BOTTLENECK PREDICTION
TEAM: SEAL TEAM 6 (202508-GSCM-430-002)
===================================================================

1. PROJECT OBJECTIVE

The goal of this project phase is to establish the foundation for predicting which airports or global regions are most likely to experience air freight bottlenecks.

The analysis uses historical air transport data combined with supplemental intermodal logistics data (e.g., port and truck routes) to identify points of high volume, high volatility, and rapid growth that pose a major risk to supply chain flow.

2. DELIVERABLES IN MAIN BRANCH

This 'main' branch contains all files required for the Part 1 assignment submission:

-- DATA FILES --
* data.csv: Original raw dataset (Global Air Transport Data).
* cleaned_data.csv: The cleaned, processed, and merged dataset ready for analysis.
* Port_of_Los_Angeles_-_TEU_Counts_Monthly_A...csv: Supplementary port volume data.
* New_York_City_Truck_Routes.csv: Supplementary ground logistics data.

-- ANALYSIS & DOCUMENTATION --
* EDA_Air_Freight_Bottlenecks.ipynb: Jupyter Notebook containing all Exploratory Data Analysis (EDA), including descriptive statistics and the three required visualizations (Load Trend, Volatility Risk, Growth Rate).
* README.md: This document.
* model_proposal.md: Clear statement on the proposed Classification Model and supporting source/citation.

3. REPOSITORY STRUCTURE & BRANCHING

The repository is structured with required branches for the next phases of the project:

* main: Latest stable version (always protected).
* data-prep: For data cleaning and feature engineering work.
* modeling: For Python machine learning model development.
* simulation: For AnyLogic files (.alp) and simulation scenario experiments.
* docs: For report drafts, slides, and documentation.

4. AI DISCLOSURE

In compliance with the GSCM-430 academic policy, the following AI assistance was utilized in the preparation of this project phase:

* TOOL: Gemini (Generative AI Assistant by Google)
* PURPOSE:
    - To generate and troubleshoot Python code templates for data loading and the required Exploratory Data Analysis (EDA) visualizations.
    - To assist in drafting and structuring the content of this README.md file and the model_proposal.md document.

All final analytical outputs, code, conclusions, and documentation have been thoroughly reviewed and approved by the human team members.

5. TEAM MEMBERS

*Nick Stock
*Gabe Sansom
*Frederick Walter
*Jake Jensen
*Garret Schoeb
