# Flex Paint

Has the same three layers (base coat, metallic flakes, and a clear top coat) with the added *flex*-ibility of a custom falloff color.

<img src="_static/media/flex_paint.png" alt="my alt text" width="50%"/>

## Inputs

### Base Coat

#### Color
Specifies the base color of the paint.
<figure>
  <img src="_static/media/bc_color/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Variation of base colors</figcaption>
</figure>

#### Falloff Color
Specifies the color seen at glacing angles.
<figure>
  <img src="_static/media/bc_falloff_color/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Variation of falloff colors</figcaption>
</figure>

#### Metallic
Controls the metallic appearance of the base paint coat.
<figure>
  <img src="_static/media/bc_metal/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Metallic from 0.0 to 1.0</figcaption>
</figure>

#### Roughness
Controls the roughness of the base paint coat.
<figure>
  <img src="_static/media/bc_roughness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Roughness from 0.0 to 1.0</figcaption>
</figure>

#### Curve Factor
The curve factor determines how quickly the falloff color fades. A lower value means a smoother transition from the base pigment color to the falloff color, while at 1.0, it's just the falloff color. 
<figure>
  <img src="_static/media/bc_curve_factor/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Curve Factor from 0.0 to 1.0</figcaption>
</figure>

#### Use Subtractive Color Mixing
Uses the Kubelka-Munk model to simulate subtractive color mixing.
<figure>
  <img src="_static/media/bc_sub_color_mix/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Subtractive color mixing off and on</figcaption>
</figure>

#### Pigment Scatter

```{note}
Only works when **Subtractive Color Mixing** is enabled.
```

Controls how much the light is scatters within the base layer pigment. 
<figure>
  <img src="_static/media/bc_pigment_scatter/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Pigment Scatter from 0.0 to 1.0</figcaption>
</figure>

#### Pigment IOR

```{note}
Only works when **Subtractive Color Mixing** is enabled.
```

The refractive index of the internal medium. Typically in the range of 1.33 and 1.5 (water and oil respectivly).
<figure>
  <img src="_static/media/bc_pigment_ior/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Pigment IOR from 1.33 to 2.0</figcaption>
</figure>

### Flakes Coat

#### Tint

Sets the color of the flakes tint in the paint. Since the flakes are embedded inside the base coat, the color of the base coat will influence the flake tint.
<figure>
  <img src="_static/media/flake_tint/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Variation of flake tints</figcaption>
</figure>

#### Scale
Adjusts the size of the flakes.
<figure>
  <img src="_static/media/flake_scale/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Scale from 250.0 to 5000.0</figcaption>
</figure>

#### Density
Controls the density of the flakes.
<figure>
  <img src="_static/media/flake_density/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Density from 0.0 to 1.0</figcaption>
</figure>

#### Variation
This parameter determines the extent to which flake orientation deviates from the surface normal. A value of 0.0 means minimal deviation, aligning flakes closely with the surface. Higher values intensify the flake effect, making it more pronounced.
<figure>
  <img src="_static/media/flake_var/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Variation from 0.0 to 0.1</figcaption>
</figure>

#### Roughness
Specifies the roughness of the flakes.
<figure>
  <img src="_static/media/flake_roughness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Roughness from 0.0 to 1.0</figcaption>
</figure>

#### Absorption

Specifies the degree of light absorbed by the pigment before it is reflected off the flakes. 
<figure>
  <img src="_static/media/flake_absorption/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Absorption from 1.0 to 5.0</figcaption>
</figure>

#### Weight
This multiplier scales the reflection intensity received by the flakes.
<figure>
  <img src="_static/media/flake_weight/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Weight from 0.0 to 1.0</figcaption>
</figure>

### Clear Coat

#### Color
Specifies the color of the clear coat layer.
<figure>
  <img src="_static/media/cc_color/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Color from black to white</figcaption>
</figure>

#### Roughness
Controls the roughness of the clear coat layer.
<figure>
  <img src="_static/media/cc_roughness/strip.png" alt="my alt text"/>
  <figcaption text-align="center">Roughness from 0.0 to 1.0</figcaption>
</figure>

## Outputs

### Shader
Standard shader output.