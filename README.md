# kaldi-docker

CPU-based images and GPU-based images for Kaldi-asr. 

## Building images

Command to build the imange:

>> docker build -f Dockerfile.cpu -t kaldi/cpu:latest .

Command to run the container:

>> docker run -d -p 1989:1989 --name kaldicpu --ipc=host  kaldi/cpu:latest

## Using pre-built images

> docker pull laleye/kaldi_cpu

Command to run:

> docker run -d -p 1989:1989 --name kaldicpu --ipc=host  laleye/kaldi_cpu:latest
