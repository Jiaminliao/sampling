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

The number of your chosen topic: `#`3

Describe the purpose of your survey:

```
The purpose of the survey is to examine the relationship between age and music taste, with a specific focus on perceptions of popular music. The survey is used to study the differences in music preferences across age groups and how individuals change in their music taste across different stages of their life. The collected results might be used in an academic research paper intended for publication.

```

Describe your target population, sampling frame, sampling units, and observational units:
```
Target population: Adults in Toronto. 
Sampling frame: Individuals who are accessible through university (including students and staffs at University of Toronto) and community recruitment in Toronto.
Sampling units: individuals.
Observational units: individual survey responses.
Overall sampling strategy: Stratified sampling by age groups such as 18-25, 26-35, 36-45, 46-55, 56-65, 65+. Participants will be recruited through multiple channels including sending emails with survey links to registered UofT students and staffs, posting survey link on social media platforms like facebook, instagrams, etc., and placing posters in community centers and libraries to reduce selection bias associated with single source.
```

Your 5-10 question survey:
```
1. What is your age? (Please enter your age in years)
2. How often do you listen to music?
   - Daily
   - A few times per week
   - Occasionally
   - Rarely
3. Which three music genres do you listen to most often?
   (Select up to three)
   Pop, Jazz, Classical, Rock, ……, Other (please specify)
4. On a scale of 1–5, how much do you like today’s popular music?
    (1 = strongly dislike, 5 = strongly like)
5. Please briefly explain your answer. (Optional)
6. For each of the following age ranges, which music genre(s) did you like most?
   (Select up to two for each age range, if applicable)
   - Ages 12–17
   - Ages 18–25
   - Ages 26–35
   - Ages 36–45
   - Ages 46–55
   - Ages 56–65
7. To what extent do you think age influences music taste?
   (0 = Not at all, 10 = A great deal)
```

## Part B - Survey Evaluation:

Identify and describe survey features:

```
1. Sample type: Two-stage stratified probability sampling (survey with a cross-sectional design).
2. Sample size: A field sample of approximately 50,000 units was used. 
3. Target population: All persons 15 years of age and older living in the ten provinces of Canada. It excludes residents of institutions.
4. Sampling frame: The sampling frame combines landline and cellular telephone numbers from the Census and administrative sources with Statistics Canada’s dwelling frame.
5. Survey mode(s) : Electronic questionnaire or through CATI (computer assisted telephone interviewing).
6. Timeline: 2018-09-04 to 2018-12-28 for data collection, reference period: 12 months preceding the interview date
7. Response rate: 41.9%
8. Weights: Person-level estimation weights: Each respondent represents several individuals in the target population. The basic person weight (WGHT_PER) is provided for analysis at the individual level. The weights were adjusted to account for the subsampling of non-volunteers and were calibrated so that the weighted income distribution matches the 2017 CIS distribution by province. In addition to the estimation weights, bootstrap weights were performed for design-based variance estimation.
9. Data processing:  Used the SSPE set of generalized processing steps. Edits were performed automatically and manually at various stages of processing including family, consistency and flow edits. Error detection was implemented through built-in CATI edits with additional verification and correction conducted at head office. 
10. Cleaning, imputation, etc: See above answer for cleaning. For missing or incomplete data, imputation was primarily carried out using donor imputation based on a score function to identify the nearest donor record. When donor imputation was not possible, mean imputation was applied. 
11. Sources of error: Non-sampling error: coverage error (e.g., households without telephones) and non-response (both family or individual levels), response error, processing error. Sampling error/variability was estimated using bootstrap weights. 
12. Limitations, known biases, etc: Telephone coverage exclusion; non-response bias - reduced by adjustments to the survey weights and extracted data from administrative.
13. Link to documentation and any additional sources used: https://www23.statcan.gc.ca/imdb/p2SV.pl?Function=getSurvey&Id=796234
```

## Rubric

-	All required components are present and complete **Complete / Incomplete**
-	Choice of sampling strategy for Part A is justified and related to survey purpose **Complete / Incomplete**
-	Information for Part B is complete and correct **Complete / Incomplete**

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 14 January 2026`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (a2_survey_design_and_evaluation.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/sampling/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via the help channel in Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
