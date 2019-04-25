
<b> ffmpeg -i udp://xxx.x.x.x:1234 -map 0:10 -map 0:9 -c:v copy -c:a copy -f mpegts filePath.ts </b>  <br>
Create a video of the channel you specify from all channels in the ts format.

<b> ffplay udp://xxx.x.x.x:1234 </b> <br>
Plays video by selecting one of the random content in the stream

