# Human-Count-detection
In this i have created a program to detect, track and count the no. of humans in the chosen video using YOLO v8 , Centroid tracking algorithm merged with Hungarian algorithm.

'human counting yolo v3-v4' file contains the code for detecting humans using yolo v3 (or v4 as required) and my own centroid tracking algorithm. I have provieded you with coc.names, cfg files of yolo v3,v4 , but you need to download weights file from the internet.

'human counting v8' file contains the code for detecting humans using yolo v8 and my own centroid tracking algorithm. I have provided you with the sample video . you dont need any other file to run this code, just the main file and sample video is enough ! 

Note 1 : if you are using any other video to detect/count/track humans (or any other object that yolo detects) change the roi1 and roi2 values in main function as required.

Note 2 : i have used my own centriod tracking algorithm , so this code is not as effitient as other algortihms out there. all the youtube videos and codes that i saw needs tons of files to run this project or you need to clone deep sort repository. I have made this simple by implementing everything into one file with simples logics. Thanks for visiting.
