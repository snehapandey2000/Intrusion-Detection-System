# Intrusion Detection System using Machine Learning Algorithms

## Problem Description
An Intrusion Detection System (IDS) is a security mechanism designed to identify and respond to security threats in computer networks or systems. The main goal of an IDS is to detect and alert the user or system administrator of any suspicious activity or behavior on the network.
The project aims to study the accuracy and efficiency of intrusion detection by applying various machine learning algorithms to identify malicious traffic. The project is focused on two tasks- classifying malicious traffic and benign traffic, and classifying different malicious traffic based on attack types.

## Dataset
The data used to train the classifier is taken from the [CSE-CIC-IDS2018](https://www.unb.ca/cic/datasets/ids-2018.html) dataset provided by the Canadian Institute for Cybersecurity. It was created by capturing all network traffic during ten days of operation inside a controlled network environment on AWS where realistic background traffic and different attack scenarios were conducted.
As a result the dataset contains both benign network traffic as well as captures of the most common network attacks.
The dataset is comprised of the raw network captures in pcap format as well as csv files created by using [CICFlowMeter-V3](https://www.unb.ca/cic/research/applications.html#CICFlowMeter) containing 80 statistical features of the individual network flows combined with their corresponding labels.
A network flow is defined as an aggregation of interrelated network packets identified by the following properties:
* Source IP
* Destination IP
* Source port
* Destination port
* Protocol

The dataset contains approximately 16 million individual network flows and covers the following attack scenarios:
* Brute Force
* DoS
* DDos
* Heartbleed
* Web Attack
* Infiltration
* Botnet

## Classifiers
The project implements and studies the results of Naive Bayes Classifier, Random Forest Classifier, Decision Tree Classifier and Logistic Regression Classifier.

## Execution
The code files can be easily exceuted on Google Colab by signing with a gmail id. 

To run in local mode:

Download the dataset and .ipynb files. Change the datatset path in the files and run all cells.

