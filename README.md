## About Invictus
Invictus is a set of jupyter notebooks showcasing how to accomplish specific computer vision task using the Python programming language.

### Setting Up
It is generally encouraged that you always use Python virtuan environment to have isolated Python installations per project. In this guide, I suggest you do the same. So 'cd' into the 'invictus' directory that you've cloned onto your computer and perform the following actions to run the notebooks in a separate virtual environment.

1. ```conda create -n myenv python=3.6```
2. ```activate myenv```
3. ```pip install -r requirements.txt```
4. ```jupyter notebook```

### Opening Notebooks
In invictus, every notebook is self-contained and demonstrates end-to-end flow of actions that must be taken to accomplish a given task. The name of a notebook file suggests its purpose.

Once you've started jupyter notebooks with the command ```jupyter notebook``` you must open http://localhost:8888/ in your browser to see the tree of files and directories in invictus.

Click on the ```notebooks``` folder and select your notebook of choice to see the code demonstration.

_______________________
pytesseract application

for windows 32bit https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w32-setup-v5.0.0-alpha.20201127.exe

for windows 64bit https://digi.bib.uni-mannheim.de/tesseract/tesseract-ocr-w64-setup-v5.0.0-alpha.20201127.exe

WARNING: Tesseract should be either installed in the directory which is suggested during the installation or in a new directory. The uninstaller removes the whole installation directory. If you installed Tesseract in an existing directory, that directory will be removed with all its subdirectories and files.
