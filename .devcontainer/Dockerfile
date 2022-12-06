# create the docker container, you can change the share memory size if you have more.
FROM nvcr.io/nvidia/pytorch:21.08-py3 AS base

# apt install required packages
RUN apt update
RUN apt install -y zip htop screen libgl1-mesa-glx

# pip install required packages
RUN pip install seaborn thop


