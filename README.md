# biznet-mrtg-average-report

This script perform data extraction from Biznet MRTG only for average upload and download traffic.<br>
The code may full of mess, but it helped me a lot.

<b>Requirement:</b><br>
- Python3 <br>
- Firefox webdriver<br>
- Tesseract OCR, set the correct path to the tesseract.exe. Find the installer inside the ocr folder<br>
https://medium.com/quantrium-tech/installing-and-using-tesseract-4-on-windows-10-4f7930313f82

<b>Usage:</b><br>
$python mrtg.py yyyy-mm-dd<br>

Result will be stored in the log folder as txt file