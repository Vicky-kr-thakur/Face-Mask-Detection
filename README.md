<h1 align="center">Face Mask Detection</h1>

  <h4 align="center">Face Mask Detection System built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams. This project aims at differentiating between those who wear a mask and not wear a mask.</h4>
</div>
<p align="center"><img src="https://user-images.githubusercontent.com/64346030/163553258-f0917f86-986d-4c3d-8b6d-00fca56954ee.png"></p>


## TechStack/framework used

- [OpenCV](https://opencv.org/)
- [Caffe-based face detector](https://caffe.berkeleyvision.org/)
- [Keras](https://keras.io/)
- [TensorFlow](https://www.tensorflow.org/)
- [MobileNetV2](https://arxiv.org/abs/1801.04381)

## :file_folder: Dataset
This dataset consists of __4095 images__ belonging to two classes:
*	__with_mask: 2165 images__
*	__without_mask: 1930 images__

## Working

To detect face masks in an image type the following command in the terminal: 
```
python detect_mask_image.py --image images/pic1.jpeg
```
To detect face masks in real-time video streams type the following command in the terminal:
```
python detect_mask_video.py 
```
## Images

<p align="center">
  <img src="https://github.com/pranjay-poddar/Face-Mask-Detection/blob/main/images/img1.png">
</p>

<p align="center">
  <img src="https://github.com/pranjay-poddar/Face-Mask-Detection/blob/main/images/img2.png">
</p>

## References
* [https://github.com/chandrikadeb7/Face-Mask-Detection)
* [https://www.pyimagesearch.com/](https://www.pyimagesearch.com/)
* [https://www.tensorflow.org/tutorials/images/transfer_learning](https://www.tensorflow.org/tutorials/images/transfer_learning)
* https://ieeexplore.ieee.org/document/9342585
