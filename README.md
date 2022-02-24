# Pixel-ImageNet
![dataset](https://github.com/shiyinzhang/Pixel-ImageNet/blob/master/ims/ims.jpg "dataset")
<br />
<br />
The subset of the dataset is available. We will release the remaining part of the dataset later. Please stay tuned.
We updated the subset of Pixel-ImageNet. The newly released version has 0.06M more images than before. 
### Introduction
The Pixel-ImageNet contains 1000 classes and 0.615M instance masks of ILSVRCLOC collected using [IOG](https://github.com/shiyinzhang/Inside-Outside-Guidance "IOG"). 
In the Pixel-ImageNet, each image contains only one class and the pixel value in the groundtruth is used to distinguish each instance.

### Download
This is the subset of Pixel-ImageNet, which contains 0.485M images and spans 946 object classes. The detail of the object class and the number of images per class is shown in [label-v2.npy](https://github.com/shiyinzhang/Pixel-ImageNet/tree/master/dataset).
The dataset is available on [Google Drive](https://drive.google.com/file/d/1AxTeOldc-g5vEWCOusI0T8_DsBi9ynG0/view?usp=sharing) and [Baidu Netdisk](https://pan.baidu.com/s/1r0MQrpWwqkS889u5TZaS2w) (pwd: i1u0). This subset is based on the training set of [ImageNet](http://www.image-net.org/download).
The full Pixel-ImageNet dataset will be released later. Please stay tuned. 



### Citations
Please consider citing our dataset in your publications if it helps your research. The following is a BibTeX reference.

    @inproceedings{zhang2020interactive,
      title={Interactive Object Segmentation With Inside-Outside Guidance},
      author={Zhang, Shiyin and Liew, Jun Hao and Wei, Yunchao and Wei, Shikui and Zhao, Yao},
      booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
      pages={12234--12244},
      year={2020}
    }
