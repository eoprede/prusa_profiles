# Slic3r profiles for Prusa i3 MK3

### MK3 Pretty PETG Profile
Profile by Chris Warkocki

Even though I'm swamped with work I've had to reprint some parts lately and put together a nice PETG profile for parts that doubles as a nice pretty PETG profile.

Feel free to adjust the infill as I'm having a kick using gyroid but all in all this is just a nice simple PETG profile that should give you good results fo general prints and parts for upgrades.

Created in and for Slic3r 1.40.0 Beta for the MK3 but this will work just fine on a MK2.5 and MK2s.
### MK3 Pretty PLA Profile
Profile by Chris Warkocki

The best things comes in threes. So we have a nice new PETG profile for slic3r, a speed PLA profile, but it's time to take everything I learned from my last profile that I did wrong and redo it and finalize it a bit.

I got some great feedback and went back to the drawing board and viola we have a preset made for pretty prints using PLA. This will work on the MK3 only.

I've zoned the speeds as best as possible to reduce motor resonance as well as other printing artifacts.

Enjoy and don't forget to keep on printing.

### MK3 Speed PLA Profile
Profile by Chris Warkocki

Some people want to print fast but still have a decent print. I've played with this over the course of the last three weeks and a few dozen random or so prints and I think it's ready.

These speeds are more in the MK3 realm so I wouldn't use this for the MK2s or MK2.5 but if someone wants to test them please let me know if they work on them.

Best with Slic3r 1.40.0 beta and above.

### Chris MK3 PLA V3
Profile by Chris Warkocki

I'm way slower than normal but it's time for an official update to the Slic3r 1.40 alpha 1 profile from me. This is very specific and targeted directly at those with issues of uneven extrusion on the MK3. After 3 weeks and lots of brainstorming I've taken a lot of input from smart people and tweaked the living poop out of it. I'm happy to say that initial prints on various MK3's show improvement to the extrusion issue.

### pp_tpu_config
Profile by Paul Park

slic3r PE for my mk3. Been working great, use at your own risk.

I would do the e-correct tower in PLA and change the e-correct (if needed) first.

And always use glue or something (baby powder, windex, etc) with TPU. I use glue.

For me each filament even from the same brand requires a specific temperature. Some need extrusion multiplier of 0.9 or 0.95. I use sainsmart.

### MK3 3Dxtech Matte Petg
Profile by Chris Warkocki

3dxtech just sent some sample Pretty Ridiculous Ultra Super Awesome Orange matte petg my way for testing. P.R.U.S.A. Orange is a near perfect match to the old ABS parts and prints like a dream as usual with every petg they sell.

I've been messing with settings and have it locked down by increasing the print temps and doing some flexing here and there

### Pretty Vase Mode
Profile by Chris Warkocki

Been working on a version of the PETG profile I've been working on specifically for printing in Vase Mode. Using large extrusions to make a nice strong vase but it's fully customizable down to 0.10mm layer heights this should be a good starting point for those looking to make some cool vases.

So why PETG? The layers just bond so much better than PLA so you won't have to worry about this this busting if you give it a good squeeze.

Getting it water tight is another story but I promise it shouldn't leak out the walls but most likely out the bottom. Adjust your perimeter overlap and extrusion multiplier till you don't get anymore leaks.

Make sure you adjust the layer height based on the intricacies of the model. at the stock 0.30mm layer height objects like the Easter Island head will have gaps so make sure to spend time looking at the layer visualizer as well making sure you don't print over a 45 degree angle. Single walls are near impossible to get harsh angles.

### MK3 Pretty PETG V2
Profile by Chris Warkocki

I couldn't just post post a PLA profile so here is the update PETG profile. This one is a little faster than the last one but still gives really nice results. Again, no ooze while mesh leveling and the special purge bubble in the beginning to prime the nozzle just right for PETG. Happy printing!

### MK3 Pretty PLA V2
Profile by Chris Warkocki

The latest and greatest release of Slic3r PE has finally hit. I've been waiting for a couple bug fixes before launching an all new profile and it just dropped an hour ago. Welcome to Slic3r PE 1.41.0 BETA. 

A few refinements and adjustments based on the all new jerk and acceleration menu as well as refinements to the start and end gcode. Goodbye blobs on the bed. Have fun and happy printing.

### NylonX
NylonX Slic3r profile by Evan Lloyd

### Hollow and spiral vase
Profiles by Fedor Pikus

Here are my profiles for water-tight vases. I started with Chris Warkocki Pretty PLA profile and modified the settings needed to make it water-tight. Basically, over-extrude a ton: make the lines wider and crank up the extrusion modifier. The hardest part is the transition from the bottom to the wall. The settings I have will do the job on most filaments and vases, at the cost of some ugliness where the infill is visible through the outside wall. If the vase is very wavy right from the bottom, then even this much overlap may not be enough. There are settings for 0.4 and 0.6mm nozzles (1.0mm nozzle works great, but I thought I'd post the more common ones). I have both spiral vase settings and regular hollow vase (no infill, 2 perimeters). Adjust the temperatures for your PLA material.