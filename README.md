# Optic-Nerve-Sheath-Phantom
A transorbital ultrasonographic optic nerve sheath training phantom based on a model designed by Hajat et al., 2020.

This model is based on a pre-existing transorbital ultrasonographic optic nerve sheath phantom—as described in [Hajat et al.’s 2020 paper](https://doi.org/10.1097/ana.0000000000000592)—and was developed alongside Dr. Michael Dinsmore, one of the authors of the paper. Its purpose is to improve the realism of the training phantom by providing a human face-shaped case in which to house the inner components of the phantom (i.e. the eye and optic nerve sheath), as well as to increase its longevity by replacing the gelatine and psyllium fiber with ballistics gel and graphite powder. Both versions of the model were created to provide training in the measurement of optic nerve sheath diameter through noninvasive ultrasonography. 

See documentation below.

> <img src="https://user-images.githubusercontent.com/84343976/197030848-43b08540-394d-4c30-8dc5-13ba37bbb042.png" width="360"><img src="https://user-images.githubusercontent.com/84343976/197030843-c0162b87-7cb7-47b7-b321-6ef388256fa0.png" width="410">

## Parts, Materials & Equipment
### Printed Parts
The files for these parts can be found in the CAD Files folder of this repository.

Left Side
* left bottom.stl/3mf * — portion of case that houses the eye and optic nerve sheath
* left lid.stl — lid for back of case
* left top.stl — top/forehead component of case
* left mold 1.stl — part 1 of mold
* left mold 2.stl — part 2 of mold

Right Side
* right bottom.stl/3mf * — portion of case that houses the eye and optic nerve sheath
* right lid.stl — lid for back of case
* right top.stl — top/forehead component of case
* right mold 1.stl — part 1 of mold
* right mold 2.stl — part 2 of mold

\* Use high temperature PLA or another heat resistant filament for components that will be in contact with molten ballistics gel (left bottom.stl and right bottom.stl). Any filament can be used for the rest of the components (PLA was used in this case).

### Materials
* High temperature PLA
* Optional other filament
* Smooth-On’s Dragon Skin 30 Silicone Rubber (or another silicone of similar hardness)
* 24G IV catheter
* Microcuff endotracheal tube (ETT)
* Ping pong balls
* Humimic Medical - Medical Ballistics Gel #4
* Graphite powder
* Super glue

### Equipment
* 3D printer (a Prusa i3 MK3 printer was used here)
* Crock pot
* 3mL syringe

## Assembly Instructions
### Mold
1. 3D print both mold components using any kind of filament. Screwing them together is optional but helps to prevent leakages when casting.
2. Spray inside of mold with mold release agent and cast with relatively rigid silicone rubber. Smooth-On's Dragon Skin 30 was used here.
3. Remove from mold when cured. There may be a small air bubble beside the eye portion of the mold, but this can be filled by applying a small additional amount of silicone into the cavity and placing it back into the mold to cure a second time.

> <img src="https://user-images.githubusercontent.com/84343976/197574596-6c672661-83ca-46ce-a8bf-ec4a8ce5119b.png" width="420"><img src="https://user-images.githubusercontent.com/84343976/197574604-9c1e3dca-c90b-4a78-aa17-e25aff4d80e0.png" width="410">

### Case
1. 3D print bottom, top**, and lid*** components. Only the bottom component requires high temperature PLA filament. <b>Note that there are issues with the bottom component file; it is only printable in one orientation, which is already saved in the .3mf file. Fixing it with PrusaSlicer's Netfabb service is not recommended.</b>

\** The top and bottom components will be glued together eventually, however since the mold fits around the bottom component, the gluing step must occur after the ballistics gel casting is complete.

\*** The lid is optional, however it is recommended as it keeps the tubes suspended in the gel steady. The lid can be attached to the bottom component in a variety of ways; magnets were used here. Holes were drilled into both components and small magnets were glued into each hole using super glue.

### Eye & Nerve Sheath
1. Make two cuts through the microcuff tube (see Figure 1): one at Cut A, just below the cuff (though be sure not to cut the lip of the cuff that extends over the tube), so that the end is flat, and the other at Cut B (be sure not to cut through the smaller tube). 
2. Cut a ping pong ball in half and glue the convex side to Cut A, just below the cuff.
3. Deair the larger tube and cap it. The deairing process was conducted by sucking the air out of the tube with a syringe, using that same syringe to fill the tube with water, inserting a thin wire to force air bubbles stuck at the bottom of the tube out, and repeating until full of water. It was then capped by applying super glue to the inside of the cap and then capping the tube at Cut B.
4. Make a third cut at Cut C (Figure 1) and insert the 24g catheter into the thinner tube. Once inserted, remove the needle and attach a 3 mL syringe to the catheter (Figure 2).
5. Deair the microcuff by pulling the air out of the cuff and tube using the syringe, and then filling it with water. Repeat until no air bubbles remain. The syringe should be filled with roughly 3 mL of water when the microcuff is deflated.

> <img src="https://user-images.githubusercontent.com/84343976/197026624-09e508db-1a30-4af5-8329-20203ecf0eb2.png" width="600"><br>
> Figure 1. Locations of cuts A, B, and C on the microcuff ETT. 
  
> <img src="https://user-images.githubusercontent.com/84343976/197026622-13779993-5ac5-418f-9a6a-7b0e1be8fc4e.png" width="550"><br>
> Figure 2. The final eye and optic nerve sheath configuration.

### Casting
1. Melt some #4 ballistics gel (roughly a third of a pound was used per phantom) at 200-250F. Once melted, stir in graphite powder until fully integrated.
2. Hold the ETT configuration upright so that the ping pong ball is open to the ceiling and fill it with ballistics gel. Allow to cool completely to prevent air bubbles from forming against the ping pong ball.
3. Place the 3D printed bottom case into the silicone mold. Clamp in place to ensure a snug fit, preventing leaks. Fill with enough ballisics gel to cover the bottom of the mold. While still warm and pliable, deflate the microcuff and place the ETT configuration ping pong ball-side down into the mold, aligning the curve of the tube so that it sticks out above the semi circle in the bottom component. This will keep the edges of the ping pong ball from sticking out of the gel, while also ensuring the ETT stays close enough to the surface for a high quality scan. Keep the syringe out of the gel; it can be rested along the top of the mold/bottom component.
4. Once cool, remove the bottom component from the mold and conduct a test scan to ensure there were no air bubbles or other issues. If satisfactory, use super glue to join the top and bottom components, and place the lid on the back of the phantom.
