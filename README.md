# Analysis-on-HackerRank-Developer-Survey-2018
Analysis on a survey conducted by HackerRank to ask developers about their age, educational background, skills and more.

## Context
HackerRank (https://www.hackerrank.com), building a platform to create the best experience for both individuals and companies, conducted a survey of their developers late in 2016 in order to provide more transparency for themselves and the world on the state of developers. The survey asked developers many questions around their skills, educational background, current role, and more. The data set they released is the full dataset of 25K responses from our developer survey, which includes both students and professionals.


## Data Discription
The data consists of five files:

<b>HackerRank-Developer-Survey-2018-Codebook.csv</b>: 
a CSV file with survey schema. This schema includes the questions that correspond to each column name in HackerRank-Developer-Survey-2018-Numeric.csv and HackerRank-Developer-Survey-2018-Values.csv. It also provides extra notes on questions if they were conditionally shown, or what the correct answer was to a coding question.

<b>HackerRank-Developer-Survey-2018-Numeric-Mapping.csv</b>: This file provides the mapping from the numeric values in HackerRank-Developer-Survey-2018-Numeric.csv and what their textual representation in the survey was. Each row represents one of the possible answers to a specific question, with a mapping of the numeric answer in the data file to the textual label in the survey.

<b>Country-Code-Mapping.csv</b>: 
a CSV file that provides the mapping of the numeric country code in our raw data in HackerRank-Developer-Survey-2018-Numeric.csv to the associated country.

<b>HackerRank-Developer-Survey-2018-Numeric.csv</b>: 
a CSV file with the raw survey responses. Each row is one respondent, including an anonymous respondent id, the timestamp of when the survey was started and ended, and the numeric responses to each question. This is the data file that we used for our analysis.


<b>HackerRank-Developer-Survey-2018-Values.csv</b>: 
a CSV file with the text version of the survey responses. Each row is one respondent, including an anonymous respondent id, the timestamp of when the survey was started and ended, and the textual response to each question. This file was derived from HackerRank-Developer-Survey-2018-Numeric.csv using the mapping files that are included in this data set. We provide it for ease of use for those who prefer to work directly with the text values.



## Key Visualization and Insights

### 1. To be Successful -- Male Developers vs Female Developers

![](https://github.com/shuanghao0808/Analysis-on-HackerRank-Developer-Survey-2018/blob/master/Visualization%20Images/11.%20If%20Respondent%20is%20Manager%20by%20Gender.png)

#### Insights:
If you look back to see those pink and blue bar charts (breakdown by gender) in notebook, you might get the idea that there is no big difference between male respondents and female respondents, however, only 19% females became to be managers. By contrast, the proportion of managers for male is more than 33%. It is still very hard to be successful while these female have the same educational background, took to coding when they were young, being at the similar age and doing the same jobs just like guys. Nowadays, all over the world to advocate equality between men and women, and in fact the situation is become better and better, but many people still hold on biased concept in the subconscious.


### 2. What are the Most Important Qualifications Hiring Managers are Looking for?
If the respondents choosed "Yes" in Q16 (Do you interview people as part of your company's hiring process),   they picked three of the most important qualifications they look for in an engineering candidate before the onsite.

![](https://github.com/shuanghao0808/Analysis-on-HackerRank-Developer-Survey-2018/blob/master/Visualization%20Images/12.%20Most%20Important%20Qualifications.png)

![](https://github.com/shuanghao0808/Analysis-on-HackerRank-Developer-Survey-2018/blob/master/Visualization%20Images/9.%20How%20Many%20Respondents%20in%20Top%2010%20Roles.png)

#### Insights:
1. Big Data, Security, Development, Data Science, Cloud and Machine Learning have a huge scope in the future. It is evident that with the increasiing data, we need to save the data, thus we need Cloud, then we need to analyze and build automative systems, for this we need Data Science and Machine Learning and Security for storing the data. Thus candidates developing skills in these domains have a bright future ahead.
2. The picture of Big Data looks good, however, in the question of current roles, the ranking of Data Scientist is 9 and it is the only one made top 10. Why this domain is in high demand but the group of people work on data is not as big as we thought? It is impossible that data positions demand very comprehensive capability for candidates, such as programming languages, statistics, modeling, analytical mind.. Employers are willing to pay them a lot, while not many can be good at all those skills.


### 3.How Well Respondents Like Programming Languages When People Know or Will Learn and When People Already Know?
Programming plays an important role in programming, and people should know how to read and write code written in different programming languages.

![](https://github.com/shuanghao0808/Analysis-on-HackerRank-Developer-Survey-2018/blob/master/Visualization%20Images/13.%20Popularity%20of%20Languages%20that%20People%20Will%20Learn.png)

![](https://github.com/shuanghao0808/Analysis-on-HackerRank-Developer-Survey-2018/blob/master/Visualization%20Images/14.%20Popularity%20of%20Languages%20that%20People%20Already%20Know.png)

#### Insigths:
1. Users of HackerRank like Python best! Is doesn't mean Python has the largest user population, but it is apparently that Python performs better than all the other languages, maximizing coder satisfaction.
2. Put both of above two plots together, I found that the heights of hate bars in the first chart are shorter than those in the second chart. This indicates that people usually feel bad at the very beginning of their coding study or they worry about if they can handle the language, but they feel a lot better when they really master it. 

## Python Jupyter Notebook in nbviewer
http://nbviewer.ipython.org/github/shuanghao0808/Analysis-on-HackerRank-Developer-Survey-2018/blob/master/Analysis/Analysis%20of%20HackerRank%20Developer%20Survey%202018%20-%20Final.ipynb
