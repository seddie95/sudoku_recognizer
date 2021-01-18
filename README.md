# sudoku_recognizer
Attempt at recognizing digits on a sudoku grid utilizing  Computer vision  and Convolutional Neural Network for Optical Character Recognition 

## Prerequisites
- Install Anaconda
- Open terminal with administration privileges 
- Create environment with requirements
- Install Tesseract


### Installing Anaconda
Anaconda is available for Windows, Linux and MacOS, it can be installed [here.](https://docs.conda.io/projects/conda/en/latest/user-guide/install/)


### Creating Conda Environment and Installing Dependencies
Ensure that for Windows you open the Anaconda prompt or terminal using administrative privileges 
or use sudo for Linux and MacOS.


1. Create the conda environment using the environment.yml file
    ```
    conda env create -f environment.yml
    ```

2. Once the environment has been created successfully with all dependencies  activate the environment.
    ```
    conda activate sudoku_recognizer
    ```
3. Install Tesseract OCR For your OS [here.](https://tesseract-ocr.github.io/tessdoc/Home.html)

## Running Python Notebooks

Open jupyter notebooks to view .ipynb files

```
jupyter notebook
```
New images can be loaded in the notebook by modifying the following line



```python
cv2.imread('NewImage.jpg')
```

## Creating a new model
In order to create a new model with your own fonts just create an empty folder called fonts and copy in the **.TTF** files.
