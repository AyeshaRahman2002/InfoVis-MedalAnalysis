InfoVis-MedalAnalysis
=====================

## Overview:
This project aims to evaluate how participants perceive and interpret historical Olympic medal data using interactive visualizations, such as line and area charts. The experiment spans Olympic Games data from 1896 to 2020 and includes a series of timed questions to test participants' comprehension of the visualized data.

## Key Features:
- Web-Based Questionnaire: A Python Flask web application that hosts the questionnaire. Participants analyze Olympic medal data through interactive visualizations.
- Visualizations: Two primary visualizations are utilized — a line chart displaying the medal counts for the top 10 countries and an area chart showing the total medal counts for selected countries across the years.
- Timed Questions: Each participant answers 20 randomized, timed questions based on the charts. These are designed to test their ability to understand trends and patterns in the data.
- Statistical Analysis: We recorded participants’ response times and accuracy to assess how effectively they interpreted the visualizations.

## Experiment Design:
- Questionnaire Setup: The questionnaire was developed using Python Flask, utilizing HTML for frontend rendering and Matplotlib for visualizations.
- Participants: Ten participants were recruited, each providing informed consent and completing the questionnaire in approximately 15-20 minutes.
- Data Collection: Response times and the accuracy of answers were tracked. Analysis focused on participants' ability to comprehend the visualized data.

## Team Members

As part of our coursework at the University of Leeds:

Ayesha Rahman

Sandra Guran

Natalie Leung

Geeyoon Lim

## Tasks Breakdown

1. Project Setup: Develop a web-based questionnaire using the Python Flask framework. Host the questionnaire on PythonAnywhere.
 ![Alt text](https://github.com/sc21samg/OlympicMedalAnalysis_Visualization/blob/main/1.0%20git.png)

2. Data Visualization, create two main charts:
Line Chart: Displaying medal counts for the top 10 countries from 1896-2020.
 ![Alt text](https://github.com/sc21samg/OlympicMedalAnalysis_Visualization/blob/main/1.1%20git.png)
Area Chart: Illustrating total medal counts for selected countries from 1896-2020.
 ![Alt text](https://github.com/sc21samg/OlympicMedalAnalysis_Visualization/blob/main/1.2%20git.png)
Generate subgraphs for each question to help guide participants.

3. Questionnaire
 ![Alt text](https://github.com/sc21samg/OlympicMedalAnalysis_Visualization/blob/main/1.4%20git.png)
Design 20 timed questions: 10 based on the line chart. 10 based on the area chart. The questions are randomized and designed to test participants' ability to interpret trends in the data.

4. Participant Recruitment: Gather 10 participants for the study. Ensure informed consent and anonymity throughout the experiment.

5. Data Collection: Record response times and track the accuracy of answers for each participant.
Analyze how well participants can comprehend the visual data.

6. Statistical Analysis: Analyze participant response times using descriptive statistics. Track correct and incorrect responses to evaluate comprehension. Perform t-tests to compare response times for line and area charts.

7. Results Reporting: Summarize findings on participants’ understanding of the historical distribution of Olympic medals. Report key insights, including response times, accuracy rates, and the absence of correlation between time spent and answer accuracy.

## Analysis:

Response Time & Accuracy: Each participant’s response time was recorded and analyzed along with their accuracy rates to determine comprehension levels. Statistical analysis such as T-tests were conducted to compare participants' performance on line versus area charts.

## Results:

Comprehension: Participants demonstrated a high overall comprehension of the visualizations, with an average accuracy rate of 93%.
Response Times: There was no significant correlation between time spent on each question and accuracy, suggesting that quicker responses were not necessarily less accurate.

## Technologies Used:
- Python Flask: Web framework for the questionnaire backend.
- Pandas & Matplotlib: Libraries used for data processing and visualization.
