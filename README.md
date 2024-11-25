![emGlow_Cover](https://github.com/user-attachments/assets/5994e88b-3618-4e13-bd43-adcedaabdfbf)

**emGlow 1.8** is an exponential glow with advanced knobs for Nuke. You can control which AOV want to affect, how many samples _(max 11)_ you want to use, anamorph deform, intensity, tint, size, falloff, tolerance with clamping, and highlights clamping.

![emGlow_Knobs_8](https://github.com/user-attachments/assets/f405463e-1978-4529-8852-54d4c7671970)

There is a Mask input that you can connect your specific mask to only affect an area in your image. 'The Overscan' feature is available with the crop for more control in your bounding box and a checkbox for cropping the image.

![emGlow_gizmo](https://github.com/user-attachments/assets/9e6e8bfe-5bf3-4ad5-9224-50cd76003462)

**NEW UPDATES in version 1.8**
- You can adjust a specific AOV (no need for it to be rgba/beauty) and after will merge it with the rest: eg. make the Glow effect in RGBA_key and after the merge with the rest and the effect only is in this AOV.
- Some knob names are modified to make them more attractive, eg: 'View Glow' for 'Glow Only'.
- Split the 'falloff' knob to min and max values.
- Made more readers the highlight knob and highlight checkbox too.
- Moved black & white clamp knobs on the bottom. Those knobs affect the values before the effect, which is just for the image. 
