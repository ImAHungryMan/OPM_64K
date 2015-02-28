KSP Integration configs for the OuterPlanets Mod by Cpt. Robau and Eudae55 and 64K by Paul Kingtiger, Raptor831 and Regex.

//These configs deviate in some aspects from the regular 64K, should that be unwanted,
using the RealSolarSystem.cfg from 64K *should* work with this, provided you delete the entry for Eeloo. 

RSS/64K:
-The RealSolarSystem.cfg file is based off the 24h version; the 12h patch should work nonetheless.
-The Mun now has a heightmap, I have not the slightest idea if that helps with anything! 
-Minmus is now only 3.2x of it's stock size, its orbit remains at 6.4x
-Gilly and Bop have stock sizes, Bop's orbit remains at 6.4x
-Gilly's orbit is at 3.2x of its stock size, since the view is more enjoyable this way :3
-Eeloo now orbits Sarnus.
-RSS .obj files for Minmus, Gilly and Bop are included, this is important for ScaledSpace.

OPM:
-All OPM bodies with the exception of Hale have had their radii and semi major axes increased by 6.4x. Hale had its radius increased by only 3.2x to allow for a SOI outside of its surface, though it still is pretty darn small. If you want to increase it for easier encounters, hit up ctrl+p, select Hale under “Planet Selection”, click “Load Data”, and refocus, the SOI should then be at 59km. No, there is no other way :p
-All atmospheric OPM planets with the exception of Sarnus had their atmospheric heights and scaleheights multiplied by 1.32. 
-The gas giants have the densities of Saturn, Uranus and Neptune with according masses. 
-Hale has a density that should approach somewhat realistic areas, Ovok has its density (but not its size) modeled on Methone. Slate has kept its geeASL value, preserving its Tylosan resemblance; and, lastly, Tekto now has Titan's density.
-Played a little with the terrain on slate and hale, no guarantees about it being an improvement.
-Kittopia/Kopernicus .bin files are included, again, important for ScaledSpace.
-Provided blank overwrite files for solar power curve, this is being handled by 64K.
-Changed OPM's RT patch to multiply the base range from the two largest RT dishes by 3; 64K modifies them another time to give them their final range.

AVP/EVE
//While AVP:Interstellar v2 does work just fine with 64K for the most part, there are a few things that do not play together well, so I tried to resolve those as best as I could. 
-Fixed surface glow layer on the Mun being too low and removed the “Halos” around some of Jool's moons, as well as the cloud layer above Pol.
-Toned down lightning on all planets a lot, removed it from Duna, added it to Tekto. As a side effect, the lightning is a lot dimmer. This is hardly ideal, but I have no idea how to get around that as of now. 
-Clouds work out of the box on the gas giants, made atmospheric haze work there too. Failed to achieve acceptable results with the Haze around most of the terrestrial planets, so I left that untouched.
-Tekto's clouds work reasonably well fortunately, however I getting the atmospheric haze right will require someone more skilled with EVE than me.

