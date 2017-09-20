Vagrant box with OpenCV, Face-Recognition and Python3 bindings for Visitor Stats
==============================

##Refer Visitor Stats based on computer vision
https://github.com/bikashsharmabks/visitor-stats-computer-vision

```
sudo usermod -a -G vboxusers $(whoami)
git clone https://github.com/bikashsharmabks/opencv-vagrant.git

cd opencv-vagrant
vagrant up

vagrant ssh

workon cv
git clone https://github.com/bikashsharmabks/visitor-stats-computer-vision.git

cd visitor-stats-computer-vision
python start.py
```
