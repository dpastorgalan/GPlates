
# **Hello reader!**

This is my GPlates repository. Here I will post my ~~always right~~ rotation files, poligons and paleogepgraphy files ready to use and modify (**especially modify**).

In general terms I try to comment as much as possible every rotation, but sometimes you will find some ~~ridiculous~~ not easy to understand comment. If that is the case, probably you are facing some self-joke about the reconstruction, do not hesitate if you do not know why and where the rotation is coming from (*probably my imagination*).

## What is a rotation file
A GPlates rotation file (.rot or .grot) is a file that includes the finite rotations of each Gplate feature (polygon, line, plate, terrane... any geological feature you may want to reconstruct) at different times. The file contains the following information:



FeatureID | Time (in million years ago) | Latitude of Euler Pole | Longitude of Euler Pole | Angle of roation | Fixed Plate | Comments

And it looks like this

5 10 0 0 0 6 !A-B not sepparated
5 15 35 22 10 6 !A-B sepparated


[TUTORIAL](http://www.earthbyte.org/Resources/GPlates_tutorials/All_Tutorials/GPlates_Rotations1_Tutorial.html)
