# MAEF-Net
Multi-attention efficient feature fusion network for left ventricular segmentation and quantitative analysis in two-dimensional echocardiography
### Please note that：
I'm sorry, the article was published at the time of the COVID-19 (the school was closed before graduation and failed to return). After graduation, the server was mistakenly cleared the account, so all codes were lost. If you encounter problems with the specific experiments and steps in the article, please feel free to contact. I will try to update the work on GitHub again when I have time later.
1. Reproduction of heart segmentation section, please refer to（ https://echonet.github.io ）The code, our work also fully draws on the code framework of the website for implementation. If you are in a hurry, you can try this first, and if you encounter any problems, you can contact me;
2. It is easy to find the end diastolic/systolic phase and EF calculation using scripts. If you encounter any problems, please feel free to contact us at any time;
3. The number of validation and testing sets in this work is slightly different from the "Echo" dataset. Please refer to the introduction in the article for details;
4. The external test set for this work cannot be made public temporarily due to its involvement in patient privacy.

* This repository provides the code for ["Multi-attention efficient feature fusion network for left ventricular segmentation and quantitative analysis in two-dimensional echocardiography"]. 
* Our work now was Accepted by the Ultrasonics. If you want to cite this article, please use "Yan Zeng#, Po-Hsiang Tsui#, Kunjing Pang, Guangyu Bin, Jiehui Li, Ke Lv, Xining Wu, Shuicai Wu*, and Zhuhuang Zhou*, “MAEF-Net: multi-attention efficient feature fusion network for left ventricular segmentation and quantitative analysis in two-dimensional echocardiography,” Ultrasonics, in press, 2022."

### Requirementss
Some important required packages include:
* tensorflow version >=1.12.0.
* opencv-python >=3.3.0
* pandas >=0.20.1
* python >= 3.6 
* Some basic python packages such as SimpleITK.

## Usages
### Data[data]
[data]:https://echonet.github.io/dynamic/

## Acknowledgement
Part of the code is revised from [EchoNet-Dynamic][Echo].
For more details, see the accompanying paper, Video-based AI for beat-to-beat assessment of cardiac function, David Ouyang, Bryan He, Amirata Ghorbani, Neal Yuan, Joseph Ebinger, Curt P. Langlotz, Paul A. Heidenreich, Robert A. Harrington, David H. Liang, Euan A. Ashley, and James Y. Zou. Nature, March 25, 2020. https://doi.org/10.1038/s41586-020-2145-8
[Echo]:https://github.com/echonet/dynamic

## Contact
* email:799633204@qq.com
* QQ:799633204
