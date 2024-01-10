# itsm

## **Business Case-Study**

ABC Tech is an mid-size organisation operation in IT-enabled business
segment over a decade. On an average ABC Tech receives 22-25k IT
incidents/tickets , which were handled to best practice ITIL framework
with incident management , problem management, change management
and configuration management processes. These ITIL practices attained
matured process level and a recent audit confirmed that further
improvement initiatives may not yield return of investment.
ABC Tech management is looking for ways to improve the incident
management process as recent customer survey results shows that
incident management is rated as poor.

Machine learning looks prospective to improve ITSM processes through
prediction and automation. They came up with key areas, where ML can
help ITSM process in ABC Tech.

**1)** Predicting High Priority Tickets so that they can take preventive measures or fix the problem before it surfaces.

**2)** Forecast the incident volume monthwise and quarterwise. So that they can be better prepared with resources and technology planning.

**3)** Auto tag the tickets with right priorities and right departments so
that reassigning and related delay can be reduced.


## **Dataset Description**

This Dataset contain Total of 24 features and 1 Target(Priority)

1) CI_Name: Represents the Configuration Item (CI) Name, which is an element of
the IT infrastructure that is managed in the context of IT Service Management.

2) CI_Cat: Denotes the category of the Configuration Item.

3) CI_Subcat: Specifies the subcategory of the Configuration Item. It provides more detailed information about the type of CI.

4) WBS: Stands for Work Breakdown Structure. It is a project management tool that represents a hierarchical decomposition of the total scope of work to be carried out by the project team.

5) Incident_ID: Unique identifier for each incident. It is a reference number or code assigned to each reported incident.

6) Status: Represents the current status of the incident.

7) Impact: Indicates the impact of the incident on the business or IT services.

8) Urgency: Reflects the urgency of addressing the incident.

9) Priority: Represents the overall priority assigned to the incident, which is often a combination of impact and urgency.

10) number_cnt: It's not explicitly described, but it may be a numerical count  associated with something in the dataset.

11) Category: Denotes the category of the incident, providing additional classification information.

12) KB_number: May refer to a Knowledge Base (KB) article number. Knowledge base articles are often used for documenting solutions to common issues.

13) Alert_Status: Represents the status of any alerts associated with the incident.

14) No_of_Reassignments: Indicates the number of times the incident has been reassigned or transferred to different support personnel or groups.

15) Open_Time: Represents the timestamp when the incident was initially reported or opened.

16) Reopen_Time: Timestamp indicating when the incident was reopened, if applicable.

17) Resolved_Time: Timestamp indicating when the incident was resolved or fixed.

18) Close_Time: Timestamp indicating when the incident was closed or marked as completed.

19) Handle_Time_hrs: Represents the time taken to handle or resolve the incident, often measured in hours.

20) Closure_Code: Denotes the code or reason for closing the incident.

21) No_of_Related_Interactions: Indicates the number of related interactions associated with the incident.

22) Related_Interaction: Information about the related interactions associated with the incident.

23) No_of_Related_Incidents: Represents the number of incidents related to the current incident.

24) No_of_Related_Changes: Indicates the number of related changes associated   with the incident.

25) Related_Change: Information about the related changes associated with the incident.


![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/f08fe065-c9c1-4d14-bd0a-1a0c1ec4ea7a)

![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/6bfcf991-665f-453b-9778-9f6c6017ea54)



## **Model Creation**

**1) Decision Tree**

**2) Random Forest**

**3) Gradient Boosting**

## **Model Comparision Report**

![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/8058918e-dc21-4b01-a968-5e68ea730263)

![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/36c558bc-d871-4dc3-843a-760d7c32973a)


------
## **Forcast the incident volume month-wise and quarter-wise**
![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/03bb5f4b-e468-4997-a62a-01add30b0a7f)

![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/a89a90c9-9ca2-435b-95c3-7ea2f2cc1771)


## **Auto Tagging**


## **Model Creation**

**1) Decision Tree**

**2) Random Forest**

**3) Gradient Boosting**

![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/fc807b9c-8668-486d-905a-61f61a41f7ca)

![image](https://github.com/Bamit-2021/ITSM_Tickets_Prediction/assets/77608956/ccb3cca1-2909-49a9-b2ab-24681948e8ac)


## **Challenges Faced:**

1) Empty cells present in features but not showing in isnull().sum() code, so we have to perform logic to show it into null values.

2) Given handle time hr is not understood we create our own handle time from open time and resolve time.

3) Selecting the best parameter range for Hyperparameter tuning in the Decision Tree and Random Forest model for  high-priority Tickets and Auto Tag objectives.

4) Creating Monthwise features with incidents from open time and CI_Cat is tricky and requires logic.

5) Creating Quarterwise features with incidents from open time and CI_Cat is tricky and requires logic.


