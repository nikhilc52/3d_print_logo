# Turning Logos into 3D-Printable Objects

## Image Manipulation

- Upscale the image using this [AI tool](https://www.upscale.media/upload). Only do this is the image is a low-res, non-SVG.
- Convert the image to an SVG using this [Adobe tool](https://www.adobe.com/express/feature/image/convert/svg). Only do this is the image is a non-SVG.

## Blender

- Open the SVG in [Blender](https://www.blender.org/download/) (File -> Import -> SVG)
- Zoom to the any one of the curves imported (~ + 3)
- Select all the curves, then join them together (Ctrl+J)
- Convert the object to a mesh (Object -> Convert -> Mesh)
- Select all edges and extrude upwards (Tab -> 2 -> A -> E)
- Set origin to geometry (Right click -> Set Origin -> Origin to Geometry)
- Scale up (S)
- Add a plane (Shift+A -> Mesh -> Plane)
- Scale up in the X and Y to align with image (S / S -> X / S -> Y)
- Position the plane right under the SVG object (G -> Z)
- Extrude the plane to add depth (Tab -> 3 -> E -> Z)
- Export as STL (File -> Export -> STL)

**You can now import the STL in a 3D printing software, and edit characteristics accordingly.**

## Sample Logos

3D Printed PICSciE Logo:

<img src="PICSCIE LOGO/PICSCIE-3D.png" alt="3D Printed PICSciE Logo" width="200"/>

3D Printed Princeton Research Computing Logo:

<img src="PRC LOGO/PRC-3D.png" alt="3D Printed Princeton Research Computing Logo" width="200"/>
