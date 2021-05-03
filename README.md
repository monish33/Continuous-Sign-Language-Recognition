<h1 align="center">
  Continuous-Sign-Language-Recognition
</h1>

<p align="center">
  <a href="https://www.python.org"><img src="https://img.shields.io/badge/language-python-blue.svg?style=flat"></a>
 
</p>


## Introduction
This is an AI model using the Machine Learning, Image Processing which involved repeatedly gesturing in front of a camera to teach the system the fundamentals of sign language. This is to combat the differences between various Country’s sign languages and their regional dialects without compromising on accuracy while giving way to crowd-sourcing.


## Intermediate Outputs
The outputs below were taken directly from our model.
#### RAW Feed (1920x1080 @ 60 fps)
<img src="https://github.com/monish33/Continuous-Sign-Language-Recognition/blob/main/docs/gifs/raw_ns.gif" width="360"/><img src="https://github.com/monish33/Continuous-Sign-Language-Recognition/blob/main/docs/gifs/raw_smith.gif" width="360"/>

#### Extraction of skin tones (Removal of unwanted entities)
<img src="https://github.com/monish33/Continuous-Sign-Language-Recognition/blob/main/docs/gifs/skin_ns.gif" width="360"/><img src="https://github.com/monish33/Continuous-Sign-Language-Recognition/blob/main/docs/gifs/skin_smith.gif" width="360"/>

#### Canny Edge Detection to extract only perimeter of change
<img src="https://github.com/monish33/Continuous-Sign-Language-Recognition/blob/main/docs/gifs/edges_ns.gif" width="360"/><img src="https://github.com/monish33/Continuous-Sign-Language-Recognition/blob/main/docs/gifs/edges_smith.gif" width="360"/>


## Getting Started
### Prerequisites
Things you need to run the program:
- Python Compiler (3.7 Recommended)
- A clone of this repository :P
- **Easy Way:** Install all the necessary packages form pypi by using the following command:
  ```bash
  pip install -r requirement.txt
  ```
- If you still prefer the old fashioned way, then use the following commands:
    ```bash
    pip install opencv-python
    pip install matplotlib
    pip install numpy
    pip install tqdm
    ```



<p align="center">
  Done by <a href="https://github.com/monish33">Monish Murale</a>
</p>


