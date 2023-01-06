# DistilBert-IDs
Saving the Last Hidden States of DistilBert output as numpy array so we can use it later on for any experiment 

i used this refrence from Jay Alammar : https://colab.research.google.com/github/jalammar/jalammar.github.io/blob/master/notebooks/bert/A_Visual_Notebook_to_Using_BERT_for_the_First_Time.ipynb#scrollTo=iaoEvM2evRx1

in this code , i save the output as pickle file so it can be used again for down stream task, this should make it easier and faster 

you can switch between DistilBert and Bert models 

for text classification purpose, if you will use LHS as your input, you will need only to use any machine learning classifier and no need to use transformers 
