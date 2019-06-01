# PET dataset

### script
```bash
pip3 install wget
cd datset/original
bash download_pet_dataset.sh
cd ..
bash split_train_val_images.sh
```
 - download_pet_dataset.sh
    - download pet dataset and extract tar.gz
    
  - split_train_val_images.sh
    - 90% train data
    - 10% validation data 

### Requirements
 - wget

### Reference
 - https://www.robots.ox.ac.uk/~vgg/data/pets/