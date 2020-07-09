# faceRecognition-using-LBPH
face recognition using LBPH algo, (image processing)

1) extact the harscascade file 
2) run faceRecog_formDB.py file (terminal recommended)
    enter name and numerical id you want to associate with the face, that you are recording
    it will take 100 frames of the face, and then close by itself.
3) open faceRecog_recog.py file  in editor and set the condition, if it finds the ID matching with what you just registered, and save the file
4) run the faceRecog_train.py file, it will run the algorithm and store the trained file.
5) at last run the faceRecog_recog.py file, it will detect the face and give the label with % of confidence in matching and name  associated with the face.
6) press q to end the script

## In the videoCapture(n) change the value of n to 0 or 1 as per the device you are using.
