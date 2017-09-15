# README
This repository contains 4 datasets used in "DropRegion: Training of Inception Font Network for High-Performance Chinese Font Recognition". 

All the datasets are in LMDB format, and in each dataset, `train-lmdb` and `test-lmdb` are training samples and testing samples respectively, while `train-attachment` and `test-attachment` are the indices of training samples and testing samples respectively. 

## SCF\_DB\_25
SCF\_DB\_25 is a character dataset containing 25 font styles, and each font style contains 3866 commonly used Chinese characters. There are 3 levels of training samples size, 200, 400 and 1000, and the size of each sample is 64*64. 

## SCF\_TDB\_25
SCF\_TDB\_25 contains the text block of 320 Chinese Tang poems, using the same font style and characters as SCF\_DB\_25, and 320 poems are split into 8 parts. The  sizes of training samples are 384\*320, and because the testing samples are cropped from the text blocks, he  sizes of testing samples are 128\*128, and each testing sample contains 4 characters. 

## VRICFChar
VRICFChar is a verisimilar real image dataset containing 30 font styles, each of which used the same Chinese characters as above. The size of the samples is 64*64.

## VRICFTextblock
VRICFTextblock is a verisimilar real image text block dataset containing the same font styles as VRICFChar and the same poems as SCF_TDB_25, and the sizes of training samples and testing samples are 384\*320 and 128\*128 respectively.

## Download Links
- [SCF\_DB\_25](http://www.hcii-lab.net/data/IFN_DropRegion_Data/SCF_DB_25.zip)
- [SCF\_TDB\_25](http://www.hcii-lab.net/data/IFN_DropRegion_Data/SCF_TDB_25.zip)
- [VRICFChar](http://www.hcii-lab.net/data/IFN_DropRegion_Data/VRICFChar.zip)
- [VRICFTextblock](http://www.hcii-lab.net/data/IFN_DropRegion_Data/VRICFTextblock.zip)
