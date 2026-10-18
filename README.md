# Forge Pass — Preview and Volumetric sample pair

The approved collection structure is **1,100 artworks: 990 Preview and 110 Volumetric**. Each of eleven families will contain 90 Preview and 10 Volumetric artworks. Motion is no longer a tier in this revised structure.

This package contains **two sample artworks**, both from the Circuit family, to review before developing the full collection.

[View the Preview/Volumetric comparison](ForgePass_1100_Sample_Comparison.jpg)

[Play the Volumetric GIF](Circuit_Volumetric_Sample.gif)

[Download the complete sample package](ForgePass_1100_Preview_Volumetric_Samples.zip)

[View animation keyframes](Volumetric_Loop_Keyframes.jpg)

## Sample artwork 1: Preview / Quad Circuit

A polished static composition with four substantial stepped circuit assemblies, asymmetric right-angle forks, four prominent circular junctions, a fixed faceted central hub and one broken framing ring. Cyan, cobalt and silver colours are assigned to different structural parts.

Artwork file: Circuit_Preview_Sample.png — 2048 × 2048 RGB PNG.

## Sample artwork 2: Volumetric / Six-Gate Bloom

A different composition with six stepped gate assemblies, six outer circular junctions, two dimensional foreground rings and a thin blue rear halo. Foreground and rear branches separate and merge slowly. The central hub stays fixed; the branch roots retain their connection through telescoping feeder rails.

Artwork files:

- Circuit_Volumetric_Sample.gif — 1000 × 1000, 20 fps, 240 frames, 12-second infinite loop, 25,416,033 bytes.
- Circuit_Volumetric_Sample.png — 2048 × 2048 RGB still at maximum separation.

The Volumetric PNG is a still backup of that same animated artwork. It is not an additional Preview artwork. This package therefore contains two artworks in three media files.

The Volumetric movement starts partially separated, reaches maximum opening at 3 seconds, returns through partial separation at 6 seconds, merges at 9 seconds and loops continuously. It uses depth-layer movement and halo expansion/contraction.

## Current stage

The 1,100-piece allocation is approved. The complete revised collection has not been generated yet. These samples demonstrate the two tiers and a clear composition change within one family. Final per-artwork ID assignments and the broader individual variation system remain to be developed after sample review.

The earlier eleven-family review remains a separate design reference. This sample package does not replace it or alter the previous 198-piece delivery.

## Included files

The artwork folder contains the three PNG/GIF exports. Comparison JPEGs are review aids. Collection_Plan.json records the current allocation; Validation.json records the completed sample checks. The source folder contains deterministic geometry and a reproducible renderer.

The renderer uses Python, NumPy, Pillow and FFmpeg. The dimensional appearance comes from shaded rails, extrusion edges, sphere lighting and layered geometry. Blender and paid rendering software are not required.

From an extracted copy with dependencies installed and FFmpeg on PATH:

    python source/create_samples.py

No MP4s are required or included. No NFTs have been minted, deployed or listed by producing this review sample.
