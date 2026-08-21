# Biomimetic Industrial Design Board Skill

This skill generates an A3 portrait biomimetic industrial-design process board. The user can provide only an organism, or an organism plus a product type. The skill then calls an image generator and builds a coherent story from biological observation to the final product render.

## Key capabilities

- Infers a suitable product when only an organism is supplied
- Uses a consistent A3 portrait grid and professional portfolio hierarchy
- Preserves all seven design-process sections
- Keeps the same product identity across sketches, refinement, and final render
- Supports reference images, palettes, materials, and mood directions
- Limits generated copy to reduce gibberish

## Mandatory sections

1. BIOLOGICAL ORIGIN
2. FEATURE EXTRACTION
3. FORM EVOLUTION
4. FORM EXPLORATION
5. DESIGN REFINEMENT
6. FINAL DESIGN
7. DESIGN HIGHLIGHTS

## Installation

Copy the following directory into the personal skills directory of a compatible environment:

```text
skills/create-biomimetic-design-board
```

The skill requires an available `imagegen` image-generation capability.

## Examples

Organism only:

```text
Use $create-biomimetic-design-board to create an A3 biomimetic industrial-design board inspired by a jellyfish.
```

Specified product:

```text
Use $create-biomimetic-design-board to design a foldable desk lamp inspired by a butterfly.
```

With visual direction:

```text
Use $create-biomimetic-design-board to design a bamboo-inspired floor lamp in warm white, bamboo green, and linen textures.
```

With reference images:

```text
Use $create-biomimetic-design-board to design a lotus-seedpod-inspired air purifier, using my uploaded images as layout and palette references.
```

## Output note

The default output is one polished raster board. A3 is the intended composition and layout target; it is not a guarantee of perfectly typeset copy, editable layers, or a production-ready print file. Create a separate Illustrator, InDesign, or editable PDF deliverable when exact production files are required.

## Version

Current version: v1.0.0. See [CHANGELOG.md](CHANGELOG.md).

## License

MIT License.
