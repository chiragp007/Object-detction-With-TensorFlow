# Object-detction-With-TensorFlow

Wheat-Head-Detction

Step-1
  -: download-> https://github.com/tensorflow/models
  -: filter you image data 
  -: if there is no BBOX in csv for images then remove those images from dataset
  -: csv manipulation
  -: now you have (filterd images + csv)
  -: create Train.csv and Test.csv
  -: create train and test image folder
  -: create train.record and test.record
  -: train your model
  -: MAKE SURE, "SET PATH" WHENEVER IT REQUIRES
  -: Use this "sys.path.append("../slim")'
  -: start training, it will take lots of time
  -: Export Graph with "export_inference_graph.py",  run this file from your Terminal, Don't forget to put path in the file

Step-2
   -:Use saved .pb file
   -:Load it.
   -:and create rectangle wherever it is detected.
