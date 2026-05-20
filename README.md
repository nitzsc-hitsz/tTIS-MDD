# tTIS-MDD
This study investigated the intervention effects of tTIS in treating MDD. 

Following an acute tTIS intervention protocol of 20 minutes per session over five consecutive days, 53.8% of the 26 enrolled patients (initially 31, 4 dropped out during follow-up and 1 was excluded for excessive motion) exhibited a treatment response immediately after the intervention at 4-week follow-up phase. The specific interventional outcomes of tTIS were further analyzed from the perspectives of static functional connectivity and leading eignvector dynamic analysis (LEiDA).

The Jupyter notebook files in this repository contain the code of intervention effect analysis of tTIS for MDD.

#1 Scale_plotting.ipynb -- The purpose of this notebook is to visualize the alteration of clinical scale scores.

#2 Amygdala_FC.ipynb -- This notebook functions to assess alterations in right amygdala functional connectivity during the treatment process.

#3 Network_FC.ipynb -- The purpose of this notebook is to examine post-treatment (D0 → D5-post) changes in DMN-LIM functional connectivity during the acute phase.

#4 run_LEiDA.ipynb -- The purpose of this notebook is to construct the necessary data structures and conduct the LEiDA analysis.

#5 LEiDA_results.ipynb -- This notebook functions to characterize the treatment-induced dynamics of LEiDA states following TIS, construct a Support Vector Classifier (SVC) framework, and predict subsequent clinical scale responses.

#6 State_Plotting.ipynb -- The purpose of this notebook is to visualize the spatial distribution of LEiDA states.

#7 State_sensitivity_schaefer.ipynb -- The purpose of this notebook is to compare the similarity of LEiDA states obtained from the Schaefer-100 atlas against the Schaefer-200 and Schaefer-400 results.
