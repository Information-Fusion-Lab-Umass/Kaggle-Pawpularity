# pawpularity
Hybrid CNN on Pawpularity Kaggle Contest

Kaggle contest [link](https://www.kaggle.com/c/petfinder-pawpularity-score) 

Attempt to use the shortfused hybrid conv layer to improve a baseline VGG model with multi-modal inputs

### Notes:
After setting the correct data directory, run `main.py` using a TitanX gpu on gypsum - this works without error.

For the competition, the performance is not very satisfactory, with a public score of `rmse = 22.7` on the baseline. Possible reaons include 
 - the outdated VGG model
 - high memory complexity for more structured covariates to be used
 - training from scratch on a dataset that's not large enough might not be better than transfer learning.