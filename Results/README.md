# Results

This folder exposes the results obtained when running a hog detector with OpenCV's pre-trained SVM for person detection.


The dataset of images that were tested is a subset of the INRIA person dataset.

The dataset contains:

 	* Total number of images: 53
	* Total number of positives: 18
	* Total number of negatives: 35


The resulting images of the person detections with the drawn bounding boxes are found in the 'detection_results' folder.


The results are the following:

	* True positives: 16 (88% of the total number of positives)
	* True negatives: 30 (85% of the total number of negatives)

	* False negatives: 2
	* False positives: 5



Success and failure examples the Non Maxima Suppression procedure are found in the 'non\_maxima_suppression' folder. 

