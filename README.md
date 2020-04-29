# Cancer-detection
Using Convolutional Neural Networks to distinguish between malignant and benign skin lesions.

This is based on the [following paper in nature](https://www.nature.com/articles/nature21056.epdf?author_access_token=8oxIcYWf5UNrNpHsUHd2StRgN0jAjWel9jnR3ZoTv0NXpMHRAJy8Qn10ys2O4tuPakXos4UhQAFZ750CsBNMMsISFHIKinKDMKjShCpHIlYPYUHhNzkn6pSnOCt0Ftf6) which showed excellent results relative to human dematologist controls. This paper even made the cover of the Nature Journal in which it was published due to the ground-breaking nature of the reserach. 

<div style="text-align:center"><img src="https://pbs.twimg.com/media/C3qJe4qWcAEhPOE.jpg" width="450" height="600" />


## InceptionNet V3 Model
----
The paper makes use of the inception_net (V3) algorithm. So we'll use the pytorch version pretrained on the ImageNet dataset.
This is the structure of the Inception Net Convolutional Neural Network. One of implementations mentioned in the paper was to 
use transfer learning of Inception Net V3 pretrained model. That's what we'll try first

<div style="text-align:center"><img src="https://4.bp.blogspot.com/-TMOLlkJBxms/Vt3HQXpE2cI/AAAAAAAAA8E/7X7XRFOY6Xo/s1600/image03.png" width="900" height="400" />    
    
As you can see this is a **_really deep network_**.
