# Cancer-detection
Using Convolutional Neural Networks to design an algorithm that can visually diagnose melanoma, the deadliest form of skin cancer. In particular, the algorithm will distinguish this malignant skin tumor from two types of benign lesions (nevi and seborrheic keratoses).

This project is based on the [following paper in nature](https://www.nature.com/articles/nature21056.epdf?author_access_token=8oxIcYWf5UNrNpHsUHd2StRgN0jAjWel9jnR3ZoTv0NXpMHRAJy8Qn10ys2O4tuPakXos4UhQAFZ750CsBNMMsISFHIKinKDMKjShCpHIlYPYUHhNzkn6pSnOCt0Ftf6) which showed excellent results relative to human dematologist controls. This paper even made the cover of the Nature Journal in which it was published due to the ground-breaking nature of the reserach. 

<div style="text-align:center"><img src="https://pbs.twimg.com/media/C3qJe4qWcAEhPOE.jpg" width="450" height="600" />


## InceptionNet V3 Model
----
The paper makes use of the inception_net (V3) algorithm so I have used the same architecture to train the network 
This is the structure of the Inception Net Convolutional Neural Network. One of implementations mentioned in the paper was to 
use transfer learning of Inception Net V3 pretrained model. However, retraining the network from scrathed proved to me a more successful strategy. 

<div style="text-align:center"><img src="https://4.bp.blogspot.com/-TMOLlkJBxms/Vt3HQXpE2cI/AAAAAAAAA8E/7X7XRFOY6Xo/s1600/image03.png" width="400" height="900" />    
    
## ResNet 50 Model
----
I also trained a ResNet50 model which also showed good performance. Transfer learning proved to be less useful. Training all the parameters from scratch proved to be more
useful. 
<div style="text-align:center"><img src="https://i.stack.imgur.com/XTo6Q.png" width="900" height="400" />   
    
## VGG-16 Model
----
A VGG-16 model was trained for 10 epochs. However it proved to take too long and quickly over-fitted to the problem. 
<div style="text-align:center"><img src="https://cdn.analyticsvidhya.com/wp-content/uploads/2017/08/08131808/temp7.png" width="900" height="600" />



