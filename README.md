# Requirents-For-Darknet
# generate_train.py will generate train.txt file

open cmd on darknet folder, and run this file by typing "python generate_train.py" in cmd.
Then u will find a text file named as train.txt in data folder. 

In case, if generated train.txt file is empty(0 bytes) then, there is problem in "generate_train.py" of line "if filename.endswith(".jpg"):"
Line: "if filename.endswith(".jpg"):" here replace the extension of ur dataset image's extenion. For exapmle, try with .JPG or .JPEG or .png 
