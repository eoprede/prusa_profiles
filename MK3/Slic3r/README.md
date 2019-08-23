# Slic3r profiles for Prusa i3 MK3

- [Slic3r profiles for Prusa i3 MK3](#slic3r-profiles-for-prusa-i3-mk3)
    + [MK3 Speed PLA Profile](#mk3-speed-pla-profile)
    + [pp_tpu_config](#pp-tpu-config)
    + [MK3 3Dxtech Matte Petg](#mk3-3dxtech-matte-petg)
    + [Pretty Vase Mode](#pretty-vase-mode)
    + [NylonX](#nylonx)
    + [Hollow and spiral vase](#hollow-and-spiral-vase)
    + [Pretty PETG V3](#pretty-petg-v3)
    + [Pretty PLA V3](#pretty-pla-v3)
    + [Pretty Litho PETG](#pretty-litho-petg)
    + [Pretty Litho PLA](#pretty-litho-pla)
    + [MMU Pretty PLA V1.2](#mmu-pretty-pla-v1-2)
    + [Pretty CF PETG](#pretty-cf-petg)
    + [Palette Plus Pretty PLA](#palette-plus-pretty-pla)

### MK3 Speed PLA Profile
Updated May 5, 2018  
Profile by Chris Warkocki

Some people want to print fast but still have a decent print. I've played with this over the course of the last three weeks and a few dozen random or so prints and I think it's ready.

These speeds are more in the MK3 realm so I wouldn't use this for the MK2s or MK2.5 but if someone wants to test them please let me know if they work on them.

Best with Slic3r 1.40.0 beta and above.

### pp_tpu_config
Updated May 5, 2018  
Profile by Paul Park

slic3r PE for my mk3. Been working great, use at your own risk.

I would do the e-correct tower in PLA and change the e-correct (if needed) first.

And always use glue or something (baby powder, windex, etc) with TPU. I use glue.

For me each filament even from the same brand requires a specific temperature. Some need extrusion multiplier of 0.9 or 0.95. I use sainsmart.

### MK3 3Dxtech Matte Petg
Updated June 6, 2018  
Profile by Chris Warkocki

3dxtech just sent some sample Pretty Ridiculous Ultra Super Awesome Orange matte petg my way for testing. P.R.U.S.A. Orange is a near perfect match to the old ABS parts and prints like a dream as usual with every petg they sell.

I've been messing with settings and have it locked down by increasing the print temps and doing some flexing here and there

### Pretty Vase Mode
Updated July 12, 2018  
Profile by Chris Warkocki

Been working on a version of the PETG profile I've been working on specifically for printing in Vase Mode. Using large extrusions to make a nice strong vase but it's fully customizable down to 0.10mm layer heights this should be a good starting point for those looking to make some cool vases.

So why PETG? The layers just bond so much better than PLA so you won't have to worry about this this busting if you give it a good squeeze.

Getting it water tight is another story but I promise it shouldn't leak out the walls but most likely out the bottom. Adjust your perimeter overlap and extrusion multiplier till you don't get anymore leaks.

Make sure you adjust the layer height based on the intricacies of the model. at the stock 0.30mm layer height objects like the Easter Island head will have gaps so make sure to spend time looking at the layer visualizer as well making sure you don't print over a 45 degree angle. Single walls are near impossible to get harsh angles.

### NylonX
Updated August 14, 2018  
NylonX Slic3r profile by Evan Lloyd

### Hollow and spiral vase
Updated August 14, 2018  
Profiles by Fedor Pikus

Here are my profiles for water-tight vases. I started with Chris Warkocki Pretty PLA profile and modified the settings needed to make it water-tight. Basically, over-extrude a ton: make the lines wider and crank up the extrusion modifier. The hardest part is the transition from the bottom to the wall. The settings I have will do the job on most filaments and vases, at the cost of some ugliness where the infill is visible through the outside wall. If the vase is very wavy right from the bottom, then even this much overlap may not be enough. There are settings for 0.4 and 0.6mm nozzles (1.0mm nozzle works great, but I thought I'd post the more common ones). I have both spiral vase settings and regular hollow vase (no infill, 2 perimeters). Adjust the temperatures for your PLA material.

### Pretty PETG V3
Updated August 23, 2019  
Profile by Chris Warkocki

Pretty PLA for the year 2019 is here. This profile is specifically for the Prusa MK2s/2.5/2.5s/3/3s printers running stock firmware aka Linear Advance 1.0

But what is it???

Pretty PLA was the groundwork of tons of smart people who all had issues when the MK3 launched. The original profiles in Slic3r:PE were a bit over the top with screaming 200-300mm/s print moves and overall the print quality was less than desirable.

Hundreds of hours went into testing the perfect speeds to reduce certain artifacts the MK3 had more so than other printers like it and even new tests designed by myself like the speed towers and resonance tests all went in to find the best values for an overall safe profile that jammed less, printed a little better, and had the newest advancements. It was a profile of many comprises to not only print well but print it fast enough that it wouldn't take forever for a print to finish.

Heck those advancements inspired all the new Prusa quality profiles that took the framework the community put in and it finally made Prusa Slicer easier for the beginner.

In tradition there are new things here that aren't in other profiles.

1. improved preheating. Some users said that a small hole would form from heating the nozzle close to the bed which was used to prevent oozing. Fixed it by rising the nozzle to 0.6mm off the bed saving it from possible harm. Now you can enjoy running bed calibrations without oozing on the bed and without possibly hurting smooth PEI.

2. vastly improved supports. Let's face it. The stock supports tend to fall over or not work too well for most prints. After much testing in finding a sturdy support structure that also easily comes off the print was tough but it's getting there and it's here in this profile. I will follow up with a small guide to show you how to adjust supports for more detailed prints or prints that just don't need sturdy supports so stay tuned for that.
3. more tweaks. After thousands of hours per months in prints and looking at user feedback more small adjustments were made and hopefully this means a better overall safe profile for everyone that wants to balance good quality and ease of printing.

Note that you don't need to adjust anything besides layer height between 0.15mm-0.25mm. Just change the layer height and it'll work just fine.

### Pretty PLA V3
Updated August 16, 2018  
Profile by Chris Warkocki

Profiles time! I fixed the missing z hop necessary in the Pretty PLA profile so enjoy the refined and fixed version right here right now. It will work for certain on the MK2, MK2s, and the MK3. Nothing crazy in there and is just a nice simple profile with many many refinements.

### Pretty Litho PETG
Updated September 19, 2018
Profile by Chris Warkocki

For those looking for a starting point in printing Lithophanes I've sat down and tweaked the PETG profile a bit and did some maths and viola. I nice simple MK2s-MK3 Litho profile.

I decided on PETG since it's the superior material for this.

1. Better bed adhesion.
2. Less chance at warping if placed near a window or warm lamp light.
3. Less warping during printing.
4. Less curling than PLA.
5. Needs less cooling than PLA so difficult prints have room for more cooling.
6. Less brittle.

I use this site for making lithophanes: http://3dp.rocks/lithophane/

Feel free to test away and happy printing!

### Pretty Litho PLA
Updated September 19, 2018
Profile by Chris Warkocki

For those who don't want to venture into PETG I ran a quick test and the stock settings worked for PLA so here is a starting point for a PLA lithograph profile.

It doesn't have as much testing but the images are nearly identical and the quality is just right.

Enjoy and happy printing!

### MMU Pretty PLA V1.2
Updated September 30, 2018
Profile by Chris Warkocki

For those using the MMU2 I'm posting this profile to help alleviate a few things.

1. Included the start gcode for no mess mesh bed leveling.
2. Lower extruder acceleration as it would cause skipping. 8000 to 5000 and may try lower.
3. Increased Extruder jerk to help with tip creation. 1.5 to 2.
4. Lowered retraction speeds and increased retraction amount before wipe and the distanced needed in a move before taking a retraction. Stock settings left fine hairs of strings. Almost gone now.
5. Loading Speed at Start changed from 3 to 19. By PJR. The load speed at start was too low and would cause grinding of filament as it was mismatched with the stock bondtech load speed.
6. Loading Speed changed from 14 to 22. By PJR. If the tip is slightly out of spec lower would cause it to stop at bondtech instead of going through. You may hear a click in the extruder as it forces the filament tip into the bondtech.
7. Way Better Output filename format. 
8. Adjusted first layer line width as it was too thin IMO. 0.40 to 0.45.
9. Speed reduction to infill and solid infill. 200mm/s is too fast for some PLA so it's been reduced to a safer 120mm/2.
10. Seam position changed to aligned for better prints.
11. Bridging detection enabled so supports don't go covering the bridges.

*new*

12. Increased initial unload speed to 120mm/s to match next step
13. Increased cooling moves from 1 to 2 in order to shape the tip better. Seems to improve too thick of tip that was causing jams on entry to Festo.

So far this is working just great. No more filament grinding and the values are much more printer friendly in some areas. If your'e having issues with your MMU2 printing give this a try and let me know.

### Pretty CF PETG
Updated October 5, 2018
Profile by Chris Warkocki

I know a lot of people want to play with CF PETG so here is a really decent CF PETG profile.

It's not perfect and I've noticed different brands need different tweaks to retraction settings so print something to test and hone in those retractions before doing a huge important print.

this is a good starting point and works with both 3dxtech CF PETG and Matterhackers CF PETG but needs some adjustments depending on your setup.

For those using a hardened steel nozzle bump the print temps up 10C and for those using an Olsson Ruby leave the temp alone unless you get bad layer adhesion.

Good luck and happy printing!

### Palette Plus Pretty PLA
Updated October 5, 2018
Profile by Chris Warkocki

For those thinking of grabbing a Palette Plus on the cheap once the Palette 2 hits the market here is you Slic3r PE Pretty Palette Profile.

Tested and the palette can keep up.

Prusament btw needs a 3.2 heat and 3.5 compression factor. Fillamentum works fine with stock 2/2.