# Mask R-CNN for Crater Detection and Segmentation
### - University of Study of Naples Federico II

This is an implementation of a version of [Mask R-CNN](https://arxiv.org/abs/1703.06870)(modified by akTwelve) on Python 3, Keras, and TensorFlow 2 for my master thesis. The model generates bounding boxes and segmentation masks for each instance of craters in the image. It's based on Feature Pyramid Network (FPN) and a ResNet101 backbone.

The repository includes:
* Source code of Mask R-CNN built on FPN and ResNet101.
* Training code for MS COCO
* Pre-trained weights for MS COCO
* Jupyter notebooks to visualize the detection pipeline at every step
* ParallelModel class for multi-GPU training
* Evaluation on MS COCO metrics (AP)
* Example of training on your own dataset

## Relator: Prof. Alfredo Renga
## Author: Roberto Del Prete

## Citation
Use this bibtex to cite this repository:
```
@misc{SirBastiano_maskrcnn_2020,
  title={Mask R-CNN for Crater Detection and Segmentation on Keras and TensorFlow2},
  author={Roberto Del Prete},
  year={2020},
  publisher={Github},
  journal={GitHub repository},
  howpublished={\url{https://github.com/SirBastiano/Mask_RCNN}},
}
```
