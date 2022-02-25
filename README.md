# VR-EyeTracking
Gaze Prediction in Dynamic $360^\circ$ Immersive Videos (CVPR 2018)

This project hosts the dataset and code for our CVPR 2018 paper.

 - Yanyu Xu, Yanbing Dong, Junru Wu, Zhengzhong Sun, Zhiru Shi, Jingyi Yu, and Shenghua Gao: Gaze Prediction in Dynamic 360◦ Immersive Videos;

This paper explores gaze prediction in dynamic $360^\circ$ immersive videos, \emph{i.e.}, based on the history scan path and VR contents, we predict where a viewer will look at an upcoming time. To tackle this problem, we first present the large-scale eye-tracking in dynamic VR scene dataset. Our dataset contains 208 $360^\circ$ videos captured in dynamic scenes, and each video is viewed by at least 31 subjects. Our analysis shows that gaze prediction depends on its history scan path and image contents. In terms of the image contents, those salient objects easily attract viewers' attention. On the one hand, the saliency is related to both appearance and motion of the objects. Considering that the saliency measured at different scales is different, we propose to compute saliency maps at different spatial scales: the sub-image patch centered at current gaze point, the sub-image corresponding to the Field of View (FoV), and the panorama image. Then we feed both the saliency maps and the corresponding images into a Convolutional Neural Network (CNN) for feature extraction. Meanwhile, we also use a Long-Short-Term-Memory (LSTM) to encode the history scan path. Then we combine the CNN features and LSTM features for gaze displacement prediction between gaze point at a current time and gaze point at an upcoming time. Extensive experiments validate the effectiveness of our method for gaze prediction in dynamic VR scenes.

## EyeTracking Dataset
Download our *Eye Tracking* dataset [[Baidu Pan]](https://pan.baidu.com/s/1_YBi0GY1TQb6n3hJzQBKoQ) code: kdcj 
