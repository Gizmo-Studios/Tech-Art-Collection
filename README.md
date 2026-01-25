# 🛠️ Tech Art Collection

Collection on different small procedural assets and other tech art realted projects

## 🎯 Skills & Software
- `Houdini`
- `PCG`

## 🗝️ Key Aspects
- Creation of tools to reduce the time needed for repetitive tasks
- Rapid iteration and adjustments to react to changes
- Procediral content generation for assets


## 🚩 Personal & Design Goals
Scince I saw a GDC Talk from Sea of Thieves a few years back I am really interested in **Tech Art** and **Procedural Content Generation**. Planning and writing tools gives me a certain kind of pleasure, like solving a puzzle. All pieces falling into the right place and with one button press I can create awsome assets or change something on the fly.

<div>
  <h3> 🧱 Hotspot Texturing:</h3>

  <img align="right" width="400"
       src="https://github.com/user-attachments/assets/32e16109-f9df-4014-8d49-13a9cb204f07"/>

  <img align="right" width="400"
       src="https://github.com/user-attachments/assets/a8f6d0e5-24ad-4fe7-bac5-cac53aaf494b"/>

  Inspired by Martin Donald’s Hotspot Texturing example, I wanted to try the approach myself. I created a small Houdini asset that takes a mesh as input and either unwraps it automatically based on surface angles or allows the use of a handmade unwrap.

  The asset provides options to define the UV and mesh size and calculates a score based on size and aspect ratio, with adjustable weighting to control which factor is more important. The trim texture is supplied by the user along with a cut plane. The sections of the texture plane are also scored, and the tool then finds the best match between the UV score and the mesh score.

  The UVs are placed into the corresponding trim area and scaled to fit either uniformly or along a single axis. Afterwards, the unwrapped mesh can be used directly in-engine together with the texture.

  This tool allows a large number of objects to be unwrapped and textured in very little time and works especially well in sci-fi settings due to its focus on hard-surface modeling.

  <br clear="all">
</div>

<div>
  <h3> 🔫 PCG - Magazine:</h3>

  <img align="right" width="400"
       src="https://github.com/user-attachments/assets/3d2f5b2a-0016-4220-b525-3c071b24872c"/>

  <img align="right" width="400"
       src="https://github.com/user-attachments/assets/d6ee8bee-d9a4-4b13-a037-41ea51970b74"/>
  I wanted to create a tool for fast and easy editing of an asset that has variation. Because I really enjoy shooters, the first thing that came to my mind was a magazine generator to create different magazines that vary in size and shape. The tool handles everything including the baking process of highpoly and lowpoly and the unwrapping. Together with procedural materials in substance designer it is possible to create interesting variation. The finished assets are most likely better suited for a third person game that needs a lot of variation, because just with procedural generation they are missing a bit of uniqueness.
  <img align="left" width="300"
       src="https://github.com/user-attachments/assets/c79f7dce-8564-4e0c-9dc2-4a329833f4f3"/>


  <br clear="all">
</div>
