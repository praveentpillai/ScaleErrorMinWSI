# ScaleErrorMinWSI
Code repository associated with the implementation of the method discussed in the paper titled "Efficient Tissue Segmentation in Gigapixel Whole Slide Images via Heuristic Scaling Error Minimization". This paper discusses a heuristic method for segmenting the tissue regions from gigapixel Whole Slide Images by utilizing its low-resolution counter path.

This code base contains the following two self contained Jupyter Notebooks that can be used to reproduce the results discussed in this paper.
1. main_code_panda.ipynb: contains code for running the proposed method on PANDA dataset.
2. main_code_otsu.ipynb: contains code for running the proposed method on CPTAC-CM dataset.

The notebooks have been executed in Google Colab environment. The dependencies and other path variables have been clearly stated within the file. One may change the pathname as per the environment used to execute the code.

The dataset associated with the study can be downloaded from: https://drive.google.com/drive/folders/13bDVN1qUpeaAoy3bRO52PEgKJC2PViuH?usp=sharing. Download it to a directory and appropriately set the path in the file. The code has been tested on the Google Colab environment without any GPU support.
