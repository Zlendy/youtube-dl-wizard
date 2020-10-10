# Dependencies

You need these dependencies for the script to work
- [youtube-dl](https://youtube-dl.org/downloads/latest/youtube-dl)
- ffmpeg/ffprobe
  · [GNU/Linux](https://johnvansickle.com/ffmpeg/)
  · [Windows](https://www.gyan.dev/ffmpeg/builds/)
- [Python3](https://www.python.org/downloads/)

## How to make the dependencies recognizable for the script.

### GNU/Linux
1) Download and install python3, from the website or your distribution repositories. Skip this step if you have it installed already.
2) Download a compatible ffmpeg static release version for your CPU architecture.
3) Move the files "ffmpeg" and "ffprobe" located at the root of that folder into the directory named "ffmpeg_ffprobe" in youtube-dl-wizard.
4) Start the script

### Windows
1) Download and install python3 from the Microsoft Store or the website. Skip this step if you have it installed already.
2) Download ffmpeg-release-essentials. Keep in mind that if you download it as a 7z compressed archive you need the tool [7-Zip](https://www.7-zip.org/) to uncompress it.
3) Move the files "ffmpeg.exe" and "ffprobe.exe" located at the folder "bin" into the directory named "ffmpeg_ffprobe" in youtube-dl-wizard.

You can use the same folder between multiple operating systems as long as the dependencies located correctly.