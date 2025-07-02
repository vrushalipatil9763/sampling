# Assignment: Questionnaire Design and Sample Evaluation

## Requirements

The goal of this assignment is to practice developing and evaluating sampling materials.

### Part A - Survey Design:

Select one of the scenarios below and design a survey to meet the need(s) outlined in the prompt.

1.	In two to three sentences, describe the purpose of your survey
2.	Describe your target population, sampling frame, sampling units, and overall sampling strategy.
3.	Write a 5-10 question survey to address your chosen scenario below.

##### Scenarios
1.	You work in the Human Resources Department at a large tech company. Over the past few months, the company has been experiencing a high turnover rate across many of its departments, specifically within the entry- and lower-level positions. The company wishes to understand why this turnover is happening, and what changes need to occur to improve employee satisfaction.
2.	You work for a Canadian national political party during a federal election. Throughout the campaign period, your party has seen relatively high approval ratings, but an opposing party is also polling favorably and may still have a chance to win the election. You are one month away from the election and you want to understand what voters want from your party and its leader in order to maintain your lead and eventually win the election.
3.	You are a student researcher in the sociology department at the University of Toronto. You are working on a research project that concerns the relationship between music taste and age. This involves both comparisons between different people of different ages and comparisons of the same individual at different ages during their lifetime. You wish to understand to what extent age influences music taste, specifically as it relates to perceptions of popular music. Your results will be written into an academic paper that you hope to publish.

### Part B - Survey Evaluation:

For the **Canadian General Social Survey on Giving, Volunteering, and Participating, 2018 (cycle 33)**, conducted by Statistics Canada find any and all available documentation for the data gathered and identify and describe the survey features indicated below.

1. Sample type
2. Sample size
3. Target population
4. Sampling frame
5. Survey mode(s) 
6. Timeline
7. Response rate
8. Weights
9. Data processing
10. Cleaning, imputation, etc
11. Sources of error
12. Limitations, known biases, etc
13. Link to documentation and any additional sources used


# Your Changes

## Part A - Survey Design: 

The number of your chosen topic: `#1`

Describe the purpose of your survey: 
```
To identify key factors behind high turnover in entry and lower level positions, assess employee satisfaction, and uncover concerns to help HR improve retention and workplace conditions.
```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: All employees of the company.
Sampling frame: Employees from departments that have reported high turnover rates in recent months.
Sampling units: Individual employees selected from the departments with high turnover.
Observational units: Entry level or lower level employees whose responses will be collected and analyzed.
```

Your 5-10 question survey:
```
1. Which department do you currently work in?
(Dropdown or list of departments) Select one
2. WWhat is your current position in the company? Select one
3. What is your exprience level? Select one
4. What is your current salary range? Select one
5. How satisfied are you with your current salary?  Select one (Very dissatisfied, Dissatisfied, Neutral, Satisfied, Very satisfied)
6. Which of the following offers from another company would most likely make you consider leaving your current job?  (10% hike, 20% hike, No hike but performance based bonus, Stock options or company shares, None of the above)
7. Have you experienced or observed any kind of bias or unfair treatment in your department? (Yes, No, Somewhat, Prefer not to say, (If yes, please specify – optional text box))
8. How would you rate your overall job satisfaction? (Very dissatisfied, Dissatisfied, Neutral, Satisfied, Very satisfied)
9. Do you feel there are opportunities for professional growth and career advancement in your department?
10. What changes or improvements would make you more likely to stay with the company? (text box)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
Sample Type:
A stratified random sampling method was used. The sample was carefully chosen to represent different provinces and metropolitan areas, ensuring good national coverage.

Sample Size:
Around 25,090

Target Population:
All individuals aged 15 years and older living in private households across the 10 provinces of Canada. 

Sampling Frame:
The sampling frame was built from telephone number/address combinations using random digit dialing, covering both landline and cell phones.

Survey Modes:
For respondents in the provinces data are collected either through an electronic questionnaire or through CATI (computer assisted telephone interviewing). No proxy reporting is allowed. The respondents have the choice between French and English. Interviews are approximately 45 minutes. In the territories, data are collected through an electronic questionnaire, telephone interviews or in-person interviews.

Timeline:
Various Data collection timelines avaiable for different survey topics:  like for Canadians at Work and Home (GSS), 2016-08-02 to 2016-12-23, Canadians' Safety: 2019-04-15 to 2020-03-31

Response Rate:
The average response rate is typically around 53%.

Weights:
The dataset comes with weighting variables so that the results represent the Canadian population properly. Bootstrap weights are also provided for estimating sampling errors.

Data Processing:
After collecting the data, responses were cleaned and anonymized. A Public Use Microdata File (PUMF) was created, where some sensitive variables were removed or grouped to maintain confidentiality.

Cleaning & Imputation:
No imputation was done for missing data. That means any gaps in responses were left as-is rather than filled in with estimates.

Sources of Error:
There are a few possible sources of error:
-Sampling error because it's based on a sample, not a census.
-Non-sampling error such as people not responding or differences in how people answer online vs over the phone.

Limitations / Known Biases:
-People in institutions and the territories weren’t included, so the results may not fully represent those groups.
-Since online response was introduced in 2018, comparisons with older years should be done carefully.
-Non-response bias could exist, though weighting tries to correct for it.


Links to Documentation:

https://www150.statcan.gc.ca/n1/pub/45-25-0001/index-eng.htm
https://abacus.library.ubc.ca/file.xhtml?persistentId=hdl:11272.1/AB2/GBFDYG/CSMQYR&version=1.0
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 29/06/2025`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [X] Create a branch called `assignment-2`.
- [X] Ensure that the repository is public.
- [X] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [X] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
