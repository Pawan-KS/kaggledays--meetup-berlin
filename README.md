# kaggledays--meetup-berlin

## About
<b>Title : </b> Open your eyes for the beauty around you
<br>
<b>Aim : </b> To predict a score based on how aesthetically good an image would look to a person.
<br>
[competition link](https://www.kaggle.com/competitions/open-your-eyes-for-the-beauty-around-you/overview)

## Method

We trained Efficientnet-B3 (from [timm](https://github.com/rwightman/pytorch-image-models) library) on the images and used the output of the model's GAP layer + meta data to train Light-GBM. <br>
We ranked 6th in the competition with public LB score: 0.18541

[Train code for Efficientnetb3](b3_training.ipynb)

[Train code for LGBM](lgb_training_b3)

[Inference code](lgb-inf-b3)


</br>


[Weights for Efficientnetb3](https://www.kaggle.com/datasets/darkravager/tf-efficientnet-b3-ns)

[Weights for LGBM](https://www.kaggle.com/datasets/sakshamaggarwal/lgbm-kaggle)




