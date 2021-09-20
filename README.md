# Encoding-your-categorical-variables-based-on-the-response-variable-and-correlations

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

A Brief Introduction
=======================
Sometimes in Statistical/Machine Learning problems, we encounter categorical explanatory variables with high cardinality. Let’s say for example that we want to determine if a diet is good or bad, based on what a person eats. In trying to answer this question, we’d construct a response variable containing a sequence of characters good or bad, one for each person; and an explanatory variable for the model would be:

x = c("apple", "tomato", "banana", "apple", "pineapple", "bic mac",
	"banana", "bic mac", "quinoa sans gluten", "pineapple", 
	"avocado", "avocado", "avocado", "avocado!", ...)

