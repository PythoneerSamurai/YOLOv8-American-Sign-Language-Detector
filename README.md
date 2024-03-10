
# ASL Object Detector

An Object Detection Model trained in YOLOv8, that detects American Sign Language alphabets into 26 main categories:

['A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']


## Installation

You can either clone my repository by running the following command in your terminal (remember to open the terminal in the folder you want this project in)

```bash
 git clone https://github.com/PythoneerSamurai/American-Sign-Language-Alphabets-Object-Detector.git
```

![App Screenshot](https://github.com/PythoneerSamurai/YOLOv8-American-Sign-Language-Detector/assets/112153865/6db95127-a824-4c24-8535-33e0acedcd96)


Otherwise, you can just download this project in the form of a ZIP file, by clicking the 'green code button' and then clicking the 'download ZIP' button.

![App Screenshot](https://github.com/PythoneerSamurai/YOLOv8-American-Sign-Language-Detector/assets/112153865/9edc06fa-d16e-4064-b093-2d713dc94a52)

    
## Usage

The usage of the model is fairly simple, you need to have python installed. In addition to that you need a python library called 'ultralytics', you can install it by running the following command in your terminal

```javascript
pip install ultralytics
```

Afterwards, just open the 'main.py' file in the IDE or text editor of your choice, and specifiy the absolute path to the model file (a portion of the path is already written in the main.py file, so that you don't get confused)

![App Screenshot](https://github.com/PythoneerSamurai/YOLOv8-American-Sign-Language-Detector/assets/112153865/f7599ea3-0e8a-4f4f-bba2-0befcd066ae6)

Then you need to specify the source, it can be any one of the options available in the list of inference sources on the following website:

https://docs.ultralytics.com/modes/predict/#inference-sources

Also, you can choose the inference source to be you webcam, source=0


## Acknowledgements

 - [Dataset from Roboflow Universe]([https://universe.roboflow.com/reza-ohnxn/dental2-ztmiq/dataset/3](https://universe.roboflow.com/david-lee-d0rhs/american-sign-language-letters/dataset/6))
 - [Website for making nice GitHub readme files](https://readme.so/)


## License

No License.

