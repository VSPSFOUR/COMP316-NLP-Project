# COMP316-NLP-Project
- - - 
## End Result : Combined_Implementation_222003978_COMP316.ipynb
  - This notebook showcases the combination of both of NLP concepts below in action to find medical terms from text and present summarized information about them.
- - - 
## Extractive Summarization Section
#### Extractive Summarization - 222003978 - COMP316.ipynb
  - Holds the Text-Rank algorithm used to extract a summary from original text.
  - All linked cell blocks are collected under a heading.
#### Evaluating Extractive Summarizer.ipynb
  - This notebook is utilised to gather metrics to evaluate the Text-Rank algorithm located in "Extractive Summarization - 222003978 - COMP316.ipynb".
  - These metrics are gathered by comparing a baseline summary to one created by the algorithm. This is done by the "find_similarity" function.
  - All metrics are stored in a CSV file.

- - - 

## Information Extraction Section 
#### NER_Model_222003978_COMP316.ipynb
  - Used to train NER model and save to disk. 
  - Uses MACCROBAT2020 for training data.
#### NER_Model_Evaluation.ipynb
  - Used to gather metrics to emprically evaluate the NER model stored in  "ner_model" folder. 
  - Uses MACCROBAT2018 as testing data.
  - Evaluation data is returned in counts and percentages.
- - - 
## Data Sets
  - "TestSummarizer" holds the data used for the evaluation. 
  - "MACCROBAT2020" : NER model training data.
  - "MACCROBAT2018" : NER model testing data.
