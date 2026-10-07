---
title: Folding Drone
github: Folding-drone
description: A drone built without a kit which folds in on itself!
created_at: 07-09-2026
total_time: "..."
---
## 7th September, 2026: Humble Beginnings

First we had to do a little research. Scouring the web for how to build a drone, so I booted up a 
canva portfolio and started splashing information. I condensed it into readable sections and diagrams. Considered forces,
materials, etc, a photo shows what exactly.
Then we went to town on part research and budgeting, also shown on the slide.

<img width="446" height="250" alt="image" src="https://github.com/user-attachments/assets/77a92c7c-f1e0-4583-a0ab-d925c6a06c2b" />
<img width="451" height="252" alt="image" src="https://github.com/user-attachments/assets/e6d8adfb-faea-48cb-a6cf-8b8d4313fed0" />


**Total time spent: 1.5h**


## September 12th, 2026: Parts and Printing

Got some serious CAD work done on a basic shape for the drone, no folding parts yet, just spacing and a basic
drone shape. Printed a basic prototype of the base out of PLA to test strength. For the real deal I will consider using 
CF-PETG or another carbon fibre mix of filament for higher tensile strength (need to prepare for inevitable crashes).
Got to be optimising for strength vs weight so I cut out some unnecessary filament in the arms and cut out some fill 
whilst printing.

<img width="244" height="124" alt="image" src="https://github.com/user-attachments/assets/01afc97a-307a-46a3-8575-b112cf47dad4" />
<img width="1242" height="2208" alt="image" src="https://github.com/user-attachments/assets/5a2dd320-c8bb-48cc-8b7e-992e37952ed5" />


**Total time spent: 4.5h**


## September 15th, 2026: Flight controller considerations!

I just found a page on hackclub which goes in detail into how to create a flight controller from scratch, and although
I have never touched electronics in the past, thats not the sort of obstacle which will stop me. Started reading today
whilst sketching a diagram of how the electronics connect (very crude).
Not confident on all the inner electronic workings yet but I will keep going.

<img width="1440" height="1920" alt="image" src="https://github.com/user-attachments/assets/c8325756-24ec-4861-8e6e-b04e5d228442" />

**Total time spent: 5.5h**


## September 20th, 2026: Flight controller work.

Created a new folder in my github repository to work on the FCB, I am considering whether to go ahead with this plan or not, 
but I have imported libraries and code from the guide into my files. One such file converts LCSC component codes into a format used by KiCad which I
will be using for the FCB project. 
I have decided to keep the FCB project for another day. I will go ahead with the drone with a distributed flight controller, although after I finish this project I might try to remake a model with my own FCB. 
I will not log these hours as they did not contribute to the project.
I will not log these hours as it did not contribute to the overall project.

## September 25th, 2026: Connecting electronics in a Diagram

The whole point of having a raspberry Pi in my design is to automate some processes which cannot be coded into the FCB.
Others have used the rpi to assess images or send gps tracking to an app, but I will attempt to use it to code automatic take-off and 
landing sequences.
I have connected electronics to each other in "FPV drone builder" so I can visualise how I will solder them together in future, and to show others my
diagrams (I have never done this before and it is much simpler than I imagined with helpful guides linked to components as PDFs)
I have also begun work on finding a way to fold the drone. I considered an external hinge, but realised an internal hinge would be more compact, and could be 3D printed as one print if well designed.

<img width="333" height="292" alt="image" src="https://github.com/user-attachments/assets/ac52124f-6011-408b-88a1-74189148f9b9" />

**Total time spent: 6.5h**


## October 7th, 2026: Connecting electronics in a Diagram

I have begun to model the hinge for the centre of the drone. I had to consider the height of different components to allow space between them (the drone will fold upwards as it acts as protection for the components). I will have to fashion a locking mechanism of some sort aswell.
When I designed the arms of the drone, I made them detatchable so every time I printed a new base, only parts which had changed needed to be reprinted.

I have modelled the hinge and implemented it into the design, as well as finding STEP files of electrical components to insert as sub assemblies into the project to show scale and how everything fits.
<img width="1920" height="1440" alt="image" src="https://github.com/user-attachments/assets/aaafcde7-4a44-4547-a086-4a5ae50b2265" />
<img width="1440" height="1920" alt="image" src="https://github.com/user-attachments/assets/68c5ca62-805b-40c3-b418-2af5c74d050c" />
<img width="1920" height="1440" alt="image" src="https://github.com/user-attachments/assets/35098bc6-cb67-4721-bdbe-a8b7a8c9ab5a" />

**Total time spent: 8h**


