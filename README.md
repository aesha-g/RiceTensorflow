# RiceTensorflow


[image1]: (pure.jpg "Pure"){:height="300px" width="300px"}
[image2]: partial.jpg "Partial Impure"
[image3]: impure.jpg "Impure"


## Project Overview

Welcome to the Tensorflow Object detection! In this project, Custom Tensorflow Model can be used within mobile app to process real-time Rice Paddy's Classification using own Dataset. .  

![Pure][image1]

Rice Paddy is a final stage of carrying out actual rice from coating. In contrast to conventional agriculture, it is difficult to check the quality of rice using rice paddy.Tensorflow overcomes problems of accurate classification. While this enables the efficient way of classification in three different categories as Pure, partial Impure and Impure.

## Project Instructions

### Instructions

1. Clone the repository and navigate to the .
```	
git clone https://github.com/tensorflow/models
cd models/research/object_detection/
git clone https://github.com/RiceTensorflow/

```

2. Download the Labeled [RicePaddy dataset](https://drive.google.com/file/d/14CWHnRow9xrbSzymdp_4SRMmkkVYh42E/view?usp=sharing).  Unzip the folder and place it in the repo, at location `path/to/above path`. 

3. Download the [tfrecord files](https://drive.google.com/file/d/1h983ucaQsDkUS7xwK-4lECJQvqq6dERR/view?usp=sharing).  Unzip the folder and place it in the repo, at location `models/research/object_detection/legacy/data`.

4. Start training by using Google's Tensorflow

5. After successful training you will get  [frozen_inference_graph.pb](https://drive.google.com/file/d/14D97NS9JClEhoMAkG9XfCJg4z5qkZ6h-/view?usp=sharing).

6. open jupyter notebook from `models/research/object_detection/`

7. open object_detection_tutorial.ipynb and add path of newrice(folder name). 
	
8. Gather results from test_image folder

9. You can also use this [APK_file](https://drive.google.com/file/d/1MKp6oq1Pei2c5psQapBzrNDpfOD_kUKD/view?usp=sharing). for the same or you can test model using webcam with  [Jupyter notebook](https://drive.google.com/file/d/1hvd41X2VNtmLrWolAzBQC0XHBR960TDq/view?usp=sharing).



