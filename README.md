# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:

## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
1. Create a New Sketch:
        Open autodesk fusion 360 on your computer. From the Design workspace, select the
Create Sketch option from the toolbar. The sketch environment will open with the available
construction planes.
<img width="237" height="482" alt="Screenshot 2026-11-13 210155" src="https://github.com/user-attachments/assets/15072c6b-42e8-416f-9d2f-b29eca4340bb" />

2. Select the Sketching Plane:
        Select the appropriate plane (XY, XZ, or YZ) according to the given drawing and project
requirements. The selected plane will become the working surface for creating the sketch.

3. Create the Basic Geometry:
        Use the sketching tools available in Fusion 360 to draw the required geometry. Tools such
as (Line, Circle, Arc, Rectangle, Polygon, and Point) can be used to construct the given sketch.

4. Make the fork slot:
1. Select the end face at the 52 mm body end and start a sketch.
2. Draw a centered rectangle for the slot: 16 mm wide × 16 mm high. Center it across the
32 mm body width and vertically through the body’s 32 mm thickness.
3. Use Extrude > Cut, through the full 52 mm body length, to split the body into two
prongs.
This leaves two 16 mm thick prongs around a 16 mm central gap.

5. Add the prong holes:
1. On an outer side face of a prong, start a sketch.
2. Place a Ø18 mm circle with its center 16 mm from the bottom edge and aligned with
the rounded end shown in the drawing.
3. Cut through both prongs. If Fusion does not cut both with one feature, use Through All
with both prongs selected.
The drawing indicates the hole center is at the rounded end of the fork. It does not give a
separate center-to-end dimension, so align it with the end profile shown rather than assigning
an unsupported dimension.

6. Add the stem:
1. Select the opposite end face of the body and sketch a Ø18 mm circle centered on the
body.
2. Extrude it outward 32 mm. This gives an overall length of 84 mm (52 + 32).

7. Round the fork end:
       The front view shows a rounded outer end around the hole. Add a 16 mm radius rounding to
the outer end of each prong, centered on the Ø18 hole axis. Use a sketch/profile cut or Fusion’s
Fillet where the geometry allows it.

8. Check against the drawing
Confirm the main dimensions:
● Body: 52 × 32 × 32 mm
● Fork slot: 16 mm
● Prong holes: Ø18 mm
● Stem: Ø18 mm × 32 mm
● Overall length: 84 mm
● Hole center height: 16 mm from the bottom
The drawing does not fully dimension the slot’s position along the body or the stem’s exact
position across the width. The steps above assume the fork slot runs through the body length
and the stem is centered on the far end face.
<img width="311" height="417" alt="Screenshot 2026-11-13 210611" src="https://github.com/user-attachments/assets/8397f1de-8fa4-49cf-bd44-d1841c225866" />

9. Finish the Sketch:
       Check the final drawing for correct geometry, dimensions, view arrangement, and ISO
standard representation, select Finish Sketch. Make any necessary corrections before finalizing
the drawing. This exits the sketching environment and saves the completed 2D sketch within the
Fusion 360 design.
<img width="364" height="173" alt="Screenshot 2026-11-09 171520" src="https://github.com/user-attachments/assets/59d041d6-c128-4e94-a219-102bf061ec49" />

10. Save the Final Project:
      Check the completed 2D sketch against the given reference drawing. Save the Fusion 360
design with an appropriate project name. Ensure that the dimensions, symmetrical profile and
central cutout match the required design . Save the completed Fusion 360 design and drawing
file with the appropriate project name.

## INPUT:
![image](https://user-images.githubusercontent.com/113594316/198551872-276f8b80-bea8-4d4a-b2e8-bfdcd1e9d3cc.png)

## OUTPUT:
<img width="992" height="715" alt="Screenshot 2026-11-10 152015" src="https://github.com/user-attachments/assets/c694af51-f2af-4ebc-ab5f-59f3ee042ccd" />

## RESULT:
Thus, 3D model is created from orthographic projection.
