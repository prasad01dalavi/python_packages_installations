# Python Packages Installations
Different methods for installing packages in python

## Python2 (Windows):
 ```bash
 pip install numpy 
 pip install pandas 
 pip install matplotlib 
 pip install drawnow
 pip install sklearn 
 pip install urllib3 
 pip install requests 
 pip install Pillow 
 pip install bs4 
 pip install django 
 pip install django-cors-headers 
 pip install django-rest_framework 
 pip install python-dateutil
 pip install paho-mqtt 
 pip install virtualenv 
 pip install simplejson
 pip install opencv-contrib-python     (Version: 3.4.0)
 pip install scipy
 pip install patsy
 pip install statsmodels
 pip install pep8
 pip install clarifai===2.1.0
 pip install flask
 pip install flask-sqlalchemy
 pip install celery==3.1.0
 pip install sqlalchemy
 pip install gmplot
 pip install xlrd
 pip install pylint
 ```
 
 ## Anaconda2 (Windows):
 ```bash
conda install -c menpo opencv          (Version: 2.4.11)
conda install progressbar

# Tensorflow Installation
conda create -n tensorflow pip python=3.5      # Creates a conda virtualenv with python3 
pip install --ignore-installed --upgrade tensorflow    (Version: 1.7.0)
conda install -c menpo opencv                          (Version: 3.3.1)
# Note: In windows, Tensorflow can only be installed with Python3
```
<hr>


## Python2 (Linux):
 ```bash
sudo pip install tensorflow
sudo apt-get install protobuf-compiler python-pil python-lxmlsudo 
sudo pip install pillow
sudo pip install lxml
sudo pip install matplotlib
protoc object_detection/protos/*.proto --python_out=.
export PYTHONPATH=$PYTHONPATH:`pwd`:`pwd`/slim
sudo pip install opencv-python
sudo apt-get install -y python-dev libmysqlclient-dev && sudo pip install mysqlclient
sudo pip install flask
sudo pip install flask-uploads --upgrade
 ```
## Python3 (Linux):
 ```bash
 sudo pip3 install opencv-python       (Version: 3.4.0)
 sudo pip3 install sklearn
 ```

## Anaconda2 (Linux):
```bash
 # Add conda to python2 path:
export PATH=~/anaconda2/bin:$PATH

conda install -c dhaneshr opencv     (Version: 2.4.11)
conda install progressbar
conda install simplejson
```

## Anaconda3 (Linux)
```bash
# Add conda to python2 path:
export PATH=~/anaconda3/bin:$PATH

# Tensorflow Installation:
conda create -n tensorflow1 pip
source activate tensorflow1
pip install --ignore-installed --upgrade tensorflow-gpu
pip install --ignore-installed --upgrade tensorflow

conda install -c anaconda protobuf
pip install pillow
pip install lxml
pip install jupyter
pip install matplotlib
pip install pandas
pip install opencv-python
```
<hr>


## Python2 (RPi):
```bash
sudo apt-get install python-opencv       (Version 2.4.9)
```

## Python3 (RPi):
```bash
 # Tensorflow
 wget http://ci.tensorflow.org/view/Nightly/job/nightly-pi-python3/39/artifact/output-artifacts/tensorflow-1.4.0-cp34-none-any.whl
 sudo pip3 install ./tensorflow-1.4.0-cp34-none-any.whl       (Version: 1.4.0)
 
 sudo pip3 install matplotlib
 sudo apt-get install python3-cairo
 
 # Opencv3 on Python3
 http://www.life2coding.com/install-opencv-3-4-0-python-3-raspberry-pi-3/
 
 ```
