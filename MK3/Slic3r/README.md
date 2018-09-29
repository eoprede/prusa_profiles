# Slic3r profiles for Prusa i3 MK3

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
Updated August 16, 2018  
Profile by Chris Warkocki

Pretty PETG V3. Just fixed a couple things with bridging I didn't like in the V2. Will work on the MK2, MK2s, and the MK3 for certain.

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