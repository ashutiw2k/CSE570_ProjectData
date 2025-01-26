# About
This repository contains the datasets, raw and otherwise used in our (Ashutosh Tiwari, Aditya Patwardhan) CSE 570 Wireless Systems and Networking [Course Project](https://github.com/ashutiw2k/CSE570_Project) at Stony Brook University. 
This course was taught by Professor [Shubham Jain](https://www3.cs.stonybrook.edu/~jain/). The course website (if online) can be found [here](https://crimson-brick-4f5.notion.site/CSE-570-Wireless-and-Mobile-Networks-Fall-2024-ad7f025689be4ccfb75e98513b1833c8). 

# Data
The data is contained in the Zip Files. The content is as follows. 
1. AllRawImage.zip - All the raw image (png) captured for scene0 in the ViFit dataset.
2. RanAll.zip - The synchronised data from a project that uses the ViFit data (referenced below)
3. RAN4model_dfv4p4.zip - The synchronised data from a project that uses the ViFit data (referenced below) that was used to train a specific model.
4. SingleTestSceneData_UnSynced.zip - As the name suggests, the unsynchronised camera and sensor data from a singular data collection iteration. 
5. ResultsData.zip - A zip file containing all the data our project generated (i.e. annotated images, combined sensor readings, etc.)

# Citations and References
1. Our project was inspired by the following paper: \\
Zhang, Haichao, et al. "OOSTraj: Out-of-Sight Trajectory Prediction With Vision-Positioning Denoising." Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition. 2024. [pdf](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhang_OOSTraj_Out-of-Sight_Trajectory_Prediction_With_Vision-Positioning_Denoising_CVPR_2024_paper.pdf)
1. The raw Vifit datasets were acquired from the [ViFit webpage](https://sites.google.com/winlab.rutgers.edu/vi-fidataset).  
2. The cleaned, timestamp synchronised datasets (image and sensor) were acquired from [another project using the ViFit dataset](https://github.com/bryanbocao/vitag/blob/main/DATA.md) (thanks [Bryan Bo Cao](https://bryanbocao.github.io/)!!)