# eyegaze

So this project was mainly done by me. Jabed Miah( **jmiah@fordham.edu**) was responsible for random forest experiments.

**Considerations**
One important thing to consider is that there was a concensus of methodology between the ViT, CNN, RNN models, with same training test split, and inputs. However, the random forest had a different training and test split and added a new feature that wasn't apart of the original experiment. Future work involves fixing this so we can more accurately compare RF and these other deep learning models. Either by:
1. Adopting the inputs of Random Forest to the deep learning models
2. Configuring Random Forest similar to the deep learning models.

Of course this is not the only future work that can be accomplished, see gaze.ipynb's section of future work for a quick rundown.

The code also provided only showcases CNN, ViT, and RNN. I tried to make it pretty detailed. Also consider that there was alot of repeated code, something that I should have done was include more functions instead of repeating lots of code segments. 
