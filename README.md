# Code-Smell-Detection-using-CNN

1. For creating required input data:

	a. Download CodeSmellCNN.zip
	
	b. Download the Designate.jar, CodeSplitJava.jar (provided in the zip file)
	
	c. For Tokenization, Download github project "https://github.com/dspinellis/tokenizer", build and install it.
	
	c. In "data.py", provide the paths for required files
	
	d. Create folders and provide the path for JAVA_CODE_SPLIT_OUT_FOLDER_CLASS, JAVA_CODE_SPLIT_OUT_FOLDER_METHOD, 		    JAVA_SMELLS_RESULTS_FOLDER, JAVA_LEARNING_DATA_FOLDER_BASE, Tokenizer_Out_Path variables in "data.py" file
	
	e. Run "data.py" file

2. Providing the tokenized data outputfile  "TokenizerOutput.zip". Ignore step 1, if you don't want to create data from scratch.



Running the model:


1. Download the CNNModel.ipynb file


2. Update the path for "N_path", "P_path" variables in the file with the test data folders for the required code smell we got from      	above


3. Run all the cells in the files sequencially
