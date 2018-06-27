# Analyze-data-set-from-Stack-Exchange-Using-Hive
The data set contains the following attributes:

As part of a recruiting exercise, a major social media company asked candidates to analyze data set from Stack Exchange.
You will be using the data set to arrive at certain key insights.

qid: Unique question id
i: User id of questioner
qs: Score of the question
qt: Time of the question (in epoch time)
tags: a comma-separated list of the tags associated with the question. Examples of tags are ``html'', ``R'', ``mysql'', ``python'', and so on; often between two and six tags are used on each question.
qvc: Number of views of this question (at the time of the datadump)
qac: Number of answers for this question (at the time of the datadump)
aid: Unique answer id
j: User id of answerer
as: Score of the answer
at: Time of the answer (in epoch time)

You need to arrive at the following results:

- Top 10 most commonly used tags in this data set.
- Average time to answer questions.
- Number of questions which got answered within 1 hour.
- Tags of questions which got answered within 1 hour.
