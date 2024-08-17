# Image to PDF
This Python script allows you to convert images from a specified directory into a single PDF file. The script supports common image formats such as .jpg, .jpeg, .png, and .gif.

## Requirements
- Python 3.x
- img2pdf library
- Jupyter Notebook (optional)

Install required package 
```
pip install img2pdf
```

## How to Set Up
- 'main_dir' should be the path to your main project directory.
- 'file_dir' should point to the folder containing your images.
- 'output_file' is the path where the generated PDF will be saved. Ensure this path points to a valid directory and that you have write permissions.

## Running Script
```
images_to_pdf(file_dir, output_file)
```
