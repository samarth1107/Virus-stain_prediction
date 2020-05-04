# Virus-stain_prediction  
In this project test and train data is taken from sequence file and description of sequence:  
Data type: Protein  
Virus Type: A   
Subtype: H1N1   
Date range: from 2000 to present    
Classicical protein: HA   
Variant proteins (SOP): no option selected    
Clade classification: None    
Host: Human     
Geographic grouping: Asia   
Country: India     
Adnvaced option: Remove duplicates sequence   



Techinque used convert sequence into convert into sequence of 3 length array for PCA and then train using PCA on LSTM or using deep learning revert back array to sequence.   

Steps:  
Convert sequence into array of characters 
convert array of character into one-hot encoding  
using this one-hot train a variational autoencoder to do PCA ie to 3 length 
train using this 3 length to revert make prediction model 
