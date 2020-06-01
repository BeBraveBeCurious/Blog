# TensorFlow in Practice Specialization

## Course1: Introduction to TensorFlow for Artificial Intelligence, Machine Learning, and Deep Learning

### W1: Relation between traditional programming and machine learning

![TradationalProgrammingCodeRule](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/ML1Data_Rule_Code.PNG)
![ComputerVisionLearnRule](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/CV_Rules_labelled_data.PNG)
![TraditionalProgramming&ML](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/ML%26TraditionalProgramming.PNG)

#### HelloWorld Code in tf
![HelloWorld_ALayerNN](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/LinearRegressionTF.PNG)
model.predict([10.0])很接近19，但不完全等于，保有一定的不确定性 -> 分类任务很有用

#### howework:审题，样本scale，可以打印输出时*100K
![exCode](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/LinearRegressionTFhomework.PNG)

### W2: Computer Vision: more than Hello World 
FashionMNIST: 7k Image, 28*28Greyscale, 10 categories


#### Load Data from API and split into train and test
![APIloadData](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/APILoadData.png)

#### 3Layers NN
![ThreelayersNN](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/FlattenDenseDense3Layers.PNG)

#### Callbacks设置loss或者accuracy(acc)条件停止training
![Callbackacc](https://github.com/BeBraveBeCurious/Blog/blob/master/TensorflowPractice/Callbackacc0.99.PNG)

- logs.get('acc')>0.99
- 输入像素需标准化： x_train, x_test = x_train / 255.0, x_test / 255.0 
- label为0-10，不需要标准化





