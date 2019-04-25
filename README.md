<b>ffmpeg -i videoPath.mp4 -s 384x216 -vf fps=1 filePath/%d.jpg</b><br>
Make a one-second image from video.For example, it creates 3600 frames from a 1-hour video. The size of the image to be identified as 386x216

<b> ffmpeg -i udp://xxx.x.x.x:1234 -map 0:10 -map 0:9 -c:v copy -c:a copy -f mpegts filePath.ts </b>  <br>
Create a video of the channel you specify from all channels in the ts format.

<b>ffmpeg -i udp://xxx.x.x.x:1234  -c:v copy -c:a copy -f mpegts filePath.ts </b><br>
Randomly creates data in ts format from the inside of the stream

<b>ffmpeg -i udp://xxx.x.x.x:1234  -c:v copy -c:a copy filePath.mp4 </b><br>
Randomly creates data in mp4 format from the inside of the stream

<b> ffplay udp://xxx.x.x.x:1234 </b> <br>
Plays video by selecting one of the random content in the stream

