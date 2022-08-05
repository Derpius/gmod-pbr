# GMod PBR Textures  
PBR textures for GMod and other mountable game materials.  
Originally made for [GModDXR](https://github.com/Derpius/gmod-dxr) but is now repurposed for VisTrace.  

All MRAO textures are in the format R - Metalness, G - Roughness, B - Ambient Occlusion.  
For ease of loading these are the name of the diffuse texture with `_mrao` appended.  

Emission maps store the colour of the emission at a point, with black being no emission.  
These have the name of the diffuse texture plus the suffix `_emission`.  

Normal maps are currently not planned, but I may work on them after a large batch of MRAOs are done.  

Additionally, transmission maps will have the suffix `_transmission`.  

## Including into a GMod addon
Add the `vtf` branch as a submodule (or just clone it) to your addon's `materials` directory.  

## Showcase  
**With MRAO Textures**  
![With MRAO](https://github.com/Derpius/gmod-dxr-pbr/blob/master/Screenshots/example%20with.png?raw=true)  

**Without MRAO Textures**  
![Without MRAO](https://github.com/Derpius/gmod-dxr-pbr/blob/master/Screenshots/example%20without.png?raw=true)  
