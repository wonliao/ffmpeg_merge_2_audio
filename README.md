ffmpeg_merge_2_audio
====================

user ffmpeg merge 2 audio file to 1 file

在 MAC 上使用下列指令進行 merge 2 audio file

./ffmpeg -i 1.mp3 -i 2.m4a -filter_complex amerge -c:a libmp3lame -q:a 4 output.mp3
