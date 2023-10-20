## Road Damage Detection and Classification using Deep Learning
1. An application that helps in identifying different types of road damages by taking images as input.
2. Detects two categories of damages: cracks and potholes (and ravels).
3. Trained YOLO, Faster RCNN and SSD models for the purpose.
4. Used streamlit to build a webapp that takes images as inputs and identifies damages in the images.

### Flowchart
![image](https://github.com/AkashKhatrii/react-chat/assets/65164913/768122b7-726c-4b8a-9115-cb9228b4716c)

#### Data Collection and Labelling
1. Used RDD2022 dataset which had images from 5 different countries. <a href="https://figshare.com/articles/dataset/RDD2022_-_The_multi-national_Road_Damage_Dataset_released_through_CRDDC_2022/21431547">Link</a>
2. Not all images were used, manually selected images which were good from the dataset.
3. Labelled the images in the format needed by all the models. eg. YOLO needs .txt files for the labels and FRCNN and SSD needs xml files.

### Flowchart of Web App
![image](https://github.com/AkashKhatrii/react-chat/assets/65164913/f3189f13-5b6d-44fc-9b07-2eb291faecac)

#### Graphical User Interface
![image](https://github.com/AkashKhatrii/react-chat/assets/65164913/9c395c05-2a77-47bd-a065-dbe20a0ab438)
![image](https://github.com/AkashKhatrii/react-chat/assets/65164913/f7ad49ad-de3b-44a3-a0f3-3107d2ffffc1)
![image](https://github.com/AkashKhatrii/react-chat/assets/65164913/cfb2a906-9217-47a6-a53e-d8d1cf67a2b7)

### Predictions
![image](https://github.com/AkashKhatrii/react-chat/assets/65164913/3e6131c7-0989-4ee5-8f27-20fbecc14cb1)

![image](https://github.com/AkashKhatrii/react-chat/assets/65164913/7c1ea843-428e-48f0-a7f5-3fb7334121a7)


