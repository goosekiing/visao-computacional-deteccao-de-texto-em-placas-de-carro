# Computer Vision: Text Detection on Car Plates

This repository contains a project focused on creating code capable of reading car plates from images. The project explores various image processing methods provided by the OpenCV library to highlight the region of interest, which in this case is the car plate. These methods include:

## Image Processing Methods
- **Thresholding:**
  - Simple Thresholding
  - Adaptive Thresholding
  - Otsu's Thresholding
- **Morphological Transformations:**
  - Erosion
  - Dilation
  - Opening
  - Closing
  - Gradient
  - Top Hat
  - Black Hat

The project involves testing these methods to understand and evaluate the best techniques for highlighting the area of interest in images. After satisfactory image processing to capture the region of interest, regex along with Tesseract is used to read and capture the characters on the plate.

## Course Details
This project was completed as part of the 'Computer Vision with OpenCV' course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-visao-computacional-opencv).

## Objectives Achieved
- Learn to apply image processing techniques.
- Detect the position of a vehicle plate in an image.
- Understand how to recognize text in images using Tesseract.
- Learn about the different types of thresholding.
- Understand the morphological transformations that can be applied to images.
- Detect object edges in images.

## Technologies Used
- Python (v3.11.4)
- Jupyter Notebook
- Pytesseract (v0.3.9)
- OpenCV (cv2 v4.6.0)
- Matplotlib
- Numpy
- Skimage

## Project Structure
The directory structure of the project is as follows:
```
visao-computacional-deteccao-de-texto-em-placas-de-carro/
│
├── imagens/ (contains the images used in the project)
├── project-01.ipynb
├── requirements.txt
├── README.md
```

## Setup Instructions
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/visao-computacional-deteccao-de-texto-em-placas-de-carro.git
   ```
2. Navigate to the project directory:
   ```sh
   cd visao-computacional-deteccao-de-texto-em-placas-de-carro
   ```
3. Create a virtual environment and activate it:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```
4. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```
5. Install Tesseract on your machine. The version used in this project is 5.3.3 for Windows, available for download at: [Tesseract Download](https://digi.bib.uni-mannheim.de/tesseract/)

## Running the Notebook
1. Open Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
2. Run the `project-01.ipynb` notebook to see the text detection on car plates in action.

## Language
The language used in this project is Brazilian Portuguese (pt-br).

## Author
GitHub: [goosekiing](https://github.com/goosekiing)