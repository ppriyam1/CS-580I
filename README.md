FaceFirst is a project developed to replace the traditional door lock systems into a smart system which uses face recognition algorithm as authentication to open the door
The train the model with your faces put the faces in a folder renamed after you and put it into the folder training_data and run the retrain.sh file which would take about 10-15 minutes to train your model depending upon the data set
After training your model with your dataset we can check the accuracy of the model by calling check.sh file in a terminal which will give the accuracies of the model by clicking pictures using your webcam camera
for Implementing on Raspberry pi type on terminal run.sh which would run on raspberry pi
In raspberry pi,
	● The PIR sensor digital Output pin should be connected to pin 11
	● The servo motor pulse input pin should be connected to pin 32
	● Install Rasbian OS in raspberry pi sd card and supply power to it
	● The camera interface should be enabled from the setting of raspbian OS which is start Menu >Preferences > Raspberry 	pi configuration > Interfaces > camera > enable
	● Reboot the system for changes to take effect
	● Connect the camera module into the camera slot but between HDMI and Ethernet port in Raspberry pi
	● run run.sh to start the automatic door lock system