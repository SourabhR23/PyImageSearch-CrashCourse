# PyImageSearch CrashCourse

- **Course URL:** <https://www.pyimagesearch.com/free-opencv-computer-vision-deep-learning-crash-course/>


## Course

## Day 1: Face detection with OpenCV and Deep Learning

* **Link:** <https://www.pyimagesearch.com/2018/02/26/face-detection-with-opencv-and-deep-learning/>
* **Folder:** [01_Deep_Learning_Face_Detection](https://github.com/SourabhR23/PyImageSearch-CrashCourse/tree/master/01_Deep_Learning_Face_Detection)

**In this section we'll learn how to apply face detection with OpenCV to single input images, videos, and webcams.**

**Commands used:**

* **Face detection with Images:**
    > *python detect_faces.py --image data/image.jpg --prototext model/deploy.prototxt.txt --model model/res10_300x300_ssd_iter_140000.caffemodel* 
    
    > *python detect_faces.py -i data/sample.jpg -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*

* **Face detection with Video:**
    > *python detect_faces_video.py -v data/1.mp4 -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*

* **Face detection with Webcam:**
    > *python detect_faces_video.py -p model/deploy.prototxt.txt -m model/res10_300x300_ssd_iter_140000.caffemodel*


## Day 2: OpenCV Tutorial

* **Link:** <https://pyimagesearch.com/2018/07/19/opencv-tutorial-a-guide-to-learn-opencv/>
* **Folder:** [02_OpenCV_Tutorial](https://github.com/SourabhR23/PyImageSearch-CrashCourse/tree/master/02_OpenCV_Tutorial)

**Tutorial 1:**
In this we are going to learn, <br> 
- Loading and displaying an image 
- Accessing individual pixels
- Array slicing and cropping
- Resizing images
- Rotating an image
- Smoothing an image
- Drawing on an image <br>

**Tutorial 2:**
Along the way we'll be:
- Learning how to convert images to grayscale with OpenCV
- Performing edge detection
- Thresholding a grayscale image
- Finding, counting, and drawing contours
- Conducting erosion and dilation
- Masking an image

