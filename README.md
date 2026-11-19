# Ex.No.-1.2-Design and Draft the given 2D Sketches in modelling software.

## AIM
 To sketch the given drawing with dimensions using fusion 360 tool.
 
## REQUIREMENTS
 1. Autodesk fusion 360
 2. Windows 10
 3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
 4. 2.5 Mbps or faster download; 500 Kbps or faster upload 
 
 ## PROCEDURE
Step 1: Set Up Reference Axes & Base Grid

1. Draw primary vertical and horizontal centerline axes intersecting at the origin (0,0).

2. Offset the main vertical centerline to the left and right by 50mm to establish parallel centerlines at x = - 50 and x = 50

3. Offset the main horizontal centerline up and down by 60mm to establish horizontal lines at y = 60 and y = - 60

4. Mark the 6 outer hole centers:

***Top-left:** (- 50,60)

***Top-right:**(50,60)

***Middle-left:** (-70, 0) (offset 20mm further left from x = - 50 )

***Middle-right:** (70,0) (offset 20mm further right from x = 50 )

***Bottom-left:** (-50, 60)

***Bottom-right:** (50,- 60)

<img width="764" height="632" alt="{01C3E792-2714-40E6-A9FD-D65F049DED65}" src="https://github.com/user-attachments/assets/5227175e-5b89-4f36-9de2-9d8aedc4d536" />

 Step 2: Draw Central Geometry

1. From center origin (0,0):

Draw the innermost circle with radius "R16**.

* Draw concentric reference circles with radii **R21**, **R32**, and **R40".

2. Construct the central web pattern:

Draw vertical parallel offset lines at x = 3 (total gap width 6mm) through the center.

Construct 6 radial slots/spokes within the annular region between **R21** and **R32**.
<img width="757" height="633" alt="{BC3CBCC4-1A75-4625-A813-0D2EA20B286B}" src="https://github.com/user-attachments/assets/965ff1da-a8aa-4290-8a73-eacf0dda2dbb" />

Step 3: Construct Outer Circular Features

1. **Hole Circles:** Draw circles of radius **R15** at all 6 outer center points.

2. **Outer Bosses:**

*At top-left (-50, 60), top-right (50, 60), bottom-left (50, 60), and bottom-right (50, 60), draw outer arcs of radius **R21**.

* At middle-left (-70, 0) and middle-right (70, 0), draw outer concentric circles of radius

R20**

Step 4: Connect Tangent Lines & Fillets

1. "Outer Straight Tangents:** Draw straight line segments tangent to the outer arcs

connecting:

* Top-left arc (R21) to middle-left arc (R20).

* Bottom-left arc (R21) to middle-left arc (R20).

* Top-right arc (R21) to middle-right arc (R20).

* Bottom-right arc (R21) to middle-right arc (R20).

2. **Top & Bottom Inner Fillets:**

* Create internal tangent fillets of radius **R20** connecting the top-left arc (R21) and top-right arc (R21), resting smoothly against the central **R40** boundary.

* Create identical **R20** internal fillets at the bottom connecting the bottom-left arc (R21) and bottom-right arc (R21).

  <img width="754" height="533" alt="{5667ACF2-7C22-49C4-A6FC-FA24531EFBFA}" src="https://github.com/user-attachments/assets/97d8882e-6489-4031-beaa-746a3fce35e4" />

Step 5: Final Cleanup & Dimensioning

1. Trim all overlapping construction geometry to leave a clean outer boundary and inner features.

2. Apply centerlines, dimensions, hatch/shading, and radius annotations matching the technical drawing.

 ## OUTPUT
<img width="737" height="536" alt="{CE8E35AB-9D06-4B27-9125-9D6CE039B50B}" src="https://github.com/user-attachments/assets/c6b80f8e-67a5-427d-86cc-325334073104" />
 <img width="743" height="580" alt="{ED92E7EC-767B-4096-8EF7-D6BC3DC6355B}" src="https://github.com/user-attachments/assets/1d431081-226c-468a-a738-2fdd5e68574a" />

 
 ## RESULT
 Thus the given sketch is drawn and drafted using fusion 360 tool.
