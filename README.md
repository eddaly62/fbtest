fbtest.c
----------
This program queries the display's frame buffer and displays the attributes to the console.

To run:
sudo ./fbtest [path to frame buffer]
sudo ./fbtest /dev/fp0

Note: to avoid the sudo thing...you can add yourself to the video group.

sudo adduser dell video

adds the user dell to video group
The frame buffers belongs to the video group
You only need to do this once.