
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
As a result, we got an accuracy of 80% after we go through a lot of experiment. This value represent the performance of the trained model on VQA training dataset.

![Screenshot (814)](https://user-images.githubusercontent.com/90212538/194493877-1abe34a0-3ec8-43f7-af88-52cbe082a405.png)



A few examples of predicted answers from the "Yes/No” validation subcategory are shown below:
![Screenshot (815)](https://user-images.githubusercontent.com/90212538/194493819-c71871c9-4c38-4dcc-a9c3-01b867ed421e.png)


By looking at this figure, our VQA model output a predicted value of 0 or 1 which mean “no” or “yes” respectively. If we check the first, second and third scene, our model predict correctly, but for the fourth scene, we find that the predicted output mismatch with the correct answer which is “no”. Our model predict around 50% correctly on validation dataset.
