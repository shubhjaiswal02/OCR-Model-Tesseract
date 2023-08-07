# OCR Model using Tesseract and Pillow

This repository contains a simple Optical Character Recognition (OCR) model implemented using Python and the Tesseract OCR engine along with the Pillow library for image processing. The model is designed to extract text content from images and provide machine-readable text output.

## Benefits

- **Text Extraction from Images**: The OCR model allows you to extract textual information from images, enabling text data to be used in various applications, such as text analysis, data entry automation, and more.

- **Ease of Implementation**: The implementation is straightforward and can serve as a foundation for more complex OCR projects. It utilizes readily available libraries, making it accessible to developers with varying levels of expertise.

- **Customization**: Tesseract provides options for fine-tuning and configuring OCR parameters, allowing you to optimize text extraction for different types of images and languages.

## Limitations

- **Accuracy**: OCR accuracy can be affected by image quality, font style, noise, and layout complexity. The model's performance may vary depending on these factors, and it may not always achieve perfect results.

- **Layout Interpretation**: The current implementation doesn't take into account the layout structure of the extracted text, which can be an issue if the input image contains multiple columns, paragraphs, or other complex layouts.

- **Language Dependency**: While Tesseract supports multiple languages, the accuracy can vary depending on the language being processed.

## Performance Numbers

The accuracy and performance of the OCR model can be evaluated using various metrics, such as precision, recall, and F1-score. The actual numbers will depend on the quality of the input images, the language of the text, and any pre-processing techniques applied.

## System Requirements

To run the provided Python code, your system should meet the following requirements:

- **Python**: Python 3.x is required.

- **Tesseract**: Tesseract OCR engine should be installed on your system. You can download it from the official repository: [Tesseract OCR](https://github.com/tesseract-ocr/tesseract).

- **Pillow**: The Pillow library should be installed. You can install it using the following command: `pip install pillow`.

## Running the Code

Follow these steps to run the OCR code:

1. Install Python 3.x on your system.

2. Install Tesseract OCR engine from the official repository.

3. Install the required libraries by running the following command: `pip install pillow pytesseract`

4. Update the `tesseract_cmd` path in the code to match the path to the Tesseract executable on your system.

5. Execute the OCR code by running the Python script.


## Conclusion

This OCR model showcases the basic capabilities of extracting text from images using Tesseract and Pillow. While it comes with its benefits and limitations, it serves as a starting point for more advanced OCR projects, where additional preprocessing techniques and layout analysis can be applied to enhance accuracy and usability.


