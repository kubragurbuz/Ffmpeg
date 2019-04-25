
<b> ffmpeg -i udp://xxx.x.x.x:1234 -map 0:10 -map 0:9 -c:v copy -c:a copy -f mpegts filePath.ts </b>  

<b> ffplay udp://xxx.x.x.x:1234 </b>
Plays video by selecting one of the random content in the stream

