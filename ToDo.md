To Do List:

Run data both as Avg 5 and as a PRTG (for user's full response of 5 words and explanations)  on GPT5o-mini (do 3 runs each time) ; done 6.9.26

put both code and results in github

Run data both as Avg 5 and as a PRTG (for user's full response of 5 words and explanations)  on Gemini-Flash (do 3 runs each time)
Update the documentation on GitHub


SURF RQ1) Can ensembles of cost-efficient LLMs produce high quality numerical sentiment analysis, along with high quality explanations?

keep track of costs: input and output tokens; $; time to run; dates of runs; model number of LLM

make the following spreadsheet (tabs): 
for Carma PRTG with columns for:
gold standard, ID #, answer from gpt5.4mini  (average of 3 runs), confidence value (3H,2H1M), gemini 3.1 flash-lite  (average of 3 runs), confidence value, avg of 2 LLMS; gemini 3.5 flash and its confidence

make a spreadsheet for Carma Avg 5 with columns for:
gold standard, ID #, answer from gpt5.4mini (average of 3 runs), gemini 3.1 flash-lite  (average of 3 runs), avg of lower cost 2 LLMS; gemini 3.5 flash and its confidence

make a spreadsheet for ZORQ PRTG with columns for:
gold standard, ID #, answer from gpt5.4mini  (average of 3 runs), gemini 3.1 flash-lite  (average of 3 runs),avg of 2 LLMS; gemini 3.5 flash and its confidence

make a spreadsheet for ZORQ Avg 5 with columns for:
gold standard, ID #, answer from gpt5.4mini (average of 3 runs), gemini 3.1 flash-lite  (average of 3 runs), avg of 2 LLMS; gemini 3.5 flash and its confidence


columns that Sherri will add - Mean Absolute Diffierence, Mean squared Difference between gold standard and each tool, StDev, Pierson Coefficient, t-score; average  

---
extract the samples based records that do not have consistent high confidence - focus - 

play with using output from one, as input into another - perhaps having focus on the records that it did not have high confidence



SURF RQ 5) How much data do cost-efficient LLMs need to still maintain a high level of accuracy? (later?)

Multipolarity
*Inner PRTG SD – is this larger for items with multipolarity; is accuracy impacted by multipolarity  - think approaches to experiment
*MAE and MSE – how far off – is it off farther for items that have multipolarity

SURF RQ4) Are there certain situations where human inspection is more critical, such as when LLMs express low or even medium confidence in the evaluation? MAE is high; multipolarity

Make the SAUX user interface
SURF RQ6) What are key features needed in an automated tools for broad user-base with integrated confidence-based reviews?


Later:
Study Explanable AI:
   
  SURF RQ2) How well do various explainable AI (xAI) techniques perform for LLM-generated quantitative sentiment analysis applied to qualitative un-rated product reviews?
SURF RQ3) How well do the various xAI techniques perform as a formal evaluation of explanation quality and its role in user trust and targeted reviews, particularly in mixed ambiguous sentiment cases, as applied to qualitative un-rated product reviews?
 
Using this as a starting point: https://www.datacamp.com/tutorial/explainable-ai-understanding-and-trusting-machine-learning-models
* SHAP and LIME
* Go through steven’s RAG class 
*TextBlob
*TF-IDF: TF-IDF (Term Frequency–Inverse Document Frequency) feature extraction process. This technique transforms textual airline review data into numerical representations by measuring the importance of each term relative to its frequency in individual reviews and across the entire corpus

