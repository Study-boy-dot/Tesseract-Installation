# Tesseract-Installation
Installation Tesseract OCR5 on Unbuntu 22.04 bit 64

## Environment
|Environment|Version|
|-----------|----------|
|Architecture|x86_64|
|Ubuntu|22.04|
|python |3.10.12|

## Installation
reference: [https://www.digitalocean.com/community/tutorials/how-to-push-an-existing-project-to-github](https://tesseract-ocr.github.io/tessdoc/)
```
sudo add-apt-repository ppa:alex-p/tesseract-ocr5
sudo apt update
sudo apt install tesseract-ocr
# For python usage
pip install pytesseract
```

## Uninstall
```
sudo apt remove --autoremove tesseract-ocr tesseract-ocr-*
```
