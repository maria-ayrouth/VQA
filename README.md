
# Visual Question Answering VQA 

## What is VQA?
A VQA system takes an image and a free-form natural language question about the image as input (e.g. “Is the boy jumping?”), and produces a natural language answer as its output (e.g. “yes”). Unlike image captioning, answering questions requires the ability to identify specific details in the image .

The data that we're going to work with are from the [visualqa dataset](https://visualqa.org/index.html),a collection of images , questions and annotations . These datasets require an understanding of vision, language and commonsense knowledge to answer.

in this Notebook , We address the problem of answering binary questions about abstract scences.


## What this Notebook  cover :
* Getting a dataset to work with
* Visualizing data
* Prepare inputs(images + questions) for model:
* Build VQA model
* Improve through experiments and evaluate the model
* Make some predictions

## VQA model Architechure :

A high-level view about the VQA model :
![Screenshot (806)](https://user-images.githubusercontent.com/90212538/193788669-b5b80e2e-4854-41c8-a0f4-83bbd69b7d98.png)


## Conclusion
As a result, we got an accuracy of 91% after we go through a lot of experiment. This value represent the performance of the trained model on VQA training dataset.
![Screenshot (807)](https://user-images.githubusercontent.com/90212538/193789130-5b89dbbb-3154-48ae-88ec-f7d466c0d2ff.png)


A few examples of predicted answers from the "Yes/No” validation subcategory are shown below:
![download (20)](https://user-images.githubusercontent.com/90212538/193789507-9fb55d7f-a584-4784-bd2e-a48d5404c5a2.png)

