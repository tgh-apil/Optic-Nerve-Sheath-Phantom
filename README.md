# Optic-Nerve-Sheath-Phantom
A transorbital ultrasonographic optic nerve sheath training phantom based on a model designed by Dr. Zakir Hajat, Dr. Michael Dinsmore, and Dr. Lashmi Venkatraghavan.

This model is based on the pre-existing transorbital ultrasonographic optic nerve sheath phantom described in a [2020 paper by Hajat et al.](https://doi.org/10.1097/ana.0000000000000592), and was developed alongside Dr. Michael Dinsmore for the dual purposes of improving the realism of the training phantom by providing a human face-shaped case in which to house the inner components of the phantom (i.e. the eye and optic nerve sheath) and of increasing its longevity by replacing the gelatine and psyllium fiber with ballistics gel. It also replaces difficult to access components (namely the pediatric microcuffed endotracheal tube) with silicone components that are relatively easy to manufacture. This phantom is intended for training in the measurement of optic nerve sheath diameter through noninvasive ultrasonography.

<img src="https://github.com/tgh-apil/Optic-Nerve-Sheath-Phantom/blob/main/images/ONS1.JPG"> <img src="https://github.com/tgh-apil/Optic-Nerve-Sheath-Phantom/blob/main/images/ONS2.JPG"> 

Note: The headform model was modified from NIOSH National Personal Protective Technology Laboratory (NPPTL)’s medium size ISO Digital Headform: https://www.cdc.gov/niosh/npptl/topics/respirators/headforms/default.html

This model was developed at the Lynn & Arnold Irwin Advanced Perioperative Imaging Lab, Toronto General Hospital, University Health Network.

## Parts, Materials & Equipment
### Printed Parts List
The files for these parts can be found in the [*/stl files/*](stl%20files) directory.

*/stl files/intermediate molds/* — for silicone casting of intermediate mold
* ONSl_intmold_1.stl
* ONSl_intmold_2.stl
* ONSr_intmold_1.stl
* ONSr_intmold_2.stl

*/stl files/sheath molds/* — for silicone casting of nerve sheath
* ONS_sheathmold_4_5mm_1.stl
* ONS_sheathmold_4_5mm_2.stl
* ONS_sheathmold_5_5mm_1.stl
* ONS_sheathmold_5_5mm_2.stl
* ONS_sheathmold_6_5mm_1.stl
* ONS_sheathmold_6_5mm_2.stl

*/stl files/case/* — for housing eye and nerve sheath in ballistics gel
* ONSl_case.stl
* ONSr_case.stl

*/stl files/other/* 
* ONS_ramp.stl

### Hardware
* 8 x M4 8mm screws
* Table tennis balls (40mm in diameter)
* Super glue
* Magnets (3mm OD), 6 per head (i.e. 3 per half head)

### Printing
* PLA (polylactic acid) filament
* Fused Deposition Modelling 3D printer

### Casting
* [Smooth-On’s Mold Star 20T Silicone Rubber](https://www.smooth-on.com/products/mold-star-20t/) (or another silicone of similar hardness) 
* Hot glue gun
* 5mL syringe
* [Clear Ballistics - 10% Ballistics Gel](https://www.clearballistics.com/product/10-ballistics-gel)
* [Humimic Medical - Medical Ballistics Gel #5](https://humimic.com/product/gelatin-5-medical-gel-by-the-pound/) 
* Slow cooker
* Heat gun

## Assembly Instructions
### Intermediate Mold Silicone Casting
<img src="images/silicone%20casting_intermediate%20mold%20components.png" width="400"> <img src="images/silicone%20casting_intermediate%20mold%20setup.JPG" width="400"> 

1. Print all components in */stl files/intermediate molds*.
2. Assemble parts 1 and 2 together using 4 x M4 12mm screws per side. Use a hot glue gun to seal the seams between the two components to ensure silicone does not leak out.
3. Mix a total of 1250mL of silicone according to manufacturer instructions.
   - Note: if working with a silicone with a short pot life (such as Mold Star 20T), degassing is not recommended.
4. Pour silicone into the assembled mold and allow to cure according to manufacturer instructions.
5. Once cured, disassemble the mold and remove part 1 of the mold (i.e. the face positive). Part 2 should remain attached to the silicone to provide structural support.
   - Note: there may be a small air bubble beside the eye portion of the mold, but this can be filled by applying a small additional amount of silicone into the cavity and placing it back into the mold to cure a second time.

### Eye and Nerve Sheath Silicone Casting
<img src="images/silicone casting_eye nerve sheath components.png" width="600">

*Nerve sheath*
1. Print the mold components in */stl files/sheath molds/* corresponding to the desired sheath diameter. Ex: a file with the 5_5mm suffix will correspond to a sheath diameter of 5.5mm.
   - Note: filing may be needed to ensure parts 1 and 2 fit together neatly.
2. Assemble parts 1 and 2 together using hot glue.
3. Mix a total of 5mL of silicone according to manufacturer instructions. A fast-drying silicone (such as Mold Star 20T) is recommended.
4. Inject into mold using syringe. 
   - Note: air bubbles may result in the finished product. Though these do not typically affect the ultrasound image, they can be removed by tipping the mold upside down, which causes the air bubbles to rise to the top. The amount of silicone injected is in excess of the volume of the mold, thus allowing for a long sheath to be produced even as some silicone leaks out of the upside down mold as it cures.
5. Allow silicone to cure according to manufacturer instructions. Once cured, remove hot glue and open mold. Trim the sides of the sheath and cut to length (roughly 10 cm is adequate), ensuring one end is as flat as possible for attaching to eye.

*Eye*
1. Cut a table tennis ball in half, creating two hemispheres.
2. Mix a total of 20mL of silicone according to manufacturer instructions. A fast-drying and sturdy silicone (such as Mold Star 20T) is recommended. It is also recommended to use the same silicone as for the sheath.
3. Pour into a table tennis ball hemisphere, ensuring all of the inside surface is coated with silicone.
4. Tip upside down and place on a broad grate or similar such that the silicone can pour out of the hemisphere.
5. Allow silicone to cure according to manufacturer instructions. Once cured, the silicone should have formed a thin, smooth skin in the shape of the inside of the table tennis ball. Remove carefully and trim any excess dripping off the sides.

*Connecting the two*
1. Clamp or hang the nerve sheath in place above the upturned “eye” such that the end of the sheath touches the top of the “eye”. 
   - Note: placing the eye on top of a table tennis ball hemisphere or another 4 cm diameter ball will help it to retain its shape, making the connection process easier.
2. Mix a small amount of silicone according to manufacturer instructions (2mL total is adequate). It is recommended to use the same silicone as for the sheath and eye.
3. Carefully dab silicone onto the end of the sheath, then place it on top of the eye and smooth out any excess silicone around the point of connection.
4. Allow silicone to cure according to manufacturer instructions. Once cured, the two components should be connected into one.

## Ballistics Gel Casting & Head Assembly
**CAUTION:** Use appropriate heat-proof gloves when working with liquefied ballistic gel and/or heat gun.<br>**CAUTION:** work only in a very well ventilated area. A fume hood is highly recommended.

<img src="images/BG casting_components.png" width="400"> <img src="images/BG casting_setup.JPG" width="400"> 

1. Melt at least 125 g 10% gel and 125 g Humimic #5 gel (a total of 250 g) in a slow cooker at 105C - 115C (approx. 225F - 240F).
2. Print the case components (*/stl files/case/*) as well as the tilting ramp (*/stl files/other/*).
3. Place the case into the corresponding intermediate silicone mold so that the outside of the case is flush with the silicone. Clamp into position. 
   - Note: in order to prevent deformation of the case under high temperatures, it may be helpful to place a thin plastic or wood plate between the case and the clamp, covering the thinnest wall of the case.
4. Place the case and mold onto the tilting ramp so that the flat side of the case is slightly elevated. This will help ensure the eye and nerve sheath are properly oriented.
5. Pour ballistics gel into the case until the silicone in the window is just covered and allow to cool.
6. Place the eye-nerve sheath into something that will allow the eye to hold its shape (for example, a ping pong ball hemisphere with a hole large enough to accommodate the sheath). Pour ballistics gel into the eye until full and allow to cool. Once cool remove the eye-nerve sheath and trim any excess silicone around the top so that the gel is slightly concave. This will help prevent air bubbles when placing the eye into the case.
7. Use a heat gun to gently melt the surface of the gel in both the case and the eye, then place the eye into the case. See the figure below for approximate placement. The melted surfaces allow for a few seconds of mobility during which it is possible to correct the position of the eye and to compress out any air bubbles. Position the nerve sheath so that it is straight and vertical.
   - <img src="images/BG casting_eye positioning.png" width="400">
   - Note: the presence of air bubbles does not necessarily render the phantom unusable so long as they are not in the centre of the eye where they will block the nerve sheath during ultrasound. If this occurs, remove the eye-nerve sheath and its gel, and repeat steps 6 and 7.
8. Once cooled, pour enough ballistics gel into the case to cover the nerve sheath to a depth of roughly 5 centimetres. Allow to cool again.
9. Once cooled, unclamp and remove the case from the mold. Trim the nerve sheath so that it does not stick out beyond the case. Use a heat gun to gently heat the surface of the ballistics gel in the case to smooth out the texture imparted to it by the silicone mold.

## Final Assembly
1. Use a ⅛-inch drill bit to tap the pre-printed magnet holes in the case.
2. Apply a small amount of super glue into a hole and insert a 3mm magnet. Do the same for all holes, taking care to ensure the opposing magnets in each case half do not repel one another.
