## **Classification of Waste Images**
**DS 4002 Project 3 Group 5**

## Software and Platform 
All code used the [Python](https://www.python.org/downloads/) language on a virtual machine in [Google Colab](https://colab.research.google.com/) 

**Packages Used:**
* EDA & Visualization: [pandas](https://pypi.org/project/pandas/), [matplotlib](https://pypi.org/project/matplotlib/), [seaborn](https://pypi.org/project/seaborn/), [numpy](https://numpy.org/doc/stable/user/absolute_beginners.html), [datasets](https://pypi.org/project/datasets/), [collections.Counter](https://docs.python.org/3/library/collections.html#collections.Counter), [Pillow (ImageStat)](https://pillow.readthedocs.io/en/stable/reference/ImageStat.html)  
* Analysis: [torch](https://pypi.org/project/torch/), [torch.nn](https://pytorch.org/docs/main/nn.html), [torch.optim](https://pypi.org/project/torch-optim/), [torchvision](https://pypi.org/project/torchvision/), [sklearn.metrics](https://scikit-learn.org/1.5/modules/model_evaluation.html), [numpy](https://numpy.org/doc/stable/user/absolute_beginners.html) , [matplotlib](https://pypi.org/project/matplotlib/), [seaborn](https://pypi.org/project/seaborn/), [datasets](https://pypi.org/project/datasets/)
* These links are provided for Python package documentation.
  
## Documentation 
Our data was pulled from [Hugging Face](https://huggingface.co/datasets/garythung/trashnet) 
* **SCRIPTS folder:** contains "ImageData_Analysis.ipynb" which includes the CNN model training and "ImageData_CleaningEDA.ipynb" which includes the data cleaning and EDA.
* **DATA folder:**  contains "ImageData_CleaningEDA.ipynb" which includes data cleaning and initial EDA. This folder also contains "Data Appendix.pdf" and "Instructions to Download Data.pdf."  
* **OUTPUTS folder:** "Results Appendix.pdf" which stores the model figures and accuracy graphs computed from our analysis.

## How to Reproduce Results 
**To reproduce these results:**

- First follow to instructions to download the data - located in our DATA folder under "ImageData_CleaningEDA.ipynb"
- Run the file titled "ImageData_CleaningEDA.ipynb" - located in our DATA or SCRIPTS folder, to view how to go from the raw to clean data and view our EDA.
- Run the file titled "ImageData_Analysis.ipynb" - located in our SCRIPTS folder, to view the CNN model training.
- The PDF files titled "Data Appendix.pdf" and "Results Appendix.pdf" in the DATA and OUTPUTS folder, respectively, containing all figures run from our analysis.

## References

[1] G. Thung. Datasets at Hugging Face. https://huggingface.co/datasets/garythung/trashnet (accessed November 4, 2024) 

[2] G. Parna. Convolutional Neural Network (CNN) in Machine Learning. https://www.geeksforgeeks.org/convolutional-neural-network-cnn-in-machine-learning/
