# caffe-bvlc
Dockerfile for docker image containing the latest version of Caffe offered on the repo of BVLC.

Inspired by tleyden5iwx/caffe-gpu-master : https://hub.docker.com/r/tleyden5iwx/caffe-gpu-master

Run me with proper parameters:
nvidia-docker run -i -t --device=/dev/nvidia0:/dev/nvidia0 --device=/dev/nvidiactl:/dev/nvidiactl matthieudelaro/caffe-bvlc

Your devices may change depending on your hardware. Use those returned by:
ls /dev | grep nvidia
