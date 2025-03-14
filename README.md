# Weekly Updates
 ## Week 1
This week I researched the best model to use in order for text classification for suicide risk detection, which seems to be a transformer-based model such as BERT. I need to select a model that doesn’t drain my computer’s resources.\
I also selected the datasets I plan to use, which is suicide_prediction_dataset from HuggingFace for the first model and the IMDB sentiment analysis dataset for later.\

Files: None\

Next week, I plan on researching and starting my implementation of a model.

 ## Week 2

This week I experimented with the BERTSmall model and figured out how to import Hugging Face datasets and convert them to the correct format for usage by a BERT model.\

Files: BERTSmall_test, BERTSmall_test1\

Next week, I plan to focus on training the model.\

## Week 3

This week, I started to train the BERTSmall model but realized it was way too slow for my computer. I decided to switch to something more lightweight like the BERT Mini model, as it’s still computationally strong. I started experimenting with BERT Mini, and I ran into some errors I  have to resolve.\

Files: BERTMini_test\

Next week, I plan to focus on resolving errors and training BERTMini_test\

## Week 4

This week, I trained the BERTMini model. This going my single-task learning model, as I have to shift over to the multi-task approach next. I still have to run tests on it to make sure it works as expected.\

Files: BERTMini_test1, BERTMini\

Next week, I plan to run tests on the BERTMini model and determine how well it performs.\

## Week 5

This week, I tested the model. The model does really well on the original test dataset, so I decided to produce a synthetic dataset with new messages to see how well it does on new data. Performance dropped significantly, suggesting the model is overfitting.\

Files: BERTMiniTesting\

Next week, I’m going to start training the multi-task approach using the sentiment analysis dataset.\

## Week 6

This week, I trained the multi-task approach using the sentiment analysis dataset. It doesn’t perform as expected. In fact, there is no improvement in val loss and model does not perform well on any tests.\

Files: MTL_BERT_test, MTL_BERT_test1\

Next week, I want to figure out what’s going wrong and try training it again just to make sure I didn’t do anything wrong.\

## Week 7

This week, I continued experimenting with multi-task model to understand why it’s not training right but didn’t find a solution. When I start training, it says the loss is NaN which means something might be going wrong in the model configuration.\

Files: MTL_BERT_test2, MTL_BERT_test3\

Next week, I have to train the model again and see if the val loss remains similar to the previous version or if it improves.\

## Week 8

There was something going wrong in a line of code I had written, so I was able to remove it and train the model. The model trained better this time, although loss was still volatile. However it did trend downward which is a good sign.\

Files: MTL_BERT\

Next week, I will test the model similarly to the previous model and start looking to how to implement the most effective model into the iCare Carebot.\

## Week 9

I tested the MTL model, and turns out it generalizes better than the STL model which is a good sign. the iCare project has been incredibly difficult to get up and running. I didn’t know there was a Wiki with explicit directions, so I had been trying to open a previous version of iCare. Finally, after learning about the Wiki and making some adjustments, I got the current version to work.\

Files: MTL_BERT (Updated)\

Next week, I have to wrap everything up. I have to implement the MTL model functionality into the Carebot and finish all other requirements for the Capstone presentation.\

## Week 10

I fell sick over the weekend, so I was unable to work on the project. However, over the course of the week, I got the MTL model to run on the Carebot and also made a poster, presentation slides, and abstract for the presentation. I held a colloquium rehearsal on Friday, March 14th at 11 AM.\

Files: None (made file changes in Carebot)\

Next week, I have to prepare for the colloquium presentation.
