# Ball tracking in a Volleyball environment 🏐

## Introduction

This repository contains the code, the final report and the presentation for project of the course "Signal, Image &amp; Video" - MSc in Artificial Intelligence Systems - University of Trento. 

The aim of the project is to achieve the ball tracking in a volleyball scenario without the use of state of the art deep learning architectures.

The project is developed by [@lorenzialessandro](https://github.com/lorenzialessandro) and [@LuCazzola](https://github.com/LuCazzola).

<br>
## Installation and usage 

Clone the folder through ``git`` or download (and extract) the ``.zip`` file. Then follow these steps: 

1. Install the requirements
````
pip install -r requirements.txt
````
2. Start the notebook server
````
jupyter notebook
````
3. Open the notebook project file
````
jupyter notebook notebook.ipynb
````
4. Follow the file steps in order to run the notebook python code

If you want to execute the notebook from your terminal use the ``execute`` subcommand:
````
jupyter execute notebook.ipynb
````

In addition to the code, in the folder there is the [presentation](https://github.com/lorenzialessandro/volleyball-BallTracking/blob/main/presentation.pdf) of the project and the summary [report](https://github.com/lorenzialessandro/volleyball-BallTracking/blob/main/report.pdf).

<br>
## YOLOv5 comparison

A Yolov5 object detector has been trained on the same task and dataset. To see it's perfermances :

1. Download locally Yolov5 repo and requrements
````
git clone https://github.com/ultralytics/yolov5  # clone
cd yolov5
pip install -r requirements.txt  # install
````
2. Run detection
````
python3 detect.py --weights ../YOLOv5_weights.pt --view-img --conf-thres 0.5  --source ../videos/vid3-cut.mp4
````


