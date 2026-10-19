# Forge Pass — complete 1,100-artwork collection

**990 Preview artworks + 110 Volumetric artworks across eleven families.** Each family contains 90 Preview and 10 Volumetric artworks. Each of its ten structural subtypes contains nine Preview artworks and one Volumetric artwork.

The delivery contains **1,100 PNGs and 110 animated GIFs: 1,210 artwork media files in total**. A Volumetric artwork's matching PNG is a still backup of that same artwork; it is not an additional Preview edition. Motion is not a tier in this collection.

- PNG masters: **2048 × 2048** pixels.
- Volumetric GIFs: **1000 × 1000**, **20 fps**, a **240-frame timeline**, **12-second infinite loops**, each below **50,000,000 bytes**. Identical adjacent poses may be stored as one GIF frame with a longer display duration.
- Volumetric movement separates and merges front/rear structures slowly, with clearly visible depth movement suited to each family.
- The artwork ZIPs contain PNG/GIF media only. No MP4s or Blender installation are required.

## Download and extract

[Download the complete collection as one outer ZIP](https://github.com/aygaladima/New/archive/refs/heads/forge-pass-1100-collection.zip).

The complete download contains **28 independent art ZIPs**, approximately **1.91 GB** in total, plus supporting files. First extract the outer ZIP; then extract the individual art ZIPs into a common destination. Their Preview and Volumetric folders combine into the complete collection. A PNG and its matching GIF are always kept in the same art ZIP.

For smaller downloads, use the individual ZIP links below. Each ZIP opens normally on its own; these are not split-volume archives. The exact artwork-ID lists, file sizes, and SHA-256 checksums are recorded in Package_Manifest.json.

## Collection structure

Circuit, Lightning, Coral, Frost, Roots, Trident, Crown, Lattice, Cascade, Bonsai, and Starburst each contain 100 distinct artworks. Every family has ten structural subtypes, with separate individual compositions inside each subtype. Family, subtype, tier, seeds, and artwork-to-file associations are recorded in Collection.json in the optional source backup.

The art is generated procedurally with Python and free rendering/encoding tools. Reproduction instructions and exact dependencies are included in the source backup. Restore its compressed geometry with `python Restore_Geometry.py` before following those instructions.

## Scope

This delivery creates artwork files and production records. **It does not mint NFTs, deploy a contract, publish items to OpenSea, or list anything for sale.** Collection.json is a production manifest; it is not deployed NFT metadata. Artwork IDs must be mapped explicitly to token IDs when a minting workflow is chosen.

Marketplace creation options, animation presentation, fees, hosting capacity, and ongoing storage still require checking before publication. The GitHub links provide the downloadable project; production NFT hosting has not been selected by delivering these files.
