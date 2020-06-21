# Green-App

These are the dependencies:
Tensorflow-gpu==1.15
opencv==3.*
PIL
numpy>=1.16.0



The project is based on the open-sourced tensorflow model for object detection which can be found
in this link https://github.com/tensorflow/models/tree/master/research/object_detection

The greenpet.rar has the files for the Application on androidstudio.

Here is an example on how our model generates stickers for flowers:
![helloword4](https://user-images.githubusercontent.com/47258547/85229344-0e784d00-b3e1-11ea-8bdf-9c23fc169a19.jpg)

It is recommended to try this on a conda environment.

custom_image_detector.py is where you can put an image path and it will detect all the trees, plants, flowers there.
custom_image_detector_webcam.py is where you provide your video link and it will iterate through different frames and do the same steps
in custom_image_detector.py
vis_stickers.py is where the real editing on the image happens. It was taken from the open-sourced tensorflow utils and made many changes in order to have stickers not rectangles surrounding the plant.

