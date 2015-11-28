# How To Linux

## Open a Terminal
1. Press `Ctrl+Alt+T`
2. or find it in the applications list

## Download a YouTube video
1. Open a Terminal
2. Type `youtube-dl <videoURL>`

## Download from iPlayer
1. Open a Terminal
2. Type `get-iplayer` for a list of programs
3. Find the code of the one you need
4. Type `get-iplayer --get <code>`

## Change video/audio format
1. Open a Terminal
2. Type `ffmpeg -i <inputFile> <outputFile>`
  + format is chosen automatically by output file extension
  + eg: `ffmpeg -i video.mp4 soundtrack.mp3` just converts the video of `video.mp4` into an mp3 file

## Update the software on the computer
1. Open a Terminal
2. Type `sudo apt update && sudo apt upgrade`
3. Type the password

## Install Chrome
1. Open a Terminal
2. Type `sudo apt install chromium-browser`
3. Be fired from AV
