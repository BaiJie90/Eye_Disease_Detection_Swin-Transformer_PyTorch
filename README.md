# Eye Disease Detection using Swin-Transformer PyTorch README

## General Description

This repository contains an AI model that does image classification on images on the eye to detect if an eye has any diseases and labels them accordingly. This repository came to life in accordance to the subject AI Convergence and Application that is held on [Handong Global University (HGU)](https://www.handong.edu/eng/).

## Setup

### Required packages/libraries

The full list of requirements and their version number can be found in the `requirements.txt` file.

Execute the following command to install all the required dependencies.

```
pip install -r requirements.txt
```

**DISCLAIMER**

The packages/libraries listed in the text document contains all the packages that have been installed in the used Python environment.  
Furthermore the used packages/libraries might be of an older version or are not supported/maintained in the future.

### Data setup
To get starting with training the model, please download the dataset (link in the citations chapter), or use your own dataset.

To properly setup, create a folder named `data` in the root folder and place your data in there. The images have to be separated by class by putting them in there respective folder (see example below).

```bash
Eye_Disease_Detection_Swin-Transformer_PyTorch
  ├── data
  │   ├── class1
  │   │   ├── imagefile
  │   ├── class2
  │   │   ├── imagefile
  │   ├── class3
  │   └── etc.
  │
  ├── .gitignore
  ├── Eye_Disease_Detection.ipynb
  ├── README.md
  └── requirement.txt
```

## General Information

### File Structure

#### Eye_Disease_Detection.ipynb

Here you can find the "main" program to run/train the AI model.

#### requirements.txt

Here you can find all the needed packages/dependencies that were installed using the Python environment. The list also contains some packages/dependencies that were not needed to run this Jupyter Notebook.

## More Information & Citations

For more information about the subject Swin Transformer visit the following websites:

- https://arxiv.org/abs/2103.14030
- https://github.com/microsoft/Swin-Transformer

### Authors of this project

- [Bai Jie Cao](https://github.com/BaiJie90)
- [Maxine Olexa Phoa](https://github.com/mn4p)
- [Omole Olakunle A.](https://github.com/omole18)

### Citations

#### Source for the code:

- [Flower Classification Swin Transformer Pytorch | Kaggle](https://www.kaggle.com/code/hamedghorbani/flower-classification-swin-transformer-pytorch/notebook)

#### Source for the dataset:

- [Eye Diseases Classification Dataset | Kaggle | 4217 Images](https://www.kaggle.com/datasets/gunavenkatdoddi/eye-diseases-classification)

#### Citation Swin Transformer

```
@inproceedings{liu2021Swin,
  title={Swin Transformer: Hierarchical Vision Transformer using Shifted Windows},
  author={Liu, Ze and Lin, Yutong and Cao, Yue and Hu, Han and Wei, Yixuan and Zhang, Zheng and Lin, Stephen and Guo, Baining},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
  year={2021}
}
```
