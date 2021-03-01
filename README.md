# Different approaches for generating rap lyrics.

This project is about generating, optimizing and evaluating machine generated rap lyrics. 

Folder strucutre:

The data folder contains notebooks that obtain and preprocess data.   
This project uses two datasets:  
The rap lyrics provided on OHHLA.com and an edited data set of lyrics from AZLyrics.com which we obtained here: https://www.kaggle.com/albertsuarez/azlyrics.  
The lyrics in OHHLA are rap lyrics only. The AZLyrics data set contains rap and non-rap lyrics. 

The generation folder contains notebooks for the rap lyrics generation.  

We generated lyrics using a two-layer lstm network and a markov chain model.

The classification folder contains notebooks that are used to build a classifier which was trained to distinguish rap from non-rap lyrics through the differences in words. The classifier is used to filter the best results in the generation.  

The evaluation folder contains notebooks for the assesment of a human evaluation study and evaluation of the different methods through cosine similarity. 


# Access from colab
https://colab.research.google.com/github/AntJulRa/ANLP-project-/
