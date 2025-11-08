# Flood Area Segmentation using DeepLabV3

This project performs **semantic segmentation for flood detection** using the **DeepLabV3 architecture** implemented in **TensorFlow 2.10**.  
It includes dataset preparation, model training, evaluation, and visualization of predicted masks.

---

## Overview

Flood mapping from satellite or aerial images is an important task in disaster management and environmental monitoring.  
This project uses **DeepLabV3**, a powerful CNN-based segmentation model, to identify flooded regions in given images.

The notebook supports:
- Loading and preprocessing flood datasets (image–mask pairs)
- Training or fine-tuning DeepLabV3 with custom data
- Evaluating model performance
- Visualizing and saving segmentation predictions

---

## Environment Setup

### Create a Conda Environment

Create a new environment with **Python 3.9**:
```bash
conda create -n flood_seg python=3.9
conda activate flood_seg



```bash
pip install tensorflow==2.10 
pip install numpy pandas matplotlib tqdm IPython tf-explain



### Dataset Link

Train data: https://www.kaggle.com/code/k214744nizamuldin/unet-flood-segmentation/input
Test data: https://drive.google.com/file/d/17KSmbiXWLHXZm_5dhYVSVtK-nYi7_efU/view?fbclid=IwY2xjawN29klleHRuA2FlbQIxMQABHoSVHvLOwdJflOeU4Uvf2AvpBiHVxQEJcPZ7bpu1uHY3bmay333_87lshQCB_aem_GAK5Ep__yo1JI1LsCJ2Mlg




