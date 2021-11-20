# YOLO-Object-Detection

YOLO is a state-of-the-art, real-time object detection algorithm. In this notebook, we will apply the YOLO algorithm to detect objects in images.
darknet prints out the objects it detected, its confidence, and how long it took to find them. We didn't compile Darknet with OpenCV so it can't display the detections directly. Instead, it saves them in predictions.png. You can open it to see the detected objects. Since we are using Darknet on the CPU it takes around 6-12 seconds per image. If we use the GPU version it would be much faster.


How to run:

1. Open Jupter Notebook in your browser
2. Open the folder containing this folder
3. Run YOLO.ipynb
4. done!

For detailed explanation you can refer to my blog here: https://towardsdatascience.com/you-only-look-once-yolo-implementing-yolo-in-less-than-30-lines-of-python-code-97fb9835bfd2?source=friends_link&sk=5c7234f716e38c8a7b6625ef20fa7811

This is inspired from CVND Udacity course

LinkedIn: https://www.linkedin.com/in/garima-nishad-9b8385134/

Follow me on Twitter: https://twitter.com/garima__nishad
