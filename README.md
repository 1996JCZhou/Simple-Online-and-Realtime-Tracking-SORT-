# Simple Online and Realtime Tracker (SORT)

This is an unofficial Python implementation of [Simple Online and Realtime Tracking](https://arxiv.org/abs/1602.00763). The official Python implementation is [here](https://github.com/abewley/sort).

Welcome to my GitHub project, where I focus on the challenging task of Multiple Object Tracking (MOT). In MOT, my primary objective is to analyze an image sequence and identify moving objects, assigning consistent and accurate IDs to these objects across different frames. The objects can vary widely, from pedestrians and vehicles to various animals, with pedestrian tracking being a prominent area of research due to its commercial significance and practical applications. My repository meticulously implements the crucial aspects of the official Simple Online and Realtime Tracker (SORT) algorithm, striving to replicate its functionality with great attention to detail. 

As of now, this project is a work in progress and requires further refinement. I am in the process of selecting a video dataset that contains multiple moving objects. To aid in the tracking process, I rely on a reliable target detection tool, which provides bounding box positions and sizes for each moving object in every frame of the video. Additionally, I am exploring various Matching algorithm solutions to associate object detections across frames effectively. Two promising options under consideration are The Hungarian algorithm and The Max Weight Matching algorithm.

My mission is to create a robust and efficient Multiple Object Tracking system that can handle a diverse range of scenarios. By combining cutting-edge algorithms and techniques, I aim to contribute to the advancement of MOT research and practical applications.

## Requirements
- python
- networkx
- opencv-python
- scipy

## Results
![image](https://github.com/1996JCZhou/Multiple-Objects-Tracking/blob/master/data/Snap_Shot.PNG)

Welcome to see my videos in my Youtube channel for this project.
https://www.youtube.com/watch?v=TjlJh2Vyx04 and
https://www.youtube.com/watch?v=GMeyCBeQo3A
