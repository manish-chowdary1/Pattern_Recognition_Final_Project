# Pattern_Recognition_Final_Project


<!-- PROJECT LOGO -->
<br />
<p align="center">
  <img src="Downloads\sample_img.jpg" alt="Logo" width="150" height="150">

  <h3 align="center">Deep Learning for Fingerprint Liveliness Detection</h3>
  <p align="center">
    by: Manish Chowdary Ravipati
  </p>
</p>

## University of Florida : [Electrical and Computer Engineering](https://www.ece.ufl.edu/)<br />EEL6825 - Pattern Recognition and Intelligent Systems Fall 2023
Faculty: [Dr. Silva](https://www.ece.ufl.edu/people/faculty/catia-silva/) <br />
Students: [Manish Chowdary ](https://www.linkedin.com/in/manishcr/) <br />



<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#dependencies">Dependencies</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#running">Running</a></li>
      </ul>
    </li>
    <li><a href="#authors">Authors</a></li>
    <li><a href="#acknowledgements">Acknowledgements</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

The data used in this project is a publicly available dataset called the LivDet2015 dataset. It consists of Training(1000-Live, 250-Fake)and Testing(1000-Live, 250-Fake) fingerprint images, which are divided into four categories: live, spoof, unknown, and background. The live category contains images of real, live fingerprints, while the spoof category contains images of fake fingerprints created using various materials such as silicone, gelatin, and play-doh. The unknown category contains images that the organizers of the dataset could not verify as live or spoof, and the background category contains images with no fingerprints.

<!-- GETTING STARTED -->
## Getting Started

### Dependencies
This project was run in the UFRC PyTorch-1.7.1 kernel on HiPerGator.

* NumPy 
* Pandas 
* PIL
* Sklearn 
* Scipy 
* tqdm
* Matplotlib 
* OpenCV 



### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/manish-chowdary1/Pattern_Recognition_Final_Project.git
   ```
2. Setup (and activate) your environment

### Running

**Download the .zip file [here](https://drive.google.com/drive/folders/1pZBJvUDaAFHgfmSeHPimGXPEoxtSFL6Z?usp=sharing).**
After downloading the .zip file and extract it. Then using Bitvise transfer the data to the UFRC HiPerGator. Just run the files in the code folder in this order.
* 1) Data Pre_Processing.ipynb
After running this file check, ```FPLD-ResNet-101-CLS.pth``` without this file we cannnot perform Training and validation.
* 2) Training.ipynb
* 3) Validation.ipynb

augment.py is already performed the file is just for the reference.


**File Descriptions**
* ```augment.py.ipynb```: This file will perform data Augmentation.
* ```Data Pre_Processing.ipynb```: This is the Data Pre-process .
* ```Data Pre_Processing.pdf```: A visual copy of ```Data Pre_Processing.ipynb``` results in pdf form.
* ```FPLD-ResNet-101-CLS.pth```: This is the pre-trained model it contains the weights of a ResNet-101 convolutional neural network .
* ```Training.ipynb```: This is the Training file for the model. 
* ```Training.pdf```: A visual copy of ```Training.ipynb``` results in pdf form.

* ```Validation.ipynb```: This is the file to check the validation.
* ```Validation.pdf```: A visual copy of ```Validation.ipynb``` results in pdf form.
* ```Deep Learning for Fingerprint Liveliness Detection Report.pdf```: A pdf IEEE-format paper covering the project.

<!-- Authors -->
## Authors

* Manish Chowdary Ravipati - ravipatim@ufl.edu

Project Link: [https://github.com/manish-chowdary1/Pattern_Recognition_Final_Project](https://github.com/manish-chowdary1/Pattern_Recognition_Final_Project)


<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements

* [Catia Silva](https://faculty.eng.ufl.edu/catia-silva/)

## Thank you
