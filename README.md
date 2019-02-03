# SDJ-Midi Mappings
Collection of Information about Midi Mapping and Example Midi Mappings for Serato DJ Pro

## Rane Seventy-Two Mappings
A small collection of mappings for the Rane seventy-two mixer. Each mapping is available as a single file, several mappings can be combined if needed. 

### Quick Auto Loop
Parameter Knobs (Manual: Knob 18 for L/R Decks) are sending a midi signal if not used for FX parameter control. They can be mapped and will work as midi knob in track view mode but not in FX control mode. The mapping works like the auto loop encoder on the DDJ SP1. Left / right rotation decreases / increases auto loop length, push will enable / disable auto loop.

With the firmware 1.3 Rane adds the auto loop function to this knob as build-in feature. No midi mapping required anymore.

### Hot Loop
With the DDJ SP1 Shift + Hot Cue would enable Hot Loop. It triggers a Cue and enables an Auto Loop with the currently set Loop length.
This mapping mimics the Hot Loop mode. It is activated using Shift + Cue Mode.

Remark: Currently in Beta. Issues: 1) Output lighting is not correct. 2) Instead of all pads trigger loop on, they trigger loop toggle. 

### Beat Jump
Similar to the manual tone play this mapping triggers two midi events. Instead of having two buttons for controlling the length of the jump and two buttons for performing the jump the first row is dedicated to jump backward and the second row to jump forward. The divisions are 4 beats, 2 beats, 1 beat, 1/2 beat from left to right.


# SDJ Midi Mapping Info

## Midi Input

## Midi Output

### Colors

Color   |  Values
--------|---------:
Blue    |  1 to 10
Green   | 20 to 29
Yellow  | 30 to 39
Orange  | 40 to 49
Pink    |       50
Purple  |      120
Yellow  |      100
Red     |  106 116
Green   |       80
