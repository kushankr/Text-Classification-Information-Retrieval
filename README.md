Text Classification using Machine Learning
---------------------------------------------
#### Problem Description

"This is an exercise of text classification, through the platform of an [online data science competition](
https://inclass.kaggle.com/c/umich-si650-forum-message-classification).

Every document (i.e., a line in the data file) is a real question posted to Yahoo! answers. Your goal is to classify
the topic of each question into ONE of the following categories:
- Specific disease
- Specific treatment
- Family support
- Socializing
- Pregnancy
- Goal oriented
- Demographic-specific

The training data contains 9,826 questions, already labeled with one of the above categories. The test data contain
4,174 questions that are unlabeled. The submission should be a .csv (comma separated free text) file with a header
line ”Id,Category” followed by exactly 4,174 lines. In each line, there should be exactly two integers, separated by a
comma. The first integer is the line ID of a test question (1-4,174), and the second integer is the category your classifier
predicts one of (1,2,4,5,7,8,9). Note that the class labels are NOT continuous."
