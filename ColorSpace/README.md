# ColorSpace

## Description

Asset to certify that colors are multiplied in the correct linear color space.

For any material there are always two colors that are multiplied:

- BaseColorFactor * BaseColorTexture
- BaseColorFactor * Vertex Colors
- Vertex Colors * BaseColorTexture

The colors are crafted in a way that they are not gray (have a color), but when multiplied correctly in linear space result in a perfect mid-grey.

There are variants for PBR Metallic/Roughness and Unlit shaders.

## License Information

(C) 2022, Andreas Atteneder. CC-BY 4.0 International https://creativecommons.org/licenses/by/4.0/. 
