# Predicting-Progression-to-Severe-Glaucoma-based-on-Visual-Field-Tests-
Predicting the rate of progression to severe glaucoma can assist in the development of personalized treatment. The purpose of the study is to provide a time-to-event model that predicts the time interval of conversion from non-severe to severe glaucoma using VFs
We retrospectively used the Glaucoma Research Network and all VFs were converted to right
eye format with a temporal granularity of 1 year. We defined mean deviation (MD) of -12 dB
as the cutoff point for severe-stage glaucoma—tests with MD less than -12dB are deemed as
severe glaucoma. The 52 total deviation (TD) values of each VF served as input for a Cox
proportional hazard regression model with L2- regularization, to compute the hazard function
of progressing to severe glaucoma. The performance of the model was evaluated using the
concordance index (C-index) and Brier score in the first year. C-index is the ratio of
concordance between non-severe time and predicted risk. It is similar to AUC where 1
corresponds to prefect prediction accuracy and 0.5 corresponds to random prediction. Brier
score at time t is the mean square error between observed survival status and predicted
probability on survival at time t. Brier score ranges from 0 to 1 where 0 is the best possible
value. We defined 16 VF archetypes for analysis.1 For each archetype, we calculated the
average value of each TD spot, generating an average VF. The average VFs were utilized for
prediction with the Cox model to investigate the progression rates of archetypes. We plotted
Kaplan-Meier curves to show rates of conversion of pre-severe glaucoma to severe stage over
20 years for different archetypes.
