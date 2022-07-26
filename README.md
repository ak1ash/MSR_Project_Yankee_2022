

## Note
This is a reproduction project as part of the MSR course 2022 at UniKo, CS department, SoftLang Team

### Team name: Yankee
### Student names: 
- Akash Ravishankar
- Neha Nagesh
- Abhishek Harsha Raj

## Objective of reproduction

### Description
Reproduction of issues reported in stackoverflow. The aim was to reproduce the java issues found on Stackoverflow.

### Input Data
Java questions are extracted from Stackoverflow using [StackExchage API](https://api.stackexchange.com/docs/search#fromdate=2020-01-01&todate=2022-07-25&order=desc&sort=activity&tagged=java&filter=default&site=stackoverflow&run=true)

### Output Data
A CSV file which contains the reproducibility status is obtained as output which is used for further analysis where we see the total percentage of questions that are reproducible or irreproducible in the given data. 


## Findings of reproduction

### Process delta:

i) We first extracted the data dump from StackExchange API base as shown in paper, but we had to modify the query in order to obtain the ideal data dump for further processing. 
ii) From the data dump, we were able to reproduce most of the preprocessing steps like selecting only Java based questions.
iii) We weren't able to randomly sample the data as the process was not very well defined. Hence, we decided to go with the top 400 questions out of which we decided to select 150 questions as our sample.



### Output delta:

i) We weren't able to obtain the "No AcceptedAnswers" category due to our data being a small snapshot and was only available with 'AcceptedAnswerIDs'. Hence, in the analysis part we have zero results for this category.


## Implementaion of reproduction

### Hardware requirements:
i) x86 64-bit CPU (Intel/AMD Architechture)
ii) 4GB RAM 
iii) 1 GB free disk space

### Software Requirements:
i) Windows 10 or 11
ii) VS Code Editor
iii) Anaconda Navigator
iv) Eclipse IDE 2021-03 or IntelliJ IDE (Latest Version).
v) Chrome Browser to access Stack Overflow.


### Validation







