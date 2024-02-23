Movie settings will generate .jpg frames. These can be converted with ffmpeg e.g:

ffmpeg -r 25 -i C:\dev\mandel\movie\frame%04d.jpg -c:v libx264 -preset slow -crf 18 C:\dev\mandel\movie\zoom.mp4

Example movie:

![Example mandelbrot zoom movie](https://drive.google.com/file/d/1G8vEifFbt_6SvWcWZx_0-mFQJFBpA8v3/view?usp=sharing)