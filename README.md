# Fine-Tune BERT to Classify Text Data in MATLAB®


## Getting started

This example shows how to fine-tune a pretrained BERT model for performing text classification. 


## Overview

In this example, you modify a pretrained BERT model for text classification. First, add new layers for classification. Then, retrain the model to fine-tune it, using the original parameters as a starting point. It includes three steps:
1.	Preprocess text data and initialize BERT model
2.	Set up and train the network
3.	Test the model

This example shows the steps for fine-tuning BERT in detail. An alternative approach for document classification using BERT is to use [trainBERTDocumentClassifier](https://www.mathworks.com/help/textanalytics/ref/trainbertdocumentclassifier.html) function.

## Setup
Clone the repository into a local directory. Open the example script "FineTuning_BERT_for_Classification.mlx".

The example requires data to run. To download the data: : 
- Go to https://www.mathworks.com/help/textanalytics/ug/create-simple-text-model-for-classification.html. 
- Click on the button "Copy Command" on the top right of the page and paste it in MATLAB Command Window. This will open the example in the directory where the CSV file is stored. 
- Copy the CSV file from the example, and paste it in the cloned repository.
- If the file is saved in a different location, change the code to point to the file.

## Required Products
- MATLAB (R2024a or later) 
- Text Analytics Toolbox&trade; (R2024a or later)
- Deep Learning Toolbox&trade; (R2024a or later)

## Contact
Sohini Sarkar, ssarkar@mathworks.com

## License
The license is available in license.txt file in this GitHub repository.

## Community Support
[MATLAB Central](https://www.mathworks.com/matlabcentral)


Copyright 2024, The MathWorks, Inc.
