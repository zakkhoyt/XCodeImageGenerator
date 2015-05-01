A couple of bash scrips that will take an input image and output all the various sizes that are required for iOS projects. 

Source image should be at least 1024 pixels. This sample takea an image named logo_1024 and outputs the resized versions to a directory named logo. 

```bash
Usage: generate_logo logo_1024.png logo
Help: genearte_logo --help
```

A sample session is run like this:

```
iMac:test currentuser$ xcimage fireflower.png Icons
Processing icons....
Resizing fireflower.png to Xcode sizes in directory Icons
Created the following images in Icons
total 12312
-rw-r--r--  1 currentuser  staff   584312 May  1 14:48 Icons_1024.png
-rw-r--r--  1 currentuser  staff    13341 May  1 14:48 Icons_122.png
-rw-r--r--  1 currentuser  staff    45202 May  1 14:48 Icons_122@2x.png
-rw-r--r--  1 currentuser  staff    98760 May  1 14:48 Icons_122@3x.png
-rw-r--r--  1 currentuser  staff    14491 May  1 14:48 Icons_128.png
-rw-r--r--  1 currentuser  staff    49880 May  1 14:48 Icons_128@2x.png
-rw-r--r--  1 currentuser  staff   107795 May  1 14:48 Icons_128@3x.png
-rw-r--r--  1 currentuser  staff    18360 May  1 14:48 Icons_148.png
-rw-r--r--  1 currentuser  staff    65818 May  1 14:48 Icons_148@2x.png
-rw-r--r--  1 currentuser  staff   142784 May  1 14:48 Icons_148@3x.png
-rw-r--r--  1 currentuser  staff      780 May  1 14:48 Icons_16.png
-rw-r--r--  1 currentuser  staff     1940 May  1 14:48 Icons_16@2x.png
-rw-r--r--  1 currentuser  staff     3286 May  1 14:48 Icons_16@3x.png
-rw-r--r--  1 currentuser  staff    24496 May  1 14:48 Icons_174.png
-rw-r--r--  1 currentuser  staff    89560 May  1 14:48 Icons_174@2x.png
-rw-r--r--  1 currentuser  staff   196272 May  1 14:48 Icons_174@3x.png
-rw-r--r--  1 currentuser  staff    31451 May  1 14:48 Icons_200.png
-rw-r--r--  1 currentuser  staff   116194 May  1 14:48 Icons_200@2x.png
-rw-r--r--  1 currentuser  staff   258471 May  1 14:48 Icons_200@3x.png
-rw-r--r--  1 currentuser  staff    49880 May  1 14:48 Icons_256.png
-rw-r--r--  1 currentuser  staff   188893 May  1 14:48 Icons_256@2x.png
-rw-r--r--  1 currentuser  staff   413327 May  1 14:48 Icons_256@3x.png
-rw-r--r--  1 currentuser  staff     1698 May  1 14:48 Icons_29.png
-rw-r--r--  1 currentuser  staff     4375 May  1 14:48 Icons_29@2x.png
-rw-r--r--  1 currentuser  staff     7835 May  1 14:48 Icons_29@3x.png
-rw-r--r--  1 currentuser  staff     1940 May  1 14:48 Icons_32.png
-rw-r--r--  1 currentuser  staff    75385 May  1 14:48 Icons_320.png
-rw-r--r--  1 currentuser  staff   292317 May  1 14:48 Icons_320@2x.png
-rw-r--r--  1 currentuser  staff   625811 May  1 14:48 Icons_320@3x.png
-rw-r--r--  1 currentuser  staff     5102 May  1 14:48 Icons_32@2x.png
-rw-r--r--  1 currentuser  staff     9225 May  1 14:48 Icons_32@3x.png
-rw-r--r--  1 currentuser  staff     2617 May  1 14:48 Icons_40.png
-rw-r--r--  1 currentuser  staff     6869 May  1 14:48 Icons_40@2x.png
-rw-r--r--  1 currentuser  staff    13008 May  1 14:48 Icons_40@3x.png
-rw-r--r--  1 currentuser  staff     3018 May  1 14:48 Icons_44.png
-rw-r--r--  1 currentuser  staff     7970 May  1 14:48 Icons_44@2x.png
-rw-r--r--  1 currentuser  staff    15270 May  1 14:48 Icons_44@3x.png
-rw-r--r--  1 currentuser  staff     3490 May  1 14:48 Icons_50.png
-rw-r--r--  1 currentuser  staff     9673 May  1 14:48 Icons_50@2x.png
-rw-r--r--  1 currentuser  staff    18942 May  1 14:48 Icons_50@3x.png
-rw-r--r--  1 currentuser  staff   188893 May  1 14:48 Icons_512.png
-rw-r--r--  1 currentuser  staff   584312 May  1 14:48 Icons_512@2x.png
-rw-r--r--  1 currentuser  staff  1399355 May  1 14:48 Icons_512@3x.png
-rw-r--r--  1 currentuser  staff     4267 May  1 14:48 Icons_57.png
-rw-r--r--  1 currentuser  staff    11909 May  1 14:48 Icons_57@2x.png
-rw-r--r--  1 currentuser  staff    23449 May  1 14:48 Icons_57@3x.png
-rw-r--r--  1 currentuser  staff     4517 May  1 14:48 Icons_60.png
-rw-r--r--  1 currentuser  staff    13008 May  1 14:48 Icons_60@2x.png
-rw-r--r--  1 currentuser  staff    26091 May  1 14:48 Icons_60@3x.png
-rw-r--r--  1 currentuser  staff     5696 May  1 14:48 Icons_70.png
-rw-r--r--  1 currentuser  staff    16863 May  1 14:48 Icons_70@2x.png
-rw-r--r--  1 currentuser  staff    34224 May  1 14:48 Icons_70@3x.png
-rw-r--r--  1 currentuser  staff     5973 May  1 14:48 Icons_72.png
-rw-r--r--  1 currentuser  staff    17615 May  1 14:48 Icons_72@2x.png
-rw-r--r--  1 currentuser  staff    36254 May  1 14:48 Icons_72@3x.png
-rw-r--r--  1 currentuser  staff     6508 May  1 14:48 Icons_76.png
-rw-r--r--  1 currentuser  staff    19402 May  1 14:48 Icons_76@2x.png
-rw-r--r--  1 currentuser  staff    39923 May  1 14:48 Icons_76@3x.png
-rw-r--r--  1 currentuser  staff      277 May  1 14:48 Icons_8.png
-rw-r--r--  1 currentuser  staff      780 May  1 14:48 Icons_8@2x.png
-rw-r--r--  1 currentuser  staff     1340 May  1 14:48 Icons_8@3x.png
-rw-r--r--  1 currentuser  staff     9225 May  1 14:48 Icons_96.png
-rw-r--r--  1 currentuser  staff    29173 May  1 14:48 Icons_96@2x.png
-rw-r--r--  1 currentuser  staff    61973 May  1 14:48 Icons_96@3x.png
iMac:test currentuser$ 
```

