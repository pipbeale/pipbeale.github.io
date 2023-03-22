---
layout: post
title: PVA 3D printing
---
After watching a bunch of videos of techniques used for making inflatables and soft robotics and chatting with my fellow Biohack Participant Anna who is a digital fabrication whizz, I decided I wanted to experiement with using PVA filament. My plan was to 3D print shapes that I could cover in silicone and then dissolve in water so that I would be left with a silicone tube/shape that I could inflate! I haven't seen anyone trying this technique (although I'm sure I'm not the first) so I am really curious how it will turn out! 

I also discovered that silicone is relatively permeable to oxygen which is relevant for my final project idea - more on that later! 

## 3D Models of test shapes

Firstly I decided on a selection of test shapes to print and drew them up in Autodesk Fusion 360. Because I am going for organic and vein-like shapes, I found I was often using the "create form" function or the "create pipe" functions in fusion. 

![name](/images/PVAtestdesigns.png) 

I made each shape with an extension that was 4mm in diameter to fit a one way valve and some tubing bought from an aquarium shop to test out my inflatables. 

![name](/images/PVAtest3Dmodel.png) 

The file for each shape needs to be exported as a .stl file so that it can be imported into a slicing software.

## Slicing the model

 The PVA filament that I had was for the Ultimaker 3D printer at the Waag so I imported the .stl file into the UltiMaker Cura slicing software that seems to be specific for this printer. 

In UltiMaker it is possible to select filament types however PVA was not an option and it requires a different temperature (it's written on the roll) for the extruder than other standard filaments like PLA. This meant I had to create a custom filament in Ultimaker, and when doing this it will override the default settings of the printer. The menu for this is in the "prepare" screen and you can give the custom filament a name and specify all sorts of things including tempteratures for the extruder and the plate, colour, cost etc. 

The roll I used had the following specs from Form Utura:
Diameter - 2.85mm
Material - AquaSolve PVA
Colour - Natural
Print Temp - 180-205 degrees C (I found 195 C to be best)

Note that the suggested print temperature is given as a range. At first I had the extruder set to 200C but the filament that had already been printed looked like a jelly as the next layer was being added and it was warping the shape. I dropped the temp to 190 and the filament didn't stick to the plate. In the end I settled on 195C and it seemed to be working pretty well although maybe a bit more tweaking will be required depending on the shape.

![name](/images/PVAtemptests.png) 

Put an SD card into your compy, dont forget (like I did) to tick for the software to add supports and then hit slice. Once it is done it'll ask you if you want to export the .gcode file to the external drive. Hit yes, and then hit eject drive! 

![name](/images/PVAtestslicer.png)

## 3D print

Next I prepared the printer by loading the PVA filament. The printer also didnt have a default setting for PVA so I just selected PLA (the settings for this get overwritten with what was chosen in the slicing software). Put in the SD card and select the file to print! 

![name](/images/PVAtestballs.png) 
![name](/images/PVAtestveins.png) 

Once it was done I peeled it off the plate, and then pulled off the skirt and supports. Curved surfaces in particilar were not perfectly smooth in my prints. Particularly where they were in contact with the supports. Luckily since PVA is water soluable I could wet a cloth and use it to smooth off the imperfections a little bit.

## Silicone coating

To test out coating in silicone I mixed equal parts of the two components of silicone (I will try to find which specific one it was) and used a paint brush to apply it to the surface of the prints. I stood the shapes up by poking them through the bottom of upsidedown paper cups which worked okkkk and the bottom of the cup caught the excess silicone that ran off. I also tried laying one down in a thicker pool of silicone. 

![name](/images/PVAtestsilicone.png) 

The instructions say to apply one layer and wait 40 mins before applying the next layer. So mostly they have two layers. The working time is 3 hours so I set them aside to cure overnight. 

In the end my layers were not thick enough so I will need to apply more coats of silicone. I Will also try applying it by dipping the object in rather than painting for a more even distribution.

![name](/images/PVAtestsiliconegroup.png) 

## Dissolving the PVA

I used a magnetic stirer with a heating element that we made in another week of the Biohack Academy to speed up the dissolving process. Regardless it was rather slow. The low surface area in contact with the water meant that by the end of the day it has only just started to get slimey on the end. Hower there a number of options to try to speed up the process including reducing the infill of the 3d print or changing the pattern of the infill so that the water can penetrate more easily. 

![name](/images/SiliconeTest1.mov) 

After the weekend it actually looked awesome! But the tube was not patent so it could not be inflated. But I really liked how it looked in the water. 


**bold**

[link to google](www.google.com)
