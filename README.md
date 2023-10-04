# -*- coding: utf-8 -*-
"""
Created on Wed Aug 16 19:54:06 2023

@author: Anas
"""


**PUSH WITHOUT 'virtual environment' FOLDER:**

**Step1:** Create '.gitignore' file and add 'v1/'

**Step2:** 
!git init
!git add .
!git commit -m "Commit all files excluding v1"
!git push origin master
_____
_____




**GITHUB PUSH USING LFS:**
_____
As some files are large, use lfs.

**Step1:** !git init

**Step2:** !git lfs install

**Step1:** !git lfs track "*"

**Step4:**
!git add .
!git commit -m "Add files with LFS tracking"
!git push origin master

_____
_____


**CREATE VIRTUAL ENVIRONMENT:**
_____
**Step1:** Open another tab in 'Anaconda Powershell Prompt' and go to the project directordirectory.

**Step2:** python -m venv v1

**Step3:** .\v1\Scripts\activate

**Step4:** conda install spyder-kernels=2.4

**Step5:** pip install --upgrade spyder

**Step6:** run 'spyder' and spyder with 'v1' environment will be opoen

**Step7:** Tool>Prefrences>Python Interpreter> Use the following Python Interpreter: go to v1's python (i.e. D:/work/ProductionWork/Production2_Yolo_nas/v1/Scripts/python.exe)

_____
**Note:** step 2 command will not work in Console of spyder. It must me run in terminal (Anaconda Powershell prompt)
