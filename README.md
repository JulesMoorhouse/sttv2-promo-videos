# sttv2-promo-videos

ffmpeg -i final-video.mp4 -r 30 -c:v libx264 -preset slow -crf 18 -c:a aac -ar 44100 final-video-30fps.mp4