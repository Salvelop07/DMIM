## DMIM (DICOM 3D Medical Image Modeling)

The DICOM 3D Medical Image Modeling (DMIM) project enhances patient care by transforming traditional 2D MRI, PET, and CT scan slices into comprehensive 3D models, making it easier for doctors and technicians to visualize and analyze medical images. 🩻✨

&nbsp;
## Installation

This tutorial uses Conda and PIP. Please make sure to install them before you  proceed the next steps.

1. Create virtual environment with the following instruction:

```
$ conda create -n DMIM python=3.5.4
```
“DMIM” is the name of the new environment. Please make sure to install    	Python 3.5.4, and not other version.

2.  Activate the new DMIM environment by typing:
```
$ conda activate DMIM
```
3. Clone the repository: 
```
$ git clone https://github.com/Salvelop07/DMIM.git
```
4.  Install MongoDB:
```
$ conda install mongodb
```
5. Enter the repository folder, and install the requirements:
```
$ pip install -r requirements.txt
```
6. Open new terminal window and start MongoDB:
```
$ mongod
```
7. Finally, run the website from the repository main folder:
```
$ FLASK_APP=app.py FLASK_DEBUG=1 python -m flask run
```
8. The website should be available at http://localhost:5000/

A successful installation will result in the following index page: 

<kbd>![Home Page](https://github.com/Salvelop07/DMIM/blob/master/static/wiki/4.jpg)</kbd>
&nbsp;&nbsp;

## More images from the app

#### Store and analyze various cases
<kbd>![Store and analyze various cases](https://github.com/Salvelop07/DMIM/blob/master/static/wiki/5.jpg)</kbd>
&nbsp;

#### 3D Analysis
<kbd>![3D Analysis](https://github.com/Salvelop07/DMIM/blob/master/static/wiki/8.jpg)</kbd>
&nbsp;

#### Slice Analysis
<kbd>![Slice Analysis](https://github.com/Salvelop07/DMIM/blob/master/static/wiki/10.jpg)</kbd>
&nbsp;

#### Draw on slices
<kbd>![Draw on slices](https://github.com/Salvelop07/DMIM/blob/master/static/wiki/11.jpg)</kbd>
&nbsp;&nbsp;


## References

The X ToolKit:
https://github.com/xtk/X

AMI: 
https://github.com/FNNDSC/ami
