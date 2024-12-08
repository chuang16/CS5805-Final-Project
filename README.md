# CS5805 Final Project

#### Corey Huang, Allison Deaton, Ken Lin, Rebecca Yeung

Virginia Tech <br />
CS 5805: Machine Learning <br />
Fall 2024

YOLO implementation for face pixelation

## Instructions (PLEASE READ)

### 1) Importing Data

Download data here: http://shuoyang1213.me/WIDERFACE/

&emsp;WIDER Face Training Images <br />
&emsp;WIDER Face Validation Images <br />
&emsp;WIDER Face Testing Images <br />
&emsp;Face annotations

Data must be formatted and named as such, with 'data' folder in root directory:

data/ <br />
├── WIDER_train/ <br />
&emsp;├── 0--Parade/ <br />
&emsp;├── 1--Handshaking/ <br />
&emsp;├── 2--Demonstration/ <br />
&emsp;├── ... <br />
├── WIDER_val/ <br />
&emsp;├── 0--Parade/ <br />
&emsp;├── 1--Handshaking/ <br />
&emsp;├── 2--Demonstration/ <br />
&emsp;├── ... <br />
├── WIDER_test/ <br />
&emsp;├── 0--Parade/ <br />
&emsp;├── 1--Handshaking/ <br />
&emsp;├── 2--Demonstration/ <br />
&emsp;├── ... <br />
├── wider_face_split/ <br />

### 2) Modify 'data.yaml'

Inside 'data.yaml', change directory of 'path' to your own ABSOLUTE path (will not work otherwise).

### 3) Run 'CS5805 Final Project.ipynb'

Code will create 'runs' folder where results can be viewed. It is recommended to delete this folder before each time you run the project to save storage space.

It will also create a 'pixelated-images' folder where images are applied with face pixalization.
