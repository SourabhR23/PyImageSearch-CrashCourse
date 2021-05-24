# PyImageSearch CrashCourse

- **Course URL:** <https://www.pyimagesearch.com/free-opencv-computer-vision-deep-learning-crash-course/>

## Course

### Day 1: Face detection with OpenCV and Deep Learning

* **Link:** <https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/>
* **Folder:** [01_Deep_Learning_Face_Detection](https://github.com/SourabhR23/PyImageSearch-CrashCourse/tree/master/01_Deep_Learning_Face_Detection)

**Commands used:**

* **Face detection with Images:**

    > *python detect_faces.py --image data/image.jpg --prototext model/deploy.prototxt.txt --model model/res10_300x300_ssd_iter_140000.caffemodel*
    
    > *python detect_faces.py -i data/sample.jpg -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*


* **Face detection with Video:**

    > *python detect_faces_video.py -v data/1.mp4 -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*


* **Face detection with Webcam:**

    > *python detect_faces_video.py -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*
