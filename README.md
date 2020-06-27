Monitoring Social distancing on a video file or on a live feed from a camera

Use Google Colab to run the code 

Set runtime with gpu to run the code efficiently

Clone the repository and upload the SocialDistancing2_0.ipynb (or Open the Link https://colab.research.google.com/drive/1ZA1CxAoWZce39_HiyDCtSbNOjkP3pymt?usp=sharing and Make a copy in your drive to modify it) and vid_short.mp4 file on colab

The Code will save 750 frames of the video to a folder and then will process them to detect people and measure the distance between them 
and generate the bounding boxes for each one of them with either blue colored box if they are safe or red if they are too close.

In the last after processing all of the frames it will integrate the frames to make the video out of it which will be saved by the name
vid_short__output.mp4 on the server.

Download the output video file (vid_short__output.mp4) to play it.
