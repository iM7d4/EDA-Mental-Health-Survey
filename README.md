<h1 align="center"> EDA on Mental Health Survey </h1>

*A study of Mental Health in Tech by the Real Ricardo*

The data used in this notebook was downloaded from [Kaggle](https://www.kaggle.com/osmi/mental-health-in-tech-survey).
The source of the data was a survey done in 2014 by [OSMI](https://osmihelp.org/), a non-profit organization dedicated to raising awareness, educating, and providing resources to support mental wellness in the tech and open source communities.


**Below is a description of the questions (columns) asked in the survey:**

| Column  | Description  |
|---|---|
| Timestamp  | Date survey was filled  |
| Gender  | Gender identity of surveyed person  |
| Country  | Country of residence  |
| State  | US residents only  |
| self_employed  | Are you self-employed?   |
| family_history  | Do you have a family history of mental illness?  |
| treatment  | Have you sought treatment for a mental health condition?  |
| work_interfere  | If you have a mental health condition, do you feel that it interferes with your work?  |
| no_employees  | How many employees does your company or organization have?  |
| remote_work  | Do you work remotely (outside of an office) at least 50% of the time?  |
| tech_company  | Is your employer primarily a tech company/organization?  |
| benefits  | Does your employer provide mental health benefits?  |
| care_options  | Do you know the options for mental health care your employer provides?  |
| wellness_program  | Has your employer ever discussed mental health as part of an employee wellness program?  |
| seek_help  | Does your employer provide resources to learn more about mental health issues and how to seek help?  |
| anonymity  | Is your anonymity protected if you choose to take advantage of mental health or substance abuse treatment resources?  |
| leave  | How easy is it for you to take medical leave for a mental health condition?  |
| mental_health_consequence  | Do you think that discussing a mental health issue with your employer would have negative consequences?  |
| phys_health_consequence  | Do you think that discussing a physical health issue with your employer would have negative consequences?  |
| coworkers  | Would you be willing to discuss a mental health issue with your coworkers?  |
| supervisors  | Would you be willing to discuss a mental health issue with your direct supervisor(s)?  |
| mental_health_interview  | Would you bring up a mental health issue with a potential employer in an interview?  |
| mental_vs_physical  | Do you feel that your employer takes mental health as seriously as physical health?  |
| obs_consequence  | Have you heard of or observed negative consequences for coworkers with mental health conditions in your workplace?  |
| comments  | Any additional notes or comments?  |

## Technologies used ⚙️

* Python

* Statistics

##### Python Libraries : 
* Pandas | Numpy |  Matplotlib |  Seaborn | Scipy


### Visualizations
 
1. **History Treatment Willingness**
<p align="center">  <img src="https://github.com/iM7d4/EDA-Mental-Health-Survey/blob/main/visualizations/history_treatment_willingness.png" alt="Spotify Data Analysis using Python" width="80%" height="80%"/> </a> </p>
2. **Resouces and Awareness**
 <p align="center">  <img src="https://github.com/iM7d4/EDA-Mental-Health-Survey/blob/main/visualizations/resources_and_awareness.png" alt="Spotify Data Analysis using Python" width="80%" height="80%"/> </a> </p>
 
3. **Resource Willingness**
  <p align="center"> <img src="https://github.com/iM7d4/EDA-Mental-Health-Survey/blob/main/visualizations/resources_willingness.png" alt="Spotify Data Analysis using Python" width="80%" height="80%"/> </a> </p>
 
4. **Regression Plot for Resource Willingness**
 <p align="center"> <img src="https://github.com/iM7d4/EDA-Mental-Health-Survey/blob/main/visualizations/resources_willingness_regplot.png" alt="Spotify Data Analysis using Python" width="80%" height="80%"/> </a> </p>
 
5. **Work Interfere Willingness**
 <p align="center"> <img src="https://github.com/iM7d4/EDA-Mental-Health-Survey/blob/main/visualizations/work_interfere_willingness.png" alt="Spotify Data Analysis using Python" width="80%" height="80%"/> </a> </p>
 
6. **Workplace Resource History**
 <p align="center"> <img src="https://github.com/iM7d4/EDA-Mental-Health-Survey/blob/main/visualizations/workplace_resources_hist.png" alt="Spotify Data Analysis using Python" width="80%" height="80%"/> </a> </p>
 
### Interpretations 

1. Majority of the people are unwilling to talk about their mental health in the work environment.
2. Majority of the companies don't even have mental health resources available in the work environment.
3. Women are less likely to talk about their mental health issues. This might be resulting as tech might be considered as a male-dominent industry.
4. Average willingness score goes up as more resources are avaiable in the company.
