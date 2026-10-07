# Laser Cutting

**Specifications:** 
- Epilog Laser Fusion M2
- Inkscape v1.4.2
- Epilog Dashboard 2.2.18.0

# Preparing Workshop

1. Turn fume exhaust `ON`

2. Turn air compressor `ON`

3. Turn laser cutter `ON`

# Focusing the Laser 

Focusing the laser will vary with which material you are using. **Focusing** is required to ensure the laser is cutting at the correct width/focus. 

1. Load in your material

2. Navigate to `Jog` on the laser's console 

3. Use the joystick to move the laser to an acccessible area

4. Use the metal triangular focusing jig to mount it on the laser's frontend

5. Navigate to `Focus` on the laser's console

6. Ue the joystick to carefully lower the jig so that it touches the surface of the material

    - Once touching the material, tap the jig's top
    
    - If there is any loose give, the jig is too close to the material. Move it back up. 
    
    - Once the jig has no give when tapping it at its top, and it is securely touching the material, it is configured correctly
    
7. Remove the jig, close the top lid, and prepare your files

# Preparing Files 
- .DXG format
- Preferred units are **inches** or **millimeters**

## Inkscape
1. Import file into new Inkscape document
    
    a) **Method of Scaling:** `Read from file`
    
2. Make adjustments to **Fill and Stroke** in the Properties panel

    a) **Stroke Style:**
    
    **Width:** Change `mm`/`in` to `Hairline`
    
    b) **Stroke paint**
    
    *By default, with an object selected, should turn `red` once this setting is selected. Verify stroke lines are red.*
    
    *Adding multiple stroke colors to the file is used when scoring or engraving is needed*
    
3. Ensure the dimensions are accurate 

4. Print to `Epilog Engraver` with default settings

## Epilog Dashboard 

1. Open Epilog Dashboard (should open by default)

2. Import material settings in the rightmost side panel. *This icon is a folder with a downward arrow...*

3. Only configure `Speed`, `Power`, and `Frequency`  if absolutely necessary. These parameters should already be set by the material settings, so adjust them only in special cases

4. `Vector Sorting` can be changed to `Inside-Out` if the shape is complex

5. `Cycles` can be changed to `2` or `3` depending on the material and shape

6. Select `Print` for an immediate print, or `Send to JM` if 

# Laser cutting

1. Navigate to `Job` on the laser console, verify the displayed print job time.

2. Press `GO` once ready

3. Allow fumes to exhaust and keep lid `CLOSED`, especially for longer prints and prints with toxic materials (*ie. Plastics*)

# Safety 


## Fires
- If a fire starts at the laser's printhead, monitor the fire and ensure it is contained to the head only. If the head moves away from the fire, and the fire persists, stop the print **immediately** by opening the laser's lid. 

- The laser will automatically stop if the lid is open. Grab the nearby safety glove and place it over the fire. Use an extinguisher if needed beyond this point.
