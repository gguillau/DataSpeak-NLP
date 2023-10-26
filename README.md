# DataSpeak-NLP

## Overview

In this task, you will be helping DataSpeak to make a proof-of-concept model. The task is to train a machine learning model that can automatically generate answers to written questions a user inputs. For this purpose, you will train a model with Questions and Answers using the Python Questions from Stack Overflow dataset. 

The input to your model would be the written questions (in English), the model should produce the top answers along with a measure of certainty of it being the correct answer (i.e. confidence interval in percentage). Once you have trained an accurate model, you can think about making an application for a user interface where the user can input the question in a text box and the Top 5 (five) answers appear (along with the measure of confidence).  Refer to the figure below.

Keep in mind this is a Natural Language Processing (NLP/ Machine Learning for texts) task.  You will need to do preprocessing of the text before you train your model. Please refer to the ML for Texts Sprint and Workshop materials to make sure you accomplish this correctly.

### Data Description

Link to the dataset: https://www.kaggle.com/datasets/stackoverflow/pythonquestions

Full text of all questions and answers from Stack Overflow that are tagged with the python tag. Useful for natural language processing and community analysis. See also the dataset of R questions.


This dataset is organized as three tables:

 - Questions contains the title, body, creation date, score, and owner ID for each Python questions
 - Answers contains the body, creation date, score, and owner ID for each of the answers to these questions. The ParentId column links back to the Questions table.
- Tags contains the tags on each question besides the Python tag.


Questions may be deleted by the user who posted them. They can also be closed by community vote, if the question is deemed off-topic for instance. Such questions are not included in this dataset.

The dataset contains questions all questions asked between August 2, 2008 and Ocotober 19, 2016.



### Work process

Throughout the project, Externship team and company representatives will be working with you, guiding and helping you through the process. We are going to have common weekly meetings with a mentor to share results and plan the upcoming week and you also may ask a mentor for a private one.

