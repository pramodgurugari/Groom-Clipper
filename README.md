
<img width="720" height="381" alt="Low" src="https://github.com/user-attachments/assets/94323b07-2ad0-4dfc-87e0-90b85bb7b512" />



<img width="1525" height="848" alt="LOGO" src="https://github.com/user-attachments/assets/26514684-5fcf-42f6-90fe-95afaaeba928" />

# Groom Clipper for Houdini Solaris

A production-focused optimization tool built in **Houdini Solaris (USD)** to reduce groom complexity and improve rendering performance in groom-heavy scenes.

## Overview

**Groom Clipper** is designed to optimize groom rendering by reducing groom density at the USD level, helping artists manage heavy scenes more efficiently. Grooms are often one of the most expensive elements to render, especially in large crowd shots, where thousands of strands can significantly increase render times, memory usage, and render farm costs.

By intelligently reducing groom density based on shot requirements, Groom Clipper allows productions to achieve faster renders while maintaining the necessary visual quality.

## Why Groom Clipper?

Large crowd scenes frequently contain characters that are far away from the camera and do not require full-resolution grooms. Rendering every character with 100% groom density wastes memory and processing resources.

Groom Clipper solves this problem by allowing artists to control the percentage of groom data used per character, per shot, or per render layer.

## Features

* Groom density reduction directly in Solaris/USD
* Distance-based crowd optimization
* Custom groom percentage controls
* Non-destructive USD workflow
* Significant memory savings
* Faster render times
* Improved render stability
* Production-friendly pipeline integration
* Compatible with Arnold rendering workflows
* Ideal for crowd, shadow, and utility renders

## Example Optimization

| Character Category | Groom Density |
| ------------------ | ------------- |
| Hero Character     | 100%          |
| Foreground Crowd   | 75%           |
| Mid-Ground Crowd   | 50%           |
| Background Crowd   | 25%           |

These values can be adjusted to suit the artistic and technical requirements of each production.

## Additional Use Cases

Groom Clipper is not limited to crowd rendering.

It can also be used for:

* Shadow render layers
* Reflection passes
* Indirect lighting passes
* Lighting previews
* Look development workflows
* Technical and utility renders
* Memory-constrained rendering environments

In many of these scenarios, full groom fidelity is unnecessary, making Groom Clipper an effective optimization solution with little to no visible impact on the final image.

## USD Requirements

Groom Clipper operates after assets have been exported into USD.

**Important:** Proper groom-related Primvars must be exported during the USD publishing/export process. The tool relies on these Primvars to identify and control groom density accurately across assets.

## Benefits

* Reduced render times
* Lower memory consumption
* Improved render farm efficiency
* Better scalability for large crowd scenes
* Reduced risk of render crashes
* Faster iteration for lighting artists
* Optimized USD-based rendering workflows

## Production Impact

Groom Clipper helps studios optimize groom-heavy scenes without modifying source groom assets. By reducing unnecessary groom complexity where it is not visually important, artists can render larger scenes more efficiently, improve scene stability, and significantly reduce rendering costs while preserving the quality required for final delivery.

<img width="616" height="526" alt="tool" src="https://github.com/user-attachments/assets/7d15594e-bc13-4584-bf48-a1b1c3bbf279" />
