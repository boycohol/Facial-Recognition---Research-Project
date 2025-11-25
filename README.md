# Facial-Recognition---Research-Project
The aim of the project is to propose an ML model and a DL model capable of filling in the
attendance sheet after taking a photo of the classroom.

Employed the pretrain model `YOLOv8` to focus solely on face detection rather than identifying entire objects.

ML approach: Used **Facial landmarks** to extract facial features, then classified the student faces with **SVM**, achieved accuracy $33\%$.

DL approach: Used **Additive Angular Margin Loss** to strengthen intra-class compactness and increasing inter-class separability, with
**ResNet34** as backbone, improved the accuracy $77\%$.

Here is the link of Scientific Article: https://drive.google.com/file/d/1HQyNPI_mggBHq7PiXhqvFCPBhPnEa908/view?usp=sharing