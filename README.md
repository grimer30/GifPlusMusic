# GifPlusMusic
Input a gif and some music, output a video of the gif playing to the music :) 

## Documentation: 

When you open the program, here is a list of options that you will see. 

### Choose Image
Clicking on this button will open a file dialog and let you choose a gif or image file. Of course, a gif file will have multiple frames while a png file will just have one frame. Lots of image formats probably work, I haven't tested it. 
### Gif Framerate/BPM
The box on the left is the speed at which the frame of the gif will change. If you know the BPM of the audio (and want the gif to match up to that BPM), you can set the BPM on the right and it will automatically update the framerate box on the left. You can get the BPM to any piece of music fairly easily using a website like this: https://taptempo.io/ 
### Choose Audio
Clicking on this button will open a file dialog and let you choose an audio file. This audio will play in the output video. It is assumed that the music will be longer than the gif. 
### BG Image
This is an optional field! If you want to have a background behind the gif, you can add it as an image here. Neither the gif image or the background will be resized in any way, so you can set and compare the sizes for them yourself beforehand (using your fav graphics editor software). 
### FG Image
This is a double-optional field, optional on top of the background being optional. This foreground image (if you choose to use it) should be the same size as the background image, and will overlay on top of both the background and gif images. I thought this would look cool. Parallax (different movement speeds for the background and foreground) is not supported yet. 
The way I created my foreground image was by drawing it on a separate layer on top of the backgroud image and then exporting the layers separately, I recommend that if you're interested.  
### Background Framerate
This is the framerate that the background will move at - of course this has no effect if there is no background. The higher the framerate the longer the program will take to generate the video, I am not responsible for you crashing your computer etc.
Note that the output framerate of the video will always be 30FPS (regardless of both the gif framerate and background framerate). This is for compatibility with video players. 
### BG Movement Speed
This is the speed that the background will move at. Actually it is NOT the speed the background will move at: it is the distance the background will move per frame. This means that if you change the background framerate the 'speed' will actually also change. 
### Fade In/Out Seconds
The video will have a fade-in and fade-out effect unless you set this option to 0. This number is the time that the video will be fading in and out in seconds, and is independent of the framerate.  
### Output Video Path
This is the path for the output video. I recommend having the path start with .\ to have the file be outputted in the same folder as the executable. Changing the extension probably won't change the actual video codec or output format, support for different codecs could come in a future update. 
### Make Video
Clicking this button will start the video making process. While this process is going the button will be greyed out so that you can't accidentally double click on it. Changing any settings while it's running hopefully won't break anything but I haven't tested it. The button should become un-greyed once the video has been outputted. 
### Progress Bar
This is a progress bar to tell you how done making the video is once you've clicked Make Video. You cannot click on it or do anything with it, only watch it (watching it is optional). 


Note for posting on Discord: I have no idea why Discord doesn't support these videos. If you run the video through https://8mb.video/ then the output does work. 
