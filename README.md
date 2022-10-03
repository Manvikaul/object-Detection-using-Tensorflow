# Tensorflow Gesture Detection Model

This project includes a gesture detection model build by using Tensorflow Object Detection API. <br>
It accurately identifies 4 gestures: Thank you, live long, thumbs up and thumbs down. <br>
LabelImg library used for labelling input images https://github.com/heartexlabs/labelImg. <br>
ssd_mobilenet_v2_fpnlite_320x320 model from from tensorflow model zoo used for training. <br>
The project can identify gestures in real time through the system webcam. <br>
<br>
<br>
MODEL LOSS: <br>
![image](https://user-images.githubusercontent.com/47503962/193424572-bc3aee4f-3a45-4047-8c03-ad579395091b.png)
<br>
<br>
MODEL LEARNING RATE: <br>
![image](https://user-images.githubusercontent.com/47503962/193424733-f52d9fc5-e76f-409a-af19-bd24e68e232d.png)
<br>
<br>
MODEL EVALUATION: <br>
[LHS: Model Accuracy RHS: Test Data] <br>
<br>
![thankYou](https://user-images.githubusercontent.com/47503962/193424915-c5a0d201-3309-41b2-a45b-d793e29c6412.png)
<br>
![liveLong_pt](https://user-images.githubusercontent.com/47503962/193425479-69d7cf64-fe1e-48ef-9c79-3ff2531102bf.png)
<br>
![thumbsUp_pt](https://user-images.githubusercontent.com/47503962/193425461-08bf01f6-6db6-4126-9af5-08418a99bc0d.png)
<br>
![thumbsDown](https://user-images.githubusercontent.com/47503962/193424969-7e74121b-e2ab-45da-8772-b5d0406e0c79.png)
<br>
