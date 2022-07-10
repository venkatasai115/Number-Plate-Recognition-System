# Number-Plate-Recognition-System
--> Install Pycharm and create a new project and create virtual environment in pycharm 
--> Before starting the project in pycharm, Please install pytesseract OCR on your windows version 5.0.0 (link for the given OCR =https://digi.bib.uni-mannheim.de/tesseract/)
	Goto the link and if your windows is 32bit then click on "tesseract-ocr-w32-setup-v5.0.0-alpha.20200328.exe"
					  if 64bit then click on "tesseract-ocr-w64-setup-v5.0.0-alpha.20200328.exe"
	now We need to set the path for installed Pytesseract OCR
				1. Go to the destination folder of Pytesseract. For example if my Pytesseract OCR installed in "C:program Files\Pytesseract-OCR" then copy the path.
				2. Go to system properties.
				3. Click on advanced system settings.
				4. Click on Environment Variables
				5. Under user variables click on new and set the variable name as "TESSERACT_PREFIX" and variable path as "C:program Files\Pytesseract-OCR".
				6. Click on ok and close all windows

--> Please install Pandas, Numpy , OpenCV , SQLite3 , imutils , sys , matplotlib in the pycharm package installer where we can download the packages directly into our virtual environment
                                           (OR)
If we have installed python in our system then we can execute the code by installing python and the required modules can be downloaded by using command prompt

for Pandas      >>>python -m pip install pandas
for Numpy      >>>python -m pip install Numpy
for OpenCV    >>> python -m pip install cv
for SQLite3     >>>python -m pip install sql
for imutils	      >>>python -m pip install imutils
for sys             >>>python -m pip install sys
for matplotlib  >>>python -m pip install matplotlib
for pytesseract >>>python -m pip install pyocr

--> Now run the code and we can see the stepwise output images as output and the text on number plate printed on output terminal and updated in the csv file.
--> We can store the result and update it as required.
