# Day 1: Face detection with OpenCV and Deep Learning

* **Link:** <https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/>

## Preview:
<img src="https://github.com/SourabhR23/PyImageSearch-CrashCourse/blob/master/01_Deep_Learning_Face_Detection/output/output1.png" width="460"><img src="https://github.com/SourabhR23/PyImageSearch-CrashCourse/blob/master/01_Deep_Learning_Face_Detection/output/output2.png" width="447">
<p align="center"><img src="https://github.com/SourabhR23/PyImageSearch-CrashCourse/blob/master/01_Deep_Learning_Face_Detection/output/face_detect_video.gif" width="460">
</p>
  
  ### **Commands used:**

* **Face detection with Images:**

    > *python detect_faces.py --image data/image.jpg --prototext model/deploy.prototxt.txt --model model/res10_300x300_ssd_iter_140000.caffemodel*
    
    > *python detect_faces.py -i data/sample.jpg -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*


* **Face detection with Video:**

    > *python detect_faces_video.py -v data/1.mp4 -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*


* **Face detection with Webcam:**

    > *python detect_faces_video.py -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*
