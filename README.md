# DRCPL
Deep Residual Coupled Prompt Learning for Zero-Shot Sketch-Based Image Retrieval

![Fig.1](DRCPL-Model.png)

## ========= Installation and Requirements =========

- ``` cudatoolkit=11.3.1  ```

- ``` numpy=1.19.3  ```

- ``` python=3.7.16  ```

- ``` pytorch=1.10.0  ```

- ``` torchvision=0.11.0  ```

## ============== Datasets ==============

### Sketchy and TU-Berlin
Please go to the [ZSE-SBIR](https://github.com/buptLinfy/ZSE-SBIR)

## ============== Training ==============

### Train with the Sketchy Ext dataset

- ``` CUDA_VISIBLE_DEVICES=1 python train_cse_resnet_sketchy_ext.py  ```

### Train with the TU-Berlin Ext dataset

- ``` CUDA_VISIBLE_DEVICES=1 python train_cse_resnet_tuberlin_ext.py  ```


## ============== Testing ==============

### Test with the Sketchy Ext dataset

- ``` CUDA_VISIBLE_DEVICES=1 python test_cse_resnet_sketchy_zeroshot.py  ```

### Test with the TU-Berlin Ext dataset

- ``` CUDA_VISIBLE_DEVICES=1 python test_cse_resnet_tuberlin_zeroshot.py  ```
