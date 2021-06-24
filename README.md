
# image to text
 A simple python script to convert image to greyscale or binary (useful for further image processing)
 example:

Here is a scaled down (32x32) image of a star:
![Star Icon](https://github.com/rez1-inf/img2txt/blob/main/star32.png)<br>
Then I run the script using `-b` flag to convert to binary: `python3 img2txt.py star32.png 240 -b`
It will create a .txt file with this output:
```
32 32 0 1
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 
0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 
0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 1 1 1 1 1 1 0 0 1 1 1 1 1 1 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 0 1 1 1 1 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 1 1 1 0 0 0 0 0 0 0 0 1 1 1 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 1 1 1 0 0 0 0 0 0 0 0 0 0 1 1 1 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 0 0 0 0 0 0 1 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 0 
```

Here is the same output with `-p` (pretty) flag: `python3 img2txt.py star32.png 240 -b -p`
```
32 32 0 1
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . 1 1 . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . 1 1 . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . 1 1 1 1 . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . 1 1 1 1 . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . 1 1 1 1 . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . 1 1 1 1 . . . . . . . . . . . . . . 
. . . . . . . . . . . . . 1 1 1 1 1 1 . . . . . . . . . . . . . 
. . . . . . . . . . . . . 1 1 1 1 1 1 . . . . . . . . . . . . . 
. . . . 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 . . . . 
. . . . . 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . 
. . . . . . 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . . 
. . . . . . . . 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . . . . 
. . . . . . . . . 1 1 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . . . . . 
. . . . . . . . . . 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . . . . . . 
. . . . . . . . . . . 1 1 1 1 1 1 1 1 1 1 . . . . . . . . . . . 
. . . . . . . . . . 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . . . . . . 
. . . . . . . . . . 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . . . . . . 
. . . . . . . . . . 1 1 1 1 1 1 1 1 1 1 1 1 . . . . . . . . . . 
. . . . . . . . . 1 1 1 1 1 1 . . 1 1 1 1 1 1 . . . . . . . . . 
. . . . . . . . . 1 1 1 1 . . . . . . 1 1 1 1 . . . . . . . . . 
. . . . . . . . . 1 1 1 . . . . . . . . 1 1 1 . . . . . . . . . 
. . . . . . . . 1 1 1 . . . . . . . . . . 1 1 1 . . . . . . . . 
. . . . . . . . 1 . . . . . . . . . . . . . . 1 . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 

```
#### How to use:
```python3 img2txt.py <image_file> <threshold_value> <optional_flag_to_convert_to_binary> <optional_flag_to_pretty_print>```

eg 1: `python3 img2txt.py /home/Desktop/img2.png 240 -b -p`(-b is converte to binary, outputs 0 & 1) (-p is instead of printing 0's print a dot)<br>
eg 2: `python3 img2txt.py img2.jpg 255 -p` (here 255 is max threshold, meaning no pixel value will be replaced with 0)<br>
eg 3: `python3 img2txt.py img2.jpeg 250` (all greyscal pixel values greater than 250 will be replaced with 0)
