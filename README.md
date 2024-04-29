# Academic-Query-Classification-using-Naive-Bayes
## Description
The task at hand involves the classification of academic queries into multiple predefined categories, which include 'academic_servable', 'academic_non_servable', 'general', 'junk', and 'conversational'. The goal is to assign each query to its most appropriate category accurately. However, it's important to note that the training dataset for this task exhibits class imbalance, which means that some categories may have significantly fewer examples compared to others.

Objective: The goal of this task is to build a machine learning or natural language processing model that can accurately classify academic queries into predefined categories based on their content and intent.
Dataset Description
Files
train.csv - the training set
test.csv - the test set
sample_submission.csv - a sample submission file in the correct format
Columns
unique ID query_text category

unique ID - Unique ID corresponding to the query text
query_text - query text
category - category of the query
Details of the classification classes (categories):
academic_servable: Queries that indicate a clear intent to seek or provide academic services, such as tutoring, research assistance, or course-related help. e.g. 'what is inertia'.
academic_non_servable: Queries related to academic topics but without a clear intent to seek or provide services. These might include general academic discussions or queries about educational concepts. e.g. 'What will come in place of the question mark(?) in the given number series?'.
general: Non-academic queries that cover a wide range of topics unrelated to academics. e.g. 'Could you give me a brief overview of haryana police si'.
junk: Queries that contain irrelevant, nonsensical, or spam content. e.g. 'X-Men: Mutant Academy 2'.
conversational: Queries that are part of a conversation or dialogue and don't necessarily fall into the other categories. e.g. 'ansar me'.

Note

Training Dataset contains a total of 5k query texts and their categories tagged.
Training data has an imbalance.
