# CS5805 Final Project

#### Corey Huang, Allison Deaton, Ken Lin, Rebecca Yeung

Virginia Tech <br />
CS 5805: Machine Learning <br />
Fall 2024

YOLO implementation for face pixelation

## Instructions (PLEASE READ)

### 1) Importing Data

Download data here: http://shuoyang1213.me/WIDERFACE/

What to download: <br />
&emsp; - WIDER Face Training Images <br />
&emsp; - WIDER Face Validation Images <br />
&emsp; - WIDER Face Testing Images <br />
&emsp; - Face annotations

Data must be formatted and named as such, with 'data' folder in root directory:

data/ <br />
├── WIDER_train/ <br />
&emsp;&emsp;├── 0--Parade/ <br />
&emsp;&emsp;├── 1--Handshaking/ <br />
&emsp;&emsp;├── 2--Demonstration/ <br />
&emsp;&emsp;├── ... <br />
├── WIDER_val/ <br />
&emsp;&emsp;├── 0--Parade/ <br />
&emsp;&emsp;├── 1--Handshaking/ <br />
&emsp;&emsp;├── 2--Demonstration/ <br />
&emsp;&emsp;├── ... <br />
├── WIDER_test/ <br />
&emsp;&emsp;├── 0--Parade/ <br />
&emsp;&emsp;├── 1--Handshaking/ <br />
&emsp;&emsp;├── 2--Demonstration/ <br />
&emsp;&emsp;├── ... <br />
├── wider_face_split/ <br />

### 2) Modify 'data.yaml'

Inside 'data.yaml', change directory of 'path' to your own ABSOLUTE path that leads to where 'data.yaml' is located (will not work otherwise).

### 3) Run 'CS5805 Final Project.ipynb'

Code will create 'runs' folder where results can be viewed. It is recommended to delete this folder before each time you run the project to save storage space.

Data results can be seen in the 'results.csv' file in 'runs/detect/train2' and test images with bounding boxes applied can be found in 'runs/detect/train3'.

It will also create a 'pixelated-images' folder where images are applied with face pixalization.
