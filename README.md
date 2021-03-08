# SuryaNamaskara

This is a pet project (and probably only for personal use).
Most apps that I find in play store for guiding in Suryanamaskara rounds are buggy. Most of them are advertisement centric that need screen to be left ON, increasing carbon footprint.

* [TTS script for voice](https://gist.github.com/shrkamat/6ae283641aa85f6fe0c97576741e04d3)


#### References
* [Polly: add delay](https://stackoverflow.com/questions/48749984/add-1s-delay-to-end-of-polly-mp3-conversion)
* [Merge multiple mp3 files](https://unix.stackexchange.com/questions/279243/merge-mp3-files)
  ```bash
  ffmpeg -i "concat:SN_1.mp3|SN_2.mp3|SN_3.mp3|SN_4.mp3|SN_5.mp3|SN_6.mp3" -acodec copy SuryaNamaskara_v1p0.mp3
  ```
