# Touuch-slide-keyboard
This is an attempt to create a cheap version of SeaBoard, monofonic, slide, capacitive touch version.
It uses a custom PCB of my design, which might have to be changed.
As this is capacitive touch keyboard, it is prone to statics, and electromagtetic fields of any sort.
Adding a ground plain might help, or perhaps adding a metalic case.
It supports Hairless-midiserial and a 5-pin MIDI din.
Depending on chosen connection type, serial speed has to be adjusted in the code.
This is based on CH340G ATmega2560-16AU board which is inexpencive and has lots of IO pins.
