# Sign-Language-Detection
About this directory
Number of Images Training set: 87 images (will be increased after augmentation) Validation set: 25 images Test set: 13 images

Classes: Yes, No, I Love You, Hello, Thank You

File Types Images: .JPG Labels: .txt files in YOLO format → class_id x_center y_center width height (all normalized 0–1) Configuration: data.yaml → contains dataset paths + class names

Folder Structure dataset_split/images/train/ → Training images dataset_split/images/val/ → Validation images dataset_split/images/test/ → Test images dataset_split/labels/train/ → YOLO label files (train) dataset_split/labels/val/ → YOLO label files (val) dataset_split/labels/test/ → YOLO label files (test) data.yaml → YOLO dataset config file
