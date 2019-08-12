
# **Hello reader!**

This is my GPlates repository. Here I will post my ~~always right~~ rotation files, poligons and paleogepgraphy files ready to use and modify (**especially modify**).

In general terms I try to comment as much as possible every rotation, but sometimes you will find some ~~ridiculous~~ not easy to understand comment. If that is the case, probably you are facing some self-joke about the reconstruction, do not hesitate if you do not know why and where the rotation is coming from (*probably my imagination*).

## What is a rotation file
A GPlates rotation file (.rot or .grot) is a file that includes the finite rotations of each Gplate feature (polygon, line, plate, terrane... any geological feature you may want to reconstruct) at different times. The file is separated by columns and contains the following information:

*FeatureID:* a number that describes every feature. It is a good policy always comment every number so people can easily get the rot file

*Time:* when the described finite rotation applies, in million years ago

*Latitude of Euler Pole*

*Longitude of Euler Pole*

*Angle of roation*

*Fixed Plate:* Plate relative to which the rotation applies

*Comments:* Followed by !, they are not read by GPlates but are crucial to a human understanding of the file

They look like this

>235 10 0 0 0 236 !A-B collision
>
>235 15 35 22 10 236 !A-B subduction initiation, closure of Ocean C 
>
>235 20 35 22 20 236 !A-B are faaaaar away 

[TUTORIAL](http://www.earthbyte.org/Resources/GPlates_tutorials/All_Tutorials/GPlates_Rotations1_Tutorial.html)
