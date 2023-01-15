# EDA_SQuAD

For Exploratory data Analysis, I have choosen SQuAD dataset from Hugging face. Stanford Question Answering Dataset (SQuAD) is a reading comprehension dataset, consisting of questions posed by crowdworkers on a set of Wikipedia articles, where the answer to every question is a segment of text, or span, from the corresponding reading passage, or the question might be unanswerable.

Reason: When Financial advisors talk to the customers, they take the notes. In notes, they write about everything they talk about. This include talking about customer's family, hobbies, interests, their financial holding, emplyment, change/event in customer's history, their investment, future planing, resk appetite etc. I have given a project in which I have convert these notes, written in english natural language and to structural data, in tabular form. So, it can used in analysis, ML, reporting etc. Since, this data is quite messy and it varies from advisor to advisor. My current approach involve two NLP models and RegEx. One model for sentence segmentation and another one for text classification. After classification, I have to write up several lines of Regex code to parse the text further. I am looking for an alternate solution. My assumption is Question/Answering model may be better in this use case. As I can just use one model and get much cleaner output. I can control the questions to optimize for the precise output. For this purpose, I am exploring SQuAD dataset, to find out if it will be suitable for my project.

Notebook is well commented to explain my thought process during this Exploratoty data analysis. If you have any question, please don't hesitae to reach out.

Pallavi Srivastava
