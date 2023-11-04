# Grammar Checker for English Language
This is an implementation of a grammar checker for the English language in Python from scratch using a corpus comprising paragraphs labeled as either correct or unknown. This includes part-of-speech tagging using the Hidden Markov Model, training and tuning of N-gram language models, model evaluation using Shannon Visualization and perplexity, and other concepts of natural language processing.

Keywords: Natural Language Processing, Hidden Markov Models, N-gram Language Model, Shannon Visualization, Perplexity 
Related Topics: Preprocessing, Parts of Speech, Dependency Parsing, Language Modeling
## Problem Statement
- Part 1: Build a grammar checker using the concepts taught in class, you will be given a corpus with some paragraphs labeled correct and unknown; correct paragraphs have no grammatical errors, while unknown may/may not have sentences which have grammatical errors in them. The task is to find all the sentences that have these errors. For example: “In the country there lived a fox. The quick brown fox jump over the fence. Farmer Shaun was terrified.” In this paragraph, the sentence “The quick brown fox jump over the fence” is grammatically incorrect.
- Part 2: After finding the sentences which have these grammatical errors you have to suggest the correct alternatives. Bonus if your suggestions are also coherent with the context. For example in the previously given paragraph, the sentence: “The quick brown fox jump over the fence” Can be replaced with “The quick brown fox jumped over the fence”, “The quick brown fox jumps over the fence” as well as “The quick brown dog jumped over the fence” however the first two alternatives are correct given the context that it was a fox and not a dog
## Instructions
1. Extract the dataset in the directory `dataset/NLP_Q1`
2. Run `main.ipynb` using jupyter notebook.