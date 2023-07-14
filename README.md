# Document_Image_Hypersegmentation
此项目是参加百度网盘AI大赛----文档图像超分。最终获得第8名 获得三等奖

背景：大家平时在使用手机进行拍照、扫描的时候，往往会需要将图片放大的场景，可是分辨率放大，图片中的元素都变得模糊起来，进而难以使用。本次比赛希望选手们通过算法等知识技术，帮助人们将因为放大而模糊的图片复原，提高图片分辨率，实现文档图像的“无损放大”，让其重新发挥作用。

分析：、参考文献：SwinIR: Image Restoration Using Swin Transformer（SwinIR）、本项目基于Swin IR模型进行训练。

训练策略： 采用  128×128的图像块进行训练。

模型结构如下所示：

![image](https://github.com/AliaXueting/Document_Image_Hypersegmentation/assets/96671351/70af5099-f434-4c0f-b758-dc1890a19a4d)
