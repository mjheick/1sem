# 1sem
Shorten long videos to one second every minute (1sem).

Effectively you can take a 30 minute video and shorten it to 30 seconds.

Why would anyone want this?

# Usage
```
php -f 1sem.php video.file
```
output filename is video.1sem.file

# Requirements
- PHP (created and tested on 8.3.0RC4)
- [FFMpeg and FFProbe](https://ffmpeg.org/)

# Sources
- https://unix.stackexchange.com/questions/283878
- https://shotstack.io/learn/use-ffmpeg-to-concatenate-video/
- https://trac.ffmpeg.org/wiki/Seeking
