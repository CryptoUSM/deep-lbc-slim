# DL Cryptanalysis - LBC-IoT & SLIM

This repository contains supporting code for the paper:

> On the Security of Lightweight Block Ciphers against Neural Distinguishers: Observations on LBC-IoT and SLIM

There are 3 seperate folders in this repository:
1) LBC-IoT_Github - contains files used to train the deep learning model as a distinguisher for LBC-IoT
2) SLIM_Github - contains files used to train the deep learning model as a distinguisher for SLIM
3) LBC-IoT-Key-Recovery - contains files to run a key ranking attack on LBC-IoT

Each of the folders contains a Jupyter Notebook which can be used to run the respective programs.

The deep learning model used in this work is taken from Gohr's work and some of the code are adapted from https://github.com/agohr/deep_speck
