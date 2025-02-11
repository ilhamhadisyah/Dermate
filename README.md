
![](https://github.com/wahyutirta/Dermate/blob/master/image%20assets/logo%20new.png)

![GitHub contributors](https://img.shields.io/github/contributors/wahyutirta/dermate?color=%2342eff5&style=flat-square) ![GitHub forks](https://img.shields.io/github/forks/wahyutirta/dermate?color=%23000ce8&style=flat-square) ![GitHub issues](https://img.shields.io/github/issues/wahyutirta/dermate?color=%23f229d1&style=flat-square) ![GitHub all releases](https://img.shields.io/github/downloads/wahyutirta/dermate/total?color=%23ff8000&style=flat-square) ![GitHub pull requests](https://img.shields.io/github/issues-pr/wahyutirta/dermate?color=%23ff0000&style=flat-square)

# Table of Contents
1. [Project Description](#project-desc)
2. [Built With](#built-with)
3. [App Prerequisites](#app-prerequisites)
4. [How Others Can Replicate](#how-rep)
5. [How to Install App](#install)
6. [How to Use App](#use)
7. [Contributing](#contributing)
8. [Contact](#contact)
9. [Others](#others)
10. [License](#license)

# Project Description <a name="project-desc"></a>

Front Page           |  Article Page          |  Detection        | Result
:-------------------------:|:-------------------------: |:-------------------------:|:-------------------------:
![](https://github.com/wahyutirta/Dermate/blob/master/image%20assets/Screenshot_2021-06-03-14-35-43-024_com.example.dermate.jpg) | ![](https://github.com/wahyutirta/Dermate/blob/master/image%20assets/Screenshot_2021-06-03-14-36-16-553_com.example.dermate.jpg) | ![](https://github.com/wahyutirta/Dermate/blob/master/image%20assets/Screenshot_2021-06-03-14-36-36-660_com.example.dermate.jpg) | ![](https://github.com/wahyutirta/Dermate/blob/master/image%20assets/Screenshot_2021-06-03-14-36-53-808_com.example.dermate.jpg)



Hi, introduce **Dermate**, an automatic skin diseases diagnostic application using image recognition. This application is specifically intended to detect skin diseases in babies. **Dermate** comes as a solution to solve problems and help the Indonesia government in the healthcare sector. As a healthcare application, we help people to treat diseases without having to go to the hospital directly during this pandemic COVID-19. Parents can simply capture image for their baby skin condition, and our smart AI can easily diagnostic their baby skin diseases. Our application is also supported by articles that are able to provide information to parents about the baby skin, and further treatment to overcome the disease. With **Dermate** we provide easy, fast, and inexpensive prevention of baby skin diagnosis with secure medical privacy.

# Built With <a name="built-with"></a>
- Android Studio [Jetpack MVVM Architecture](https://developer.android.com/jetpack/guide)
- Google Cloud Platform Services [GCP Console](https://console.cloud.google.com/home/dashboard?authuser=1&project=able-decorator-315006)

ML model built with framework and libraries :
- Jupyter Notebook or Google Colab
- python==3.7.10
- tensorflow==2.5.0
- numpy==1.19.5
- scikit-learn==0.22.2
- matplotlib==3.2.2
- splitfolders==0.4.3
- keras==2.5.0
- [MobileNet Model Based Architecture](https://github.com/tensorflow/tensorflow/blob/v2.5.0/tensorflow/python/keras/applications/mobilenet.py#L80-L313)

# App Prerequisites <a name="app-prerequisites"></a>
- Android Version 9+
- Internet Connection

# How Others Can Replicate <a name="how-rep"></a>

Built Model :
- Download our dataset from our [drive](https://drive.google.com/drive/u/1/folders/1MeHLKL6dW3_PePbT34t37k478bGrBjCp)
- Install all framework and libraries that needed
- Run our [model](https://github.com/wahyutirta/Dermate/blob/master/ML%20Model/skin_diseases.ipynb) on your colab
- Download model TFlite and labels.txt

Deployment Model :
- Initialize database
- insert data into the base for feature usage
- Initialize the intrepeter
- Preparing the image input (224x224x3)
- Perform inference
- Obtain map results

Mobile Application Development :
- compileSdkVersion 30
- buildToolsVersion "30.0.3"


# How to Install App <a name="install"></a>
- Download apk from the [latest release](https://github.com/wahyutirta/Dermate/releases)
- Enable install from unknown sources
- Install apk

# How to Use App <a name="use"></a>
- Open app
- Tap the scan button in home page
- Add image
- Start recognize
- See result

# Contributing <a name="contributing"></a>
Pull requests are **welcome**. For major changes, please open an issue first to discuss what you would like to change. Next steps:
1. Fork the project repo on GitHub
2. Clone the project to your local machine
3. Commit changes to your own branch
4. Push your work back up to your fork
5. Submit pull request, so we can review your changes

Note : Please make sure to update tests as appropriate.

# Contact <a name="contact"></a>
- Putu Wahyu Tirta Guna - wahyutirta12345@gmail.com
- Ilham Hadisyah Ramadhan - ilhamhadisyahsmd@gmail.com
- Stenli Tong - stenli.tong@binus.ac.id
- Putu Althea Putri Wiradani - altheaowl@gmail.com
- Ni Putu Yulika Trisna Wijayanti - yulika.wijayanti@gmail.com
- Ni Made Sinta Wahyuni - madesintawahyuni@gmail.com
- Dermate Team - dermate.team@gmail.com

# Others <a name="others"></a>
- Academic Resource Paper :
[MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications](https://arxiv.org/abs/1704.04861)
- Project Link :
[Github Repository](https://github.com/wahyutirta/Dermate)
- Presentation Document :
[[B21-CAP0022] Bangkit Capstone “Dermate” Automatic Skin Diseases Diagnostic Application using Image Recognition](https://docs.google.com/presentation/d/1rb7HWnorYF5MOJFICkOq6rTzQGk18emL71rodVOaLmc/edit?usp=sharing)

# License <a name="license"></a>
Copyright (c) 2021 Sarjana Bangkit
