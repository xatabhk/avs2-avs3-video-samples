# avs2(IEEE.1857-4) video samples
AVS2/IEEE.1857-4 encoded video samples.

test1_avs2.mkv<br>
  Basic file. It contains AVS2 video (854x480), MP3 audio. The sample comes from the Big Buck Bunny open project.
 
test5_avs2.mkv<br>
  Multiple audio/subtitles. The sample contains AVS2 video (1024x576 pixels), and stereo AAC and commentary in AAC+ (using SBR). The source material is taken from the Elephant Dreams video project

Beijing 2022 winter olympics emblem_avs2.mkv<br>
  Basic file. It contains AVS2 video (1920x1080), and stereo AAC audio. Official video of Beijing 2022 Winter Olympic Games emblem.

# avs3(IEEE.1857-10) video samples
AVS3/IEEE.1857-10 encoded video samples.

test5_avs3.mkv<br>
  Multiple audio/subtitles. The sample contains AVS3 video (1024x576 pixels), and stereo AAC and commentary in AAC+ (using SBR). The source material is taken from the Elephant Dreams video project

# Encoder used for generating samples videos:
Ffmpeg: https://github.com/xatabhk/FFmpeg-avs2-avs3/releases/tag/n4.4-dev-avs3<br>
Command line examples for encoding AVS2 and AVS3 videos：<br>

```
ffmpeg -i xxx.mp4 -vcodec avs2 -acodec copy xxx_AVS2.mkv
ffmpeg -i xxx.mkv -vcodec avs3 -acodec copy xxx_AVS3.mkv
```

# Video players with CAVS/AVS2/AVS3 enabled:
1.	Ffmpeg: https://github.com/xatabhk/FFmpeg-avs2-avs3/releases/tag/n4.4-dev-avs3<br>
Commmand line examples for playing videos:
```
ffplay xxx_AVS2.mkv
ffplay xxx_AVS3.mkv
```
2.	Mpc-hc: https://gitee.com/zhengtianbo/cavs-avs2-avs3_decoder_added_to_mpc_hc/releases
3.	Vlc3: https://github.com/xatabhk/vlc-3.0-avs2-avs3/releases/tag/v3.0-avs2-avs3-200830
4.	Vlc4: https://github.com/xatabhk/vlc-avs2-avs3/releases/tag/v4.0-avs2-avs3-200830

