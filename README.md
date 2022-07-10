# Airplane Detection and Classification Based on YOLO

Wrote a paper accepted by IntellSys 2022 as a co-author.

link: not published yet.

Won the First Place in NCSU’s poster presentation contest.

link: https://gti.ncsu.edu/2020/08/14/virtual-poster-competition/

Abstract
-----------------------------------------
The purpose of our research is to use computer vision algorithms to automatically detect aircraft and their roles and types
in satellite imagery. Our dataset is called Rareplanes, which is a unique open-sources machine learning dataset. We use an object detection model called YOLO to achieve the project. YOLO, which stands for “You Only Look Once”, is a state-of-the-art, real-time object detection system. It is a single network which can easily be optimized end-to-end directly. During the research, we divide the whole research into three stages, which are basic recognition, role classification and type classification. Firstly, we train a YOLOv3 (the 3rd version of YOLO) model to detect airplane in a picture. As a result, the mAP (mean Average Precision) is 0.98 which demon- strates the precision of detection. Secondly, we train the model to detect airplanes and classify their roles which contains transport, private and sport. The mAP of role classification is about 0.961. Thirdly, we train the model to classify which type they belong to. The types can be divided into 54 types such as Boeing 767, Fokker 100 and so on. The mAP is about 0.563. In the future, there are some work we are going to handle. Firstly, we plan to update our YOLOv3 model to improve the mAP of detection and classification of aircraft type. Secondly, in order to improve its practicability when the imagery is noisywe plan to blend the synthetic and real data in different proportions.
