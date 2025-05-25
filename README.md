# Face Detection using Haar Cascade Classifier

## 📌 Project Description

This project demonstrates face detection using OpenCV’s Haar Cascade Classifier. It showcases how to detect faces in:

* Single-person images
* Group images with multiple faces
* Video files (frame-by-frame detection)

Face detection is performed using pre-trained Haar cascade models provided by OpenCV.


## 🎯 Objectives

* Load and display images and videos.
* Detect and draw bounding boxes around faces.
* Experiment with parameters like `scaleFactor`, `minNeighbors`, and `minSize` to observe detection sensitivity.
* Apply detection both on static images and on video frame streams.


## 📁 Dataset and Resources

* **Images Used**: `Girl.jpg`, `GroupPhoto.jpg`
* **Video Used**: `Video.mp4`
* **Model Used**: `haarcascade_frontalface_default.xml` from OpenCV's pretrained Haar cascades.



## 🛠 Features

* Face detection on different types of images.
* Adjustable detection parameters.
* Real-time video face detection using a frame-by-frame approach.
* Visual output using `matplotlib` for better integration in Jupyter or Colab.


## 🧪 Experiments

The detection is tested with different configurations:

* Changing `minSize` to detect smaller faces in group photos.
* Adjusting `scaleFactor` and `minNeighbors` to tune sensitivity.
* Visualizing how detection performance changes with each parameter tweak.


## 🖼 Output

* Bounding boxes are drawn around detected faces in both images and video frames.
* Each processed image/frame is displayed using `matplotlib`.

---

## ✅ Requirements

* Python
* OpenCV (`opencv-python-headless`)
* Matplotlib

---

## 📌 Conclusion

This project demonstrates how Haar Cascades can effectively be used for face detection in both static and dynamic content. Parameter tuning is key to achieving optimal results, especially for crowded images or fast-moving video scenes.

---

