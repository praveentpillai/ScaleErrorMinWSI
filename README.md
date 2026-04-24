# ScaleErrorMinWSI
Code repository associated with the implementation of the method discussed in the paper titled "Efficient Tissue Segmentation in Gigapixel Whole Slide Images via Heuristic Scaling Error Minimization". This paper discusses a heuristic method for segmenting the tissue regions from gigapixel Whole Slide Images by utilizing its low-resolution counter path.

The organisation of the code base is as follows:
1. lazyslide_method.ipynb: contains code for generating results using the proposed method.
2. lazyslide_method.ipynb: contains code for generating results using the LazySlide tool API.
3. tiatoolbox_method.ipynb: contains code for generating results using the TIAToolbox tool API.
4. result_generator.ipynb: contains code for generating plots as shown in the research paper.
5. output_sample_generator.ipynb: contains code for generating output figures as shown in the research paper.
6. results/ : folder containing the plots generated when the codes within the result_generator.ipynb file are executed.
7. output_images/ : folder containing the figures generated when the codes within the output_sample_generator.ipynb file are executed.
8. scaling_error_estimation/ : folder containing code files for studying the scaling error estimation process.

The notebooks have been executed in Google Colab environment. The dependencies and other path variables have been clearly stated within the file. For execution, follow the below steps:
1. This github repository is to be downloaded to the Google Drive.
2. The notebooks can be opened using Google Colab interfaces and changes have to be made to the path variables as specified in each file.
3. The dataset associated with the study can be downloaded from: [https://drive.google.com/drive/folders/13bDVN1qUpeaAoy3bRO52PEgKJC2PViuH?usp=sharing](https://drive.google.com/drive/folders/1tFYSdAgTHR_cxUx5oU2VH79dab3rpsBn?usp=drive_link). Download it to a directory.
4.  Appropriately set the path in the file.
5.  Once done, the notebooks can be executed independently to generate the results.
