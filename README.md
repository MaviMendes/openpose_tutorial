# openpose_tutorial
Code based on an open pose tutorial: https://www.youtube.com/watch?v=9jQGsUidKHs

**First**, install opencv and matplotlib if you don't have them installed \
On Ubuntu: pip3 install opencv-contrib-python
pip3 install matplotlib

**Second**, on your terminal, go to the directory where the programs are stored and run them.\
For Python3: python3 video_analyse.py \
python3 webcam_analyse.py\

***Atention***: In the program "video_analyse.py", you must pass the correct name of the video file on this line:\
cap = cv.VideoCapture('woman_running.mp4')

**Obs:**: The is also a Jupyter Notebook code, similar to the separated codes, copied from the tutorial  \
**Obs 2:** graph_opt.pb is from the repo -> https://github.com/quanhua92/human-pose-estimation-opencv
It is responsible for recognizing the body parts and was built using TensorFlow \
**More info about openpose:**\
A 2019 guide to Human Pose Estimation with Deep Learning: https://nanonets.com/blog/human-pose-estimation-2d-guide/#deeppose\
Guide to OpenPose for Real-time Human Pose Estimation: https://analyticsindiamag.com/guide-to-openpose-for-real-time-human-pose-estimation/\
OpenPose : Human Pose Estimation Method: https://www.geeksforgeeks.org/openpose-human-pose-estimation-method/\

