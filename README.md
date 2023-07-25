# Video-Vision-Transformer
Transformer-based models for video classification, drawing upon the recent success of such models in image classification. Our model extracts spatiotemporal tokens from the input video, which are then encoded by a series of transformer layers. In order to handle the long sequences of tokens encountered in video, we propose several, efficient variants of our model which factories the spatial- and temporal-dimensions of the input. Although transformer-based models are known to only be effective when large training datasets are available, we show how we can effectively regularise the model during training and leverage pre trained image models to be able to train on comparatively small datasets. 

# Video-Vision-Transformer Photo
![alt text](https://github.com/google-research/scenic/blob/main/scenic/projects/vivit/data/vivit.png?raw=true)
