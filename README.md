**ANLP 2020/2021**
# Evaluating generated song lyrics

This project is about generating, optimizing and evaluating machine generated rap lyrics. 
We trained two simple algorithms for text generation on Hip-Hop song lyrics from OHHLA.com.
We also trained different classification algorithms to classify song texts as either Hip-Hop or non-Hip-Hop.
Since the quality of the generated text is not very consistent, we came up with the idea to use the probability that is returned of the classification algorithm as a filter for our generated output.
At the end we also conducted short online survey where we asked friends and colleagues to judge our generated output and compare it to human written lyrics and random text.  
Results can be found [here](https://www.umfrageonline.com/results/61d577a-20a491e)

# Directory structure
The data folder contains notebooks that obtain and pre-process data.   
This project uses two datasets:  
The rap lyrics provided on OHHLA.com and an edited data set of lyrics from AZLyrics.com which we obtained [here](https://www.kaggle.com/albertsuarez/azlyrics).  
The lyrics in OHHLA are rap lyrics only. The AZLyrics data set contains rap and non-rap lyrics. 

The generation folder contains three notebooks for the rap lyrics generation.
One using an N-gram Markov Chain approach, one using LSTM, and one providing a method to get the filtered output.

The classification folder contains notebooks that are used to build a classifier which was trained to distinguish rap from non-rap lyrics through the differences in words. The classifier is used to filter the best results in the generation.  

The evaluation folder contains notebooks for the assessment of a human evaluation study and evaluation of the different methods through cosine similarity. 

# Download the full project with resources
https://drive.google.com/drive/folders/1u70ncwXqr5EfsPcwD8DFNA1EFgeTvXz3?usp=sharing


# Access from Google Colab
https://colab.research.google.com/github/AntJulRa/ANLP-project-/
