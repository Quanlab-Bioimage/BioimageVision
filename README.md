

# Overview
**BioimageVision software transforms large-scale data into pyramid data and visualize the data quickly.**

## Hardware Requirements
**Here, we recommend a computer with the following specs:**
Operating system: windows 10 <br>
1. large-scale data transformation <br>
RAM: 128+ GB <br>
CPU: 8+ cores, over 3.50GHz/core <br>
2. data visualization <br>
Graphics card: 2080Ti <br>
Memory: More than 8GB <br>

## Format requirements for Large-scale data transformation
* 8bit/16bit,uncompression/LZW,Stripe storage<br>
* image size in x/y: less than 50000 x 50000<br>
* image size in z: none<br>

## Software
[Click this link to download BioimageVision.7z](https://github.com/Quanlab-Bioimage/BioimageVision/releases/tag/SoftWare)
## Installation
An installation guide can be found in section 2 of the User guide. <br>
It takes approximately 10s to install the software on a recommended computer.

## User Guide
[User Guide](https://github.com/Quanlab-Bioimage/BioimageVision/blob/master/User%20Guide/BioimageVisionUserguiderV1.0.pdf)
## Demo video
**1. [Large-scale data transformation](https://github.com/Quanlab-Bioimage/BioimageVision/blob/master/Video/Large-scale%20data%20transformation.mp4)**<br>
data information: 8192 x8192 x 1600, 8 bit, LZW.<br>
running time: 245s. (computer configuration: CPU 13th Gen Intel(R) Core(TM) i9-13900K 3.00 GHz,RAM 128 GB) <br>

**2. Visualization**<br>
* [The visualization of large-scale data](https://github.com/Quanlab-Bioimage/BioimageVision/blob/master/Video/the%20visualization%20of%20large-scale%20data.mp4)
* [Visualization of slices from the whole volume data](https://github.com/Quanlab-Bioimage/BioimageVision/blob/master/Video/Visualization%20of%20slices%20from%20the%20whole%20volume%20data%20.mp4)
* [Visualization of a series of small blocks surrounding the traced neurites](https://github.com/Quanlab-Bioimage/BioimageVision/blob/master/Video/visualization%20of%20a%20series%20of%20small%20blocks%20surrounding%20the%20traced%20neurites.mp4)<br>
data information: 8271 x 9016 x 2967, 16 bit, LZW.<br>
The entire visualization is displayed on a recommended computer in real time.<br>


## Note
1. Do not perform other operations on the computer during the Large-scale data transformation.
2. The storage device must support high efficiency and long-term reading.
3. More continuous the storing address of the 2D image sequence, faster the data transformation speed.
4. All paths cannot contain Chinese characters and Spaces.

## Technique Help
quxuzhong@hust.edu.cn
