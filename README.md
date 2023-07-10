# Multilingual Visual Question Answering (mVQA)
In this project, we built three transformer-based models for multilingual visual question answering (mVQA), which is a challenging multi-modal task requiring answering questions proposed from images in multiple languages. <br>
Work done by [Xinwen Liu](https://github.com/Xinwen-Liu-Wendy), [Joseph Lin](https://github.com/josephhlinn)

## Dataset
We used the dataset for the VLSP 2022 EVJVQA Challenge (https://codalab.lisn.upsaclay.fr/competitions/12274), which contains 23,785 question and answer pairs (QAs) in three languages (English, Japanese, Vietnamese).

## Models
Three transformer-based models were built for this project. The first one is ViT + mT5, the second model is ViTMAE + mT5, and the third model is ViT + mBART. Codes codes for each model are available in the corresponding .ipynb file. We want to compare the performances of different vision models and language models for this multi-modal task.

## Reproduce experiments
All the data loading, preprocessing, model, training and evaluation codes are provided in .ipynb.

## Performance
In our experiments, we found ViT + mBART has the best performance for F1 score (0.3427) while ViTMAE + mT5 has the best performance on BLEU metric (0.2650). Following are the demonstration results of our model (ViT + mBART) in three languages. Q represents question, A represents answer, Pred represents prediction results from the model.
<img src="./Prediction.png" alt="alt text" width="1000" height="220">


