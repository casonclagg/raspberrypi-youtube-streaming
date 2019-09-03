# raspberrypi-youtube-streaming

Stream straight to YouTube from your Raspberry Pi with Docker.

docker run -it \
-e YOUTUBE_KEY=ABC \
-e BIT_RATE=6000000 \
-e FPS=30 \
ccc/rascam
