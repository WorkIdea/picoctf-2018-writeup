# Truly an Artist
Points: 200

## Category
Forensics

## Question
>Can you help us find the flag in this [Meta-Material](files/2018.png)? You can also find the file in /problems/truly-an-artist_3_066d6319e350c1d579e5cf32e326ba02. 

### Hint
>Try looking beyond the image.
>
>Who created this?

## Solution
$ exiftool 2018.png                                                                                                                                                                            
ExifTool Version Number         : 10.10
File Name                       : 2018.png
Directory                       : .
File Size                       : 13 kB
File Modification Date/Time     : 2018:12:19 17:59:02-05:00
File Access Date/Time           : 2018:12:19 17:59:51-05:00
File Inode Change Date/Time     : 2018:12:19 17:59:30-05:00
File Permissions                : rw-rw-r--
File Type                       : PNG
File Type Extension             : png
MIME Type                       : image/png
Image Width                     : 1200
Image Height                    : 630
Bit Depth                       : 8
Color Type                      : RGB
Compression                     : Deflate/Inflate
Filter                          : Adaptive
Interlace                       : Noninterlaced
Artist                          : picoCTF{look_in_image_13509d38}
Image Size                      : 1200x630
Megapixels                      : 0.756


### Flag
`flag` picoCTF{look_in_image_13509d38}
