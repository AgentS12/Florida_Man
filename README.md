# Forida_man Generative AI with Falcon_7B
Using fine-tuned LLM's to generate new innovative Florida Man stories.  Falcon is a LLM developed by in the UAE, while it is not great for anwering questions it's ability to reply well allowed for the generation of great LLM's
#Data
Florida_man contains several columns and about 42,000 rows, though we are only interested in the title column
#Cleaning
Data was cleaned in striping_florida_man file, it involves removing rows not containing the word "florida", all columns that were not the title column, and removed all but the first 500 rows due to the cost of generating prompts.
#Generating prompts
Used relevance AI to reverse generate prompts that would create the titles that would create a knowledge base for Falcon-7B.  Link to the reverse prompt: https://app.relevanceai.com/notebook/bcbe5a/97bdcaee3a79-4d67-a5e7-5daba3c22ba0/58f12841-cd02-445e-92c5-b1106f465d3b/use/app

#Running the Model
Copy_Florida_Man_AI is where the code is laid out, I imported Falcon via the huggie face interface into a local notebook for training.  Imported the new data set generated 125 step fine tunning process.  attempts on the generateion were made before and after the training set to see if the data had an effect.  Indeed there was a difference with the new AI learning the Head line format as well as generating unpromted additions to make the headline more convincing.
