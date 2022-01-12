# 2021_VRDL_HW4

## Setup
```
git clone https://github.com/cszn/KAIR.git
pip install timm
```
### Put vrdl_hw4_train.py in KAIR
### Put vrdl_hw4_train.json in KAIR/options/swinir

## Training
```
cd KAIR

python vrdl_hw4_train.py --opt options/swinir/vrdl_hw4_train.json

```

## Inference
```
cd KAIR

python vrdl_hw4_test.py --task classical_sr --scale 3 --training_patch_size 48 --model_path model_path --folder_lq lr_images_path --folder_gt lr_images_path

```
