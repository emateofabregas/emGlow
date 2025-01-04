![emGlow_Cover](https://github.com/user-attachments/assets/5994e88b-3618-4e13-bd43-adcedaabdfbf)

**emGlow 1.9** is an exponential glow with advanced knobs for Nuke. You can control which AOV want to affect, how many samples _(max 11)_ you want to use, anamorph deform, intensity, tint, size, falloff, tolerance with clamping, and highlights clamping.

![emGlow_Knobs_9](https://github.com/user-attachments/assets/bb6e9e41-2ba8-4a90-ba7a-68729497c6c7)

A mask input allows you to connect your specific mask only to affect an area in your image. 'The Overscan' feature is available with the crop for more control in your bounding box and a checkbox for cropping the image.

![emGlow_gizmo9](https://github.com/user-attachments/assets/2b22a414-4b1a-49f6-a950-7137a3af119d)

**UPDATES in version 1.9**
- Simplified the falloff(pow) operation in the glow effect and made it pow of 2 falloff a knob (same algorithm to exposure f-stop). 
- Added a label following the channels knob.

**UPDATES in version 1.8**
- You can adjust a specific AOV (no need for it to be rgba/beauty) and after will merge it with the rest: e.g. make the Glow effect in RGBA_key and after the merge with the rest and the effect only is in this AOV.
- Some knob names are modified to make them more attractive, e.g., 'View Glow' for 'Glow Only.'
- Split the 'falloff' knob to min and max values.
- Made more readers the highlight knob and highlight checkbox too.
- Moved black & white clamp knobs on the bottom. Those knobs affect the values before the effect, which is just for the image. 
