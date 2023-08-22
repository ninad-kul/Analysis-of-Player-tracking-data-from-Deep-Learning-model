# Analysis of Player tracking data given by Deep Learning model
In this I am trying to do the analysis of data given by player detection model in form of .CSV file.
The player detection model was used on a video of volleyball match and we got a csv file containing coordinates of bounding boxes around each player for each frame.
I am calculating the centroid of the bounding box around each player and considering it as the position of that player.

Using the position (centroid) I am trying to calculate the following parameters -- 
1. Nearby players i.e. having distance less than 100 pixels. (done)
2. Total distance covered by the player in pixels during the rally. (in progress)
3. Average speed of the player in pixels per second (in progress)

Attaching the python colab script.

Tried doing it by using object oriented features to gets hands dirty in it.
