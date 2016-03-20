## Youtube Playlist Scripting

Script to run videos in an array playlist

###Random sequence
#####The first variable in the script sets the looping to be linear or random
---
###Player parameters
<dl>
  <dd>Autoplay</dd>
  <dd>No controls</dd>
  <dd>Mute</dd>
  <dd>No information</dd>
</dl>
---
###To add videos
#####Add to the videoList array with:
<dl>
<dt>videoId:</dt>
  <dd>youtube URL between 'v=' and '&'</dd>
  <dd>eg -- "http://www.youtube.com/watch?v=pfqNykQgaOs&feature=channel_video_title" -- would become "pfqNykQgaOs"</dd>
<dt>startSeconds:</dt>
  <dd>Start time (seconds)</dd>
<dt>endSeconds:</dt>
  <dd>Duration (seconds)</dd>
<dt>suggestedQuality:</dt>
  <dd>'suggested' video quality.</dd>
</dl>
