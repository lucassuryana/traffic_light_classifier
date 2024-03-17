# Route planner with A* algorithm (python)
- This is the project from [Udacity's Introduction to Self-Driving Cars Nanodegree Program](https://learn.udacity.com/nanodegrees/nd113).
- The code was developed based on the assignment from the Nanodegree program. 
- The assignment was to code a classifier for images of traffic lights that is recorded from self-driving cars.

---

## Project Overview
### Goals
* Develop a feature that can determine which of the three lights is illuminated: red, green, or yellow.

### Structures
This project consists of three files and two folders:
* The folder `images` contains images used in the Jupyter notebook.
* The folder `traffic_light_images` contains test and training images for each light: red, green, and yellow.
* `helpers.py`: This code assists in loading images and their labels.
* `test_functions.py`: This code helps evaluate the implemented functions.
* `traffic_light_classifier.ipynb`: Documentation of the steps performed to develop the traffic light classifier.

### Run the code
To run the code:
1. Clone this respository: https://github.com/lucassuryana/traffic_light_classifier.git 
2. Open traffic_light_classifier.ipynb
3. Run all chunks

### Results
1. The main contribution of the code is the classification algorithm in create_feature function.
2. The accuracy of the classifier is 95.8%