# Video Thumbnails
Video thumbnails can be generated with the following command: `ffmpeg -i "<input>" -vf "select=eq(n\,<frame>)" -vframes 1 "<output>"`
> https://superuser.com/questions/1009969/how-to-extract-a-frame-out-of-a-video-using-ffmpeg

# GIFs
GIFs can be compressed with a variation of the following command: `ffmpeg -i <input> -filter_complex "fps=15,scale=-1:400" <output>`