# AMLS_assignment22_23-
Student Number:18086046
ELEC0134 Assignment Instructions:
1.Create a folder named "AMLS_22_23_SN18086046"
2. Download the training and test datasets using the links provided in the worksheet and store them in the folder "Datasets" inside the folder "AMLS_22-23_SN18086046"
3. Now the folder "Datasets" should have 2 folders containing the data for the training and test sets
4. Open all "labels.csv" files and select the first column,go to Data->Text to columns->Press Next-> Choose Tab delimiters and press Next-> Press Finish
5. Save the ".csv" file ith the same name and replace the original file with the modified one
6. The task files must be located at the folder "AMLS_22-23_SN18086046" along with their corresponding saved models
7. Each task file contains the model training as wwell as the validation and test accuracy

Notes:
1. There is no separate main.ipynb file. Instead the test datasets are loaded and their accuracy is tested in the corresponding task files
2. All the task .ipynb files should  be located in the same directory as the .os method is used to locate and load the image data and labels and for that reason no additional folers were created
3. Packages required: Numpy,pandas,os,PIL,skimage,PyTorch,time
