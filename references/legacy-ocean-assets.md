# Legacy ocean asset construction notes

Use this note only when a source contains ocean, lake, waves, or a large water surface. The goal is not to copy a specific copyrighted asset; it is to reproduce the cheap construction logic of early 3ds Max and Maya scene assets.

## Historical construction evidence

- Autodesk's 3ds Max Design 2011 tutorial constructs an ocean from a plane and deforms or shades that plane: https://download.autodesk.com/us/3dsmaxdesign/2011/help/files/WS1a9193826455f5ff-e569a012180ce58913129.htm
- ScriptSpot's Ocean Plane script, first submitted in 2011, creates a primitive ocean plane fitted to the camera perspective and uses a displacement map: https://www.scriptspot.com/3ds-max/scripts/ocean-plane
- TurboSquid's 2012 Procedural Ocean asset for 3ds Max 2010 and V-Ray reports only 30 polygons and 30 vertices: https://www.turbosquid.com/FullPreview/666615
- TurboSquid's older 3ds Max 9 and Mental Ray sea asset reports a 240-polygon animated plane: https://www.turbosquid.com/3d-models/3d-model-photo-realistic-sea/500138

Do not download or redistribute an asset unless its license is explicit and compatible. Use these pages as construction and era references when licensing is unclear.

## Cow Come ocean recipe

1. Fit one large plane to the current camera and horizon. A second intersecting plane is allowed only when needed to fake a foreground breaker.
2. Apply one dull blue-green base-color image with obvious repetition, long perspective stretching, and uneven texel scale.
3. Suggest waves with crude low-frequency displacement or painted or fake bump. Keep the true silhouette and mesh simple.
4. Represent foam as two to five pale gray or dirty-white flat ribbons or cards with jagged cut edges. Let them float, intersect, or stop abruptly.
5. Use a single flat horizon card. Distant ships may be tiny dark blocks.
6. Lock metalness, specular, reflection, clearcoat, transmission, and emission to 0 and roughness to 1. There is no water reflection, wet highlight, transparency, refraction, or subsurface color.
7. Give the ocean only weak self-shading from the same camera-relative upper-front-left default light used by every scene. Disable cast and received shadows; foam cards and railings must not darken the water.

Reject modern stylized water bands, clean graphic wave icons, physically simulated water, glossy game water, realistic spray, caustics, cinematic mist, and richly colored tropical oceans.
