# Mask R-CNN for Instance segmentation using colab
This is a notebook that trains, tests and deploys the [Mask R-CNN](https://arxiv.org/abs/1703.06870) model all on google Colab using Tensorflow and FastAPI

The notebook is split into 9 parts:

1. Cloning the [Mask R-CNN repository](https://github.com/matterport/Mask_RCNN) to get the model and check depencies and GPU given <sub>(you usually get a Tesla K80, but if you restart runtime multiple times you can get a Tesla T4) </sub>

2. Setiing up the config file

3. Pre-processing the Dataset

4. Training the model & Analyzing the metrics with the help of tensorboard (Loss, mAP, ...)

5. Testing the model on pictures you can upload 

6. Background removal option

7. Deploy the model using FastAPI

Enjoy !
