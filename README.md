# Youtube-scripting

Script to run videos in an array playlist

//Random sequence
The first variable in the script sets the looping to be linear or random

//Player parameters
Autoplay
No controls
Mute
No information

//To add videos
Add to the videoList array with:
  videoId: 
    youtube URL between 'v=' and '&'
    eg -- "http://www.youtube.com/watch?v=pfqNykQgaOs&feature=channel_video_title" -- would become "pfqNykQgaOs"
  startSeconds:
    a start time (seconds)
  endSeconds:
    a duration (seconds)
  suggestedQuality:
    'suggested' video quality.
