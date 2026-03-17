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

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/32e16109-f9df-4014-8d49-13a9cb204f07"/>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/a8f6d0e5-24ad-4fe7-bac5-cac53aaf494b"/>

  Inspired by Martin Donald’s Hotspot Texturing example, I wanted to try the approach myself. I created a small Houdini asset that takes a mesh as input and either unwraps it automatically based on surface angles or allows the use of a handmade unwrap.

  The asset provides options to define the UV and mesh size and calculates a score based on size and aspect ratio, with adjustable weighting to control which factor is more important. The trim texture is supplied by the user along with a cut plane. The sections of the texture plane are also scored, and the tool then finds the best match between the UV score and the mesh score.

  The UVs are placed into the corresponding trim area and scaled to fit either uniformly or along a single axis. Afterwards, the unwrapped mesh can be used directly in-engine together with the texture.

  This tool allows a large number of objects to be unwrapped and textured in very little time and works especially well in sci-fi settings due to its focus on hard-surface modeling.

  <br clear="all">
</div>

<div>
  <h3> 🔫 PCG - Magazine:</h3>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/3d2f5b2a-0016-4220-b525-3c071b24872c"/>

  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/d6ee8bee-d9a4-4b13-a037-41ea51970b74"/>
  I wanted to create a tool for fast and easy editing of an asset with multiple variations. Because I really enjoy shooters, the first idea that came to my mind was a magazine generator that creates magazines with different sizes and shapes.

The tool handles the entire pipeline, including high-poly to low-poly baking and UV unwrapping. Combined with procedural materials in Substance Designer, it is possible to create a wide range of interesting variations.

The finished assets are best suited for third-person games that require a large amount of variation. Since the assets are generated procedurally, they can lack a bit of uniqueness compared to fully hand-crafted models.
  <img align="left" width="300"
       src="https://github.com/user-attachments/assets/c79f7dce-8564-4e0c-9dc2-4a329833f4f3"/>


  <br clear="all">
</div>


 <h3> 🐀 VFX - Rats:</h3>
  <img align="right" width="500"
       src="https://github.com/user-attachments/assets/68123a63-06a4-4ba9-9120-59381a408e4c"/>
  A really small evening project where recreated the shader animation from "torch in sky"(Unity) in Unreal with Niagara and a Material where I animated the vertex offsets. The main idea is to have a lot of animated creatures on screen without the need of skeletal meshes to save performance.
  </br>
First I made the whole rat model go up and down with a sine wave. Then, by using math, I split the Rat into 3 seperate regions. The front legs, the back legs and the tail. The Legs got extra movement in the facing direction of the rat and an offset between the front and back legs. The tail uses the same up and down wave from the whole body just a bit more powerful to put some emphasize on it.
The <a href="https://sketchfab.com/3d-models/rat-801d26d47ebf41baa17055287a82da08"> rat model/textures </a> are from sketchfab, but I needed to add a 2nd UV channel for the shader, so its possible to seperate parts. The same is possible with vertex color but a UV is easier to understand and use in this case.
  <img align="left" width="1000"
       src="https://github.com/user-attachments/assets/7bfc03fd-22bb-43d6-9f15-488f9dc20e17"/>


  <br clear="all">
</div>
