ffmpeg_merge_2_audio
====================

user ffmpeg merge 2 audio file to 1 file

在 MAC 上使用下列指令進行 merge mp3 及 m4a 輸出成 ogg

./ffmpeg -i 1.mp3 -i 2.m4a -filter_complex amerge -c:a libmp3lame -q:a 4 -vcodec libtheora -acodec libvorbis output.ogg

在 Linux 上使用下列指令進行 merge mp3 及 m4a 輸出成 ogg

ffmpeg -i 1.mp3 -i 2.m4a -vcodec libtheora  output.ogg
