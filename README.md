# PuppetGAN: Manipulating Images with Crude Synthetic Proxies
- Repo for CS 585 Final Project.

# Teammates

- Yuan Zhang
- You Peng
- Junyi Zhu

# Report
- [Report is here.](./585_FinalReport.pdf)

# Dataset

- It's in [Google Drive](https://drive.google.com/drive/folders/1AS5Vmr8Ggk-yYsCEIc1_it67jJ8z1fqK?usp=sharing) 
since it's too large for Github.

- Unzip to ```./data```

# Instrcutions

- Open the dataset link and go into ```data/bodies/```.

- Choose a resolution among ```128x128```, ```64x64```, ```32x32```.

- Rename the folders which denotes the resolution you choose. For example you want to use ```128x128```:
    - First rename ```real_128``` to ```real_```.
    - Do the same for ```rows_128``` and ```synth_128```.
    
- Change the setting of **image size** for key ```bodies``` in ```./PuppetGAN/config.json```.

- Run main.py. 

# Result Files

- They are in [Google Drive](https://drive.google.com/drive/folders/1AS5Vmr8Ggk-yYsCEIc1_it67jJ8z1fqK?usp=sharing) 
since they are too large for Github.

- Unzip ```checkpoint``` to ```./PuppetGAN/checkpoints/PuppetGAN```
  
- Unzip ```results``` to ```./PuppetGAN/results```


# Credit
- BU CS 585 Professors and TAs
- [Original PuppetGAN Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Usman_PuppetGAN_Cross-Domain_Image_Manipulation_by_Demonstration_ICCV_2019_paper.pdf)
- [SynAction dataset](https://arxiv.org/pdf/1812.01037.pdf)
- [PuppetGAN Unofficial Code](https://github.com/GiorgosKarantonis/PuppetGAN)
- [Weizmann AsSTS Dataset](http://www.wisdom.weizmann.ac.il/~vision/SpaceTimeActions.html)