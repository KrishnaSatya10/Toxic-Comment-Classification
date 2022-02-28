# Toxic-Comment-Classification
This folder contains 3 components:  

1. jigsaw-toxic-comment-classification-challenge : A folder which has a single folder inside it that hosts the training data.
  
2. big.txt : This is Project Gutenberg's book data corpus which is used in spelling correction task. The word probabilties are calculated in reference to this text file to determine most probable word for replacement, that is within 2 edit distances of misspelled words. 

3. NLP_Project : A single self-contained code file which has all the processes mentioned in the paper. Comments have been provided and mark-downs explains the process-flow, design decisions, parameter selections etc. All the plots and graphs have been saved.   To run the file, please import all three files in this folder to a single directory. Please ensure that the directory name is changed to your personal colab location where you imported these files.  The code approximately takes 14 minutes to run in Google Colab GPU session setting (3 epochs which roughly take 3 minutes each,and pip installations, final predictions, word cloud creations take up additional few minutes. 
