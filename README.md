# SpaceTargetDetector
Code repo for Space Inspection For CubeSats and Other Space Targets using Object Detection in images. The repo includes:
- SpaceTargetRenderer: A Blender pipeline to generate synthetic data for training
- yolov7: An object detection module modified to train for space target detection task. Also modified for domain adaptation with unlabelled data. yolov7 used in the cubesat_DA branch. 

![alt-text](https://github.com/BatmanofZuhandArrgh/SpaceTargetDetector/blob/main/demo.gif)

**Datasets**\
In this research, both real and synthetic images were used. For real train and test set, introducing the first public image dataset of CubeSats and Space Targets in space (as of 2022), collected from the NASA, JASA, and ESA's website and youtube channel, and labelled with bounding boxes in yolov1 format. Blender generated images were also used for training and testing. Unlabelled images were also collected for domain adaptation.
- [Real dataset](https://mailuc-my.sharepoint.com/:u:/g/personal/kim3dn_ucmail_uc_edu/EfLARE6IQeJPm8qDYljCcCABd0AaqbTedxHxT0f-2MsVbQ?e=OySZE6)
- [Synthetic RS2000 dataset](https://mailuc-my.sharepoint.com/:u:/g/personal/kim3dn_ucmail_uc_edu/EXvRBkXG3r9Kqcj3LjGBXRsBTQHsx8Wx3EP9ppTKvybEuQ?e=EwKL9f)
- [Others (as mentioned in the paper)](https://mailuc-my.sharepoint.com/:f:/g/personal/kim3dn_ucmail_uc_edu/Eut4qyeg8q1OrtJ9QQpZMt4BljlAlihAEyS3uI9e_s-pGA?e=fgBUwG)

For more details about the collection and labelling process, please see *Dataset Preparation* in the paper.

For [paper](https://github.com/BatmanofZuhandArrgh/SpaceTargetDetector/blob/main/SpaceInspection_paper.pdf), [presentation](https://github.com/BatmanofZuhandArrgh/SpaceTargetDetector/blob/main/SpaceInspection_presentation.pptx), [conference recording](https://youtu.be/jCugRKsp0P0) and [demo video](https://youtu.be/9Um3asCXYww).

For fun progress pics throughout the Blender pipeline development, check out [these images](https://mailuc-my.sharepoint.com/:f:/g/personal/kim3dn_ucmail_uc_edu/EiIf4U2r4HFOl5BoS2s-JGEBBa833oUDO4cE9xXxWbHdkQ?e=ROrYTi)


*A.Q. Nguyen and D. Kim, "Space Inspection For CubeSats And Other Space Targets Using Object Detection In Images," 33rd AAS/AIAA Space Flight Mechanics Meeting, Austin, Texas, Jan. 15-19, 2023.*