All file available at link 
https://drive.google.com/drive/folders/1nGe6umANoqar3DZWGkftu1YDN2sm1QWi?usp=sharing


INPUT

Fasta files
US_aligned_sequence.fasta - USA dataset
India_aligned_sequence.fasta - India dataset

India_metadata.tsv - India metadata
USA_metadata.csv - USA metadata

decoder, encoder - model to reduce dimension

output.vcf - contains position of SNPs


model1_checkpoint.h5  
model2_checkpoint.h5  
model3_checkpoint.h5 - LSTM models


OUPUT

ARIMA.txt - result using only ARIMA model
ARIMA_SNP.txt - result using ARIMA and SNP position
Neural.txt - result using only Neural network
Neural_SNP.txt - result using Neural and SNP position



TO RUN FILE
Flu_Sequence_Detector.ipynb - Python notebook should be loaded on jupyter 
but recommed on google colab as it contain all the library before so no 
need to import it also you can use GPU power to get result faster.
You need the following steps to run program 
 1. ALL the input file should be loaded and colab runtime should be run.
 2. Change the names of file according to dataset that you want to predict 
	For USA
		fasta file -> US_aligned_sequence.fasta 
		metadata file -> USA_metadata.csv
	For India
		fasta file -> India_aligned_sequence.fasta 
		metadata file -> India_metadata.tsv
 3. Decoder, encoder and LSTM model is for USA data if your are using indian 
	data then you should make we make to make it again, code is included in the main python file
 4. There are some cell are specific for USA and India so run accordingly 