# Touch-slide-keyboard
<img width="701" alt="Screenshot 2025-04-22 at 12 50 08 PM" src="https://github.com/user-attachments/assets/4065d466-c905-4f54-a05c-2a25b9534410" />

<img width="696" alt="Screenshot 2025-04-22 at 4 04 23 PM" src="https://github.com/user-attachments/assets/923b9770-6675-46e0-9069-eded0ac1653d" />

This is an attempt to create a cheap version of SeaBoard, monofonic, slide, glide, capacitive touch version.
It has 24 notes / 2 octaves.
It is mostly intended for playing virtual instruments of ethnic kind, where slides and glides are the main characteristics of sound.

It uses a custom PCB of my design, which might have to be changed.
As this is capacitive touch keyboard, it is prone to interference of statics and electromagtetic fields of any sort.
Adding a ground plain might help, or perhaps adding a metalic case.

It supports Hairless-midiserial and a MIDI TRS (5-pin MIDI din could be soldered by free wires as well).

Depending on chosen connection type, serial speed has to be adjusted in the code.

This is based on CH340G ATmega2560-16AU board which is inexpencive and has lots of IO pins.

PCB_NEW_PCB_2025-04-22.json is an EasyEDA PCB file. 
Also attaching an archive with gerber files. But be aware, that this is a project in progress, so before orderring PCBs, you have to be aware that currently some notes false trigger due to environment and electromagnetic fields of many kinds. 
Keyboard's sensitivity also depends on other things, like:
1. Computer connected to wall outlet vs disconnected from wall outlet.
2. Proximity of devices that emit electromagnetic field.
3. Proximity of large metallic objects.
4. Wearing rubber slippers also makes a difference in sensitivity. :)
5. Playing on metal table will not work. Playing on a table with metal railings is not a good idea as well, as those metal poles would act as antennas.

From my experience, the easiest way to upload an *.ino file is to use Arduino IDE.
   

This project is free to use for non commercial purposes.

https://www.youtube.com/watch?v=N2WDr5IA7VM


https://www.youtube.com/watch?v=tIamUhcm8pE


If you ever try to improve the PCB design, please drop me a line and a PCB design file, I'd love to see what you've done.
sinitsinmike@yahoo.com


