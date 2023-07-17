# ScreenSnip
Windows python GUI for Google's Tesseract OCR engine

<img src="https://i.imgur.com/4fejZwz.gif"/>

# Libraries to install
- `pip install mss` for screen capture
- `pip install Pillow` for image file reading
- `pip install PyQt5` for GUI
- `pip install pytesseract` for tesseract interfacing (this will be removed in future versions as it does hardly anything)

# Download the required Library files from the link below and save it to ur file directory.

  https://drive.google.com/drive/folders/1wqQdR5XYSnPRDXk9xxWjzS44fVDtlCIs?usp=sharing

# Important
You must download tesseract from https://github.com/UB-Mannheim/tesseract/wiki

After installiation, move around the files so that it matches this:

    .
    ├── TESSDATA                # tessdata folder (comes with installed tesseract)
    │   ├── script
    │   │   ├── Cyrillic.traineddata
    │   │   ├── Arabic.traineddata
    │   │   ├── ...
    │   ├── chi_sim.traineddata 
    │   ├── eng.traineddata     
    │   ├── ...
    ├── TESSERACT               # Main installed tesseract engine
    │   ├── tesseract.exe
    │   ├── text2image.exe
    │   ├── libtesseract-5.dll
    │   ├── ...                 # And lots of other dll's/exe's
    └── ScreenSnip.py           # Main python script from this repo
