# Abandoned Object Detection
Detects abandoned objects in a video, particularly useful for identifying suspicious abandoned luggage in railway stations and bus stands.
This is a project developed in MATLAB, which is used to detect abandoned objects automatically from a video, particularly useful for identifying suspicious abandoned luggage at busy places like railway stations and bus stands. For this, the first frame of the video is assumed as the background image. The video is converted to frames of images and then each frame is subtracted from the background image and if an object remains static at one place for a fixed number of frames, then it is declared as an abandoned object and an alarm is raised.

### Data Set Used for Testing:
  Videos at https://github.com/kevinlin311tw/ABODA
