# HoWL-3-Audio-Patcher
HoWL-3 for the Hogs of War league has missing sound issues. This is a small build that patches the broken sectors in the image through a "Donor image". 
Not fully tested but seems to work fine

Instructions:

Real simple like. We just use HoWL-1 to repair HoWL-3's missing Subheader Submodes based on Directory diffing and traversal, file matching/positioning, and Form type

1) Grab your HoWL-1.bin and your broken HoWL-3.bin and place them into the same folder;

2) Then you can either:

- a) Double click exe
- b) Drag HoWL-3.bin into exe
- c) Run exe from cmd/shell with HoWL-3.bin as your argument

3) wait till is done

4) rename the new HoWL-3_PATCHED.bin to just HoWL-3.bin and put it back in the correct netplay folder
	(doesnt write to original file just incase you forgot to back it up)

5) ????

6) enjoy


Hacked this release together running it on only two machines so if it doesn't run for you. Please let me know what error you're getting. Probably some annoying dependancy I just need to bundle in there
