# VGG16-Covid-X-ray-Image-Classification


## Dataset 
* Data can also be retrieved by the link inside the code.<br>
* All of data are contained in the data folder, and in this folder it has folder named two for the task1 and folder named all for the task2.<br>
* Both folder two and folder all are separated into training data and test data. <br> 
* Over all folder structure: <br>
|--all<br>
|--------train<br>
|-----------------covid<br>
|-----------------normal<br>
|-----------------pneumonia_bac<br>
|-----------------pneumonia_vir<br>
|--------test<br>
|----------------covid<br>
|----------------normal<br>
|----------------pneumonia_bac<br>
|----------------pneumonia_vir<br>
|--two<br>
|--------train<br>
|-----------------covid<br>
|-----------------normal<br>
|--------test<br>
|-----------------covid<br>
|-----------------normal<br>


## Code
* task1.ipynb processes a VGG16 model for the binary classification by training the data contained in folder two, and set labels for images in the test dataset.
* task2.ipynb also contain a VGG16 model, but it does a classification for four categories.
* At the end of both tasks, there is a classification visualization through T-SNE given the feature from a chosen layer of the previous trained VGG16 model.
