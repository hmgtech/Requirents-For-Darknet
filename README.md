# Requirents-For-Darknet
# Label Image:
If your dataset have been collected, then we need to label it for object detection.
For label the image, we need to download the tool. I prefer labelImg by tzutalian which is python scripted and it is much easier to use.
To get this, we need to clone their repository. link: github.com/tzutalin/labelImg
All the requirements to run this tool is mentioned there. 
Apart from this, i made a video how to use it. you can refer it also. link: https://www.youtube.com/watch?v=unxKwZ9_zCc

# After Labeling  the image we need to download darknet repository. 
Clone this : https://github.com/AlexeyAB/darknet

# After downloading darknet:
we need to extract the it. And we have to make it.

# generate_train.py will generate train.txt file

open cmd on darknet folder, and run this file by typing "python generate_train.py" in cmd.
Then u will find a text file named as train.txt in data folder. 

In case, if generated train.txt file is empty(0 bytes) then, there is problem in "generate_train.py" of line "if filename.endswith(".jpg"):"
Line: "if filename.endswith(".jpg"):" here replace the extension of ur dataset image's extenion. For exapmle, try with .JPG or .JPEG or .png 

