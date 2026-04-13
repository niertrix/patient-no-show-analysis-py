# Patient No-Show Analysis
Python analysis done on the Kaggle Medical Appointment No Show dataset

# Dataset
[Medical Appointment No-Show](https://www.kaggle.com/datasets/joniarroba/noshowappointments)

# Steps to clean the data
1. The neighbourhoods' names are all capitalized and need to be fixed.
2. Reformat `[PatientId]` to be loaded properly.
3. `[ScheduledDay]` and `[ApponintmentDay]` are not formatted correctly. let's turn them into `datetime` format.
4. Let's also extract the time from `[ScheduledDay]` and put it in a new column.
5. Next, let's extract the date from `[ScheduledDay]` and `[AppointmentDay]`.
6. Transform some columns to category for optimization and ease-of-use.
7. Finally let's save the finished work!

# Insights
- The longer the waiting time the less likely patients are to show up.
- About 75% of patients showed up after receiving SMS messages.
- The elderly are actually more reliable than the youth, as the difference between the patients who showed up and ones who didn't decreases among older patients.

# Visualization
<img width="758" height="450" alt="waitingtime" src="https://github.com/niertrix/patient-no-show-analysis-py/blob/main/waitingtime.png" />

<img width="758" height="450" alt="SMSreceived" src="https://github.com/niertrix/patient-no-show-analysis-py/blob/main/SMSreceived.png" /> 

<img width="758" height="450" alt="agedifference" src="https://github.com/niertrix/patient-no-show-analysis-py/blob/main/agedifference.png" />

<p align="center" width="100%">
<video src="https://github.com/niertrix/patient-no-show-analysis-py/blob/main/Demonstration.mp4" width="80%" controls></video>
</p>
