
# National ID Card Recognition


This Python script extracts text from ID card images using OpenCV and Tesseract OCR.

## Prerequisites

- Python 3.x
- OpenCV (`pip install opencv-python`)
- Tesseract OCR ([[invalid URL removed]]([invalid URL removed]))
- pytesseract (`pip install pytesseract`)
- numpy (`pip install numpy`)
- matplotlib (`pip install matplotlib`)
- pandas (`pip install pandas`)

## Usage

1. **Set Tesseract OCR path:**
   - Update the `tesseract_path` variable in the script with the correct path to your Tesseract OCR executable.

2. **Run the script:**
   - Open a terminal or command prompt.
   - Navigate to the directory where the script is located.
   - Execute the script using the following command:
     ```bash
     python id_card_text_extractor.py
     ```

3. **Enter image path:**
   - When prompted, enter the path to the ID card image you want to process.

4. **View results:**
   - The script will display the extracted text in a pandas DataFrame.
   - It will also display intermediate image processing steps (blurred image, Canny edges, contours).

## Additional Notes

- **Error handling:** The script includes basic error handling to catch common issues like invalid image paths or OCR errors.
- **Customization:** You can customize the script to extract additional fields from the ID card or modify the image processing steps as needed.
- **Language support:** The script currently uses the Arabic language model for Tesseract OCR (`lang='ara'`). Adjust this setting if you're working with ID cards in a different language.

## Contact

For any questions or issues, feel free to contact [Eng/Omar Adel] at [omaratito202020@gmail.com].
