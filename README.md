# DETR 
Welcome to our second Computer Vision project.

**Abstract.** In this work, we introduce the panoptic segmentation problem of image, its evaluation metric, and provide the 2020 SOTA Detection Transformer (DETR) as the optimal solution. Then explain explicitly how does DETR performs object detection: the Transformer architecture, the process of extracted image's feature transformation to Transformer's digestible form, the queries for questioning detected object and the loss computation, also the optimization algorithm. In order to deploy panoptic segmentation, the panoptic head is added to notice each detected object and render the segmentation version of image.Finally, we clarify its powerful properties by implement [COCO-2017](https://cocodataset.org/index.htm#download) pretrained model and apply it to [Wheat Head detection problem](https://www.kaggle.com/c/global-wheat-detection).

For the detail of our report, see [Approaching Object detection and Panoptic segmenation problem by DETR](https://github.com/thoconvuive/DETR/blob/main/DETR.pdf)

# Notebooks
+ For the implementation of COCO-2017 pretrained model. We install and demonstrate its performance by plotting the prediction (included visualization of attention mechanism). The work can be found at [Implement pretrained DETR for object detection and panoptic segmentation Colab notebook](https://drive.google.com/file/d/1o__Xh8b2wMNYkwp0m4Rc54iyUp-DBtZv/view?usp=sharing)  

+ We train the pre-trained DETR model to get a prediction of wheat in Wheat Head dataset. This is a really hard problem, our training model have a acceptable result. See [Implement DETR for Wheat detection Colab notebook](https://drive.google.com/file/d/1E8Bua-BaEf5EE-6VNN3hznHlCLnAOLh6/view?usp=sharing) for full detail.
