```{note}
This page is under construction.
```

# Pearloid
![alt text](../_static/media/pearloid_banner.png)

Pearloid is a type of synthetic material (celluloid plastic) designed to mimic the appearance of mother of pearl. It’s often used in making musical instruments and decorative items, to give a lustrous iridescent finish.

## Inputs

### Base

#### Color
Specifies the base color.
<figure>
  <img src="../_static/media/pearloid/base/color/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Variation of base colors</figcaption>
</figure>


#### Roughness
Controls the roughness of the base layer.
<figure>
  <img src="../_static/media/pearloid/base/roughness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Roughness from 0.0 to 1.0</figcaption>
</figure>


#### Transmission Weight
Controls the Transmission Weight of the base layer.
<figure>
  <img src="../_static/media/pearloid/base/transmission_weight/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Transmission Weight from 0.0 to 1.0</figcaption>
</figure>

#### IOR
Controls the Index of Refraction of the base layer.
<figure>
  <img src="../_static/media/pearloid/base/ior/strip.png" alt="my alt text"/>
  <figcaption text-align="center">IOR from 1.0 to 4.0</figcaption>
</figure>

### Flakes

#### Weight
This multiplier scales the reflection intensity received by the celluloid flakes.
<figure>
  <img src="../_static/media/pearloid/flake/weight/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Weight from 0.0 to 1.0</figcaption>
</figure>

#### Density
Controls the density of the celluloid flakes.
<figure>
  <img src="../_static/media/pearloid/flake/density/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Density from 0.0 to 1.0</figcaption>
</figure>

#### Tint
Sets the color of the flakes tint in the paint.
<figure>
  <img src="../_static/media/pearloid/flake/tint/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Variation of flake tints</figcaption>
</figure>

#### Scale
Adjusts the size of the flakes.
<figure>
  <img src="../_static/media/pearloid/flake/scale/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Scale from 3.0 to 60.0</figcaption>
</figure>

#### Randomness
The randomness of the flake shape.
<figure>
  <img src="../_static/media/pearloid/flake/randomness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Randomness from 0.0 to 1.0</figcaption>
</figure>

#### Grain Scale

<figure>
  <img src="../_static/media/pearloid/flake/grain_scale/strip.png" alt="my alt text"/>
  <figcaption text-align="center"></figcaption>
</figure>

#### Roughness
Specifies the roughness of the flakes.
<figure>
  <img src="../_static/media/pearloid/flake/roughness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Roughness from 0.0 to 1.0</figcaption>
</figure>

#### Absorption
Specifies the degree of light absorbed by the pigment before it is reflected off the flakes. 
<figure>
  <img src="../_static/media/pearloid/flake/absorption/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Absorption from 0.0 to 2.0<</figcaption>
</figure>

#### Seed

### Flake Depth

#### Intensity
Controls the intensity of the depth seperation between flakes. At 0.0, all flakes have the same depth. At 1.0, flakes will have a large difference in depth. 
<figure>
  <img src="../_static/media/pearloid/flake/depth_intensity/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Depth Intensity from 0.0 to 1.0</figcaption>
</figure>

#### Threshold
Controls the depth at which flakes start to appear.
<figure>
  <img src="../_static/media/pearloid/flake/depth_threshold/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Depth Threshold from 0.0 to 1.0</figcaption>
</figure>

### Flake Normal

#### Distance
Multiplier for the height value to control the overall distance.
<figure>
  <img src="../_static/media/pearloid/flake/normal_distance/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Normal Distance from 0.0 to 0.64</figcaption>
</figure>

#### Roughness
Controls the normal map roughness. 
<figure>
  <img src="../_static/media/pearloid/flake/normal_roughness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Normal Distance from 0.0 to 1.0</figcaption>
</figure>

#### Variation
This parameter determines the extent to which flake orientation deviates from the surface normal. A value of 0.0 means minimal deviation, aligning flakes closely with the surface. Higher values intensify the flake effect, making it more pronounced.
<figure>
  <img src="../_static/media/pearloid/flake/normal_variation/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Normal Variation from 0.0 to 0.2</figcaption>
</figure>

### Pearlescence

#### Weight
Adjusts the intensity of the pearlescent effect.
<figure>
  <img src="../_static/media/pearloid/pearlescence/weight/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Pearlescence Weight from 0.0 to 1.0</figcaption>
</figure>

#### Thickness (nm)
Controls the thickness (nanometers) of the thinfilm layers.
<figure>
  <img src="../_static/media/pearloid/pearlescence/thickness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Thickness from 450nm to 650nm</figcaption>
</figure>

#### IOR

### Diffraction

#### Weight
Controls the intensity of the diffraction effect.
<figure>
  <img src="../_static/media/pearloid/diffraction/weight/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Diffraction Weight from 0.0 to 1.0</figcaption>
</figure>

#### Spread
Adjusts the spread of the diffraction effect.
<figure>
  <img src="../_static/media/pearloid/diffraction/spread/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Diffraction Spread from 0.0 to 10.0</figcaption>
</figure>

#### Tangent
Sets the tangent mapping for diffraction effects. 
<figure>
  <img src="../_static/media/pearloid/diffraction/tangent/strip.png" alt="my alt text"/>
  <figcaption text-align="center">UVmap, Y, Z</figcaption>
</figure>

### Coat

#### Weight

<figure>
  <img src="../_static/media/pearloid/coat/weight/strip.png" alt="my alt text"/>
  <figcaption text-align="center"></figcaption>
</figure>

#### Roughness
Controls the roughness of the clear coat layer.
<figure>
  <img src="../_static/media/pearloid/coat/roughness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Roughness from 0.0 to 1.0</figcaption>
</figure>

#### Tint
Specifies the tint of the clear coat layer.
<figure>
  <img src="../_static/media/pearloid/coat/tint/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Variation of tint colors</figcaption>
</figure>

## Outputs

### Shader
Standard shader output.