FROM continuumio/anaconda3

RUN conda install keras
RUN conda create -n tensorflow
RUN conda install -c conda-forge jupyter_contrib_nbextensions


RUN mkdir /code

WORKDIR /code
