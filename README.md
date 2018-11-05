# For the sake of simplicity, I modified the Makefile, Make.config and CMakeLists.txt to match a GCP Ubuntu 16.04 env
I used the following guides: \
https://github.com/keck91/drboxguide/blob/master/README.md \
https://medium.com/@zhanwenchen/install-cuda-and-cudnn-for-tensorflow-gpu-on-ubuntu-79306e4ac04e \
https://github.com/BVLC/caffe/wiki/Ubuntu-16.04-or-15.10-Installation-Guide \
https://github.com/adeelz92/Install-Caffe-on-Ubuntu-16.04-Python-3 \
https://medium.com/@mengjiunchiou/build-opencv-caffe-with-cuda-9-0-on-ubuntu-16-04-b2794a41612d \
After clone this repo 
do
```Shell
sudo apt-get update
sudo apt-get upgrade -y
sudo apt-get install nvidia-384 nvidia-modprobe
```
Reboot the instance
```Shell
cd DRBox
chmod +x ./drbox-setup.sh
./drbox-setup.sh
```
