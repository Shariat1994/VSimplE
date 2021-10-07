# VSimplE
visual Simple Embedding network for visual relation detection,  2019, tensorflow


# Installation

1. Install ipython, if you do not have ipython, you can install this tool (strongly recommended: https://ipython.org/install.html)
```bash
pip install ipython
```


2. Install TensorFlow v1.3.0
```bash
pip install tensorflow-gpu==1.3.0
```



3. Install easydict
```bash
pip install easydict
```



# Training and Testing
## 1. Download dataset (VRD dataset is used as example)
a). Download the dataset form https://share.weiyun.com/55KK78Y, and the file is named as 'sg_dataset.zip'. 

b). Use the following commend to unzip the downloaded data:
```bash
unzip sg_dataset.zip -d sg_dataset
```

c).In the path where you put vtranse folder, use the following commend to make a new folder 'dataset/VRD':
```bash
mkdir -p ~/dataset/VRD/json_dataset
mkdir -p ~/dataset/VRD/sg_dataset
```

d). Move the files in sg_dataset into the created dataset, by using the following commends:
```bash
mv sg_dataset/annotations_test.json dataset/VRD/json_dataset
mv sg_dataset/annotations_train.json dataset/VRD/json_dataset
mv sg_dataset/sg_test_images dataset/VRD/sg_dataset
mv sg_dataset/sg_train_images dataset/VRD/sg_dataset
```

uplod code on google colab and run from 1 to end
