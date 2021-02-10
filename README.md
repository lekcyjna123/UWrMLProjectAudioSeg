# Audio Segmentation
> Audio segmentation of radio transmissions.

## Table of contents
* [General info](#general-info)
* [Technologies](#technologies)
* [Libraries](#Libraries)
* [Results](#Results)
* [Status](#status)
* [Inspiration](#inspiration)

## General info
Our project aims to develop efficient algorithm that performs accurate audio recordings segmentations into two classes (music, speech) collected from radio station.

Our project comprises of two approaches: Supervised and unsupervised where after preprocessing we look how well work algorithms shown during lectures.

## Technologies
* Python - version 3.7.3

## Libraries
* faiss
* pomegranate
* librosa
* numpy
* seaborn
* sklearn

## Results
### Supervised Learning
Random Forest - 96.96% - After Smoothing - 99.58%
KNN - 92.91% - After Smoothing 94.23%
### Unsupervised Learning
Kmeans - 80.17% - After Smoothing - 80.05%
Kmeans Faiss - 80.31% -  After Smoothing - 80.03%

## Status
Project is: _finished_,

## Inspiration
Machine Learning class.

## Authors
Created by [@Sahcim](https://github.com/Sahcim), [@wojciechwojnar](https://github.com/wojciechwojnar), [@jakubmichalo](https://github.com/jakubmichalo) and [@lekcyjna123](https://github.com/lekcyjna123)
