# FaceRecognitionAttendanceSystem
facerecognition based attendance system this project is develop using python
and uses haarcascade_fortal_face_default_xml to train the images very quickly
here train images are converted into gray scale images 
this project has several windows , but it is not connected with any database,
all the entry and data is store in your local storage 

for use this project first you need to install all necessary files , then change the 
location of storage 
import tkinter as tk
from tkinter import *
import os, cv2
import shutil
import csv
import numpy as np
from PIL import ImageTk, Image
import pandas as pd
import datetime
import time
import tkinter.font as font
import pyttsx3

# project module
import show_attendance
import takeImage
import trainImage
import automaticAttedance
