The ipython notebook is to fine-tune a yolo model using an open-source dataset found on Roboflow for garbage classification purposes.

``data_zip`` can be found at via the Google Drive link https://drive.google.com/file/d/19krKarQzawGQmMHb3HH27aVfI99GeqgE/view?usp=drive_link.

The dataset consists of 15k images of 12 classes:

* battery
* biological
* brown-glass
* cardboard
* clothes
* green-glass
* metal
* paper
* plastic
* shoes
* trash
* white-glass


Each image is associated with a label file. Currently, there is no segmentation on the image. Namely, the label indicates the entire image is of "x" class. Segmentation data can be manually labeled via Roboflow.
