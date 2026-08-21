---
name: create-biomimetic-design-board
description: Use when a user wants an A3 biomimetic industrial-design presentation board, bionic product concept, biological feature extraction, form-evolution sketches, design-process infographic, product rendering, or wants to turn an animal, plant, organism, or natural structure into an industrial product.
---

# Create Biomimetic Design Board

## Overview

Turn biological inspiration into one coherent A3 portrait industrial-design board. Show a credible organism-to-product reasoning chain and make the final render the visual focus.

**REQUIRED SUB-SKILL:** Use `imagegen` to generate the final raster board.

## Interpret Input

| Input | Action |
|---|---|
| Organism only | Infer the product with the strongest functional and formal fit; state the choice briefly and generate without asking. |
| Organism + product | Use both exactly. |
| Reference images | Use as layout/style references unless explicitly named as edit targets; label each image's role in the prompt. |
| Palette/material/mood | Preserve it; infer only missing details. |

Ask only when the organism or product is genuinely ambiguous.

## Establish Design Logic

Silently identify 3–5 transferable traits from silhouette, structure, surface, movement, growth, or adaptation. Map each to product form, mechanism, interaction, material, or sustainability. Keep proportions, joints, controls, materials, and construction plausible. Abstract principles instead of making a literal animal-shaped novelty.

## Mandatory A3 Structure

Use A3 portrait ratio, 297 × 420 mm (1:1.414), with a strict grid, consistent margins, thin dividers, numbered sections, generous negative space, and top-to-bottom reading. Reserve roughly 55–60% for process and 40–45% for the final design.

Include every section:

1. **BIOLOGICAL ORIGIN** — organism/habitat photo with short callouts.
2. **FEATURE EXTRACTION** — analytical line drawing with 3–5 traits, geometry, arrows, or motion paths.
3. **FORM EVOLUTION** — 4–6 connected stages: organism → extracted lines → abstraction → product silhouette → initial concept.
4. **FORM EXPLORATION** — 6–9 industrial-design thumbnails; vary proportions, surfaces, structure, and interaction; mark one selected direction.
5. **DESIGN REFINEMENT** — orthographic, section, detail, CMF, material, or mechanism studies.
6. **FINAL DESIGN** — largest image; realistic three-quarter product render, plus at most two small views or use scenes.
7. **DESIGN HIGHLIGHTS** — 4–6 callouts covering relevant form, function, interaction, process, sustainability, and user value.

Sections may share rows but may not disappear into a collage.

## Prompt Contract

```text
Use case: infographic-diagram
Asset type: A3 portrait biomimetic industrial-design board
Primary request: Transform [organism] into [product].
Input images: [image + role, if present]
Biomimetic mapping: [3–5 trait → design translations]
Layout: all seven mandatory sections with final render dominant
Final render: [view, setting, materials, construction, lighting]
Style: professional industrial-design portfolio, restrained, manufacturable
Palette: neutral base + organism-derived accent
Text (verbatim): title, section numbers, seven short English headings only
Constraints: strict grid; visible evolution; same product identity across sketches and render; ample negative space
Avoid: long text, gibberish, cartoon biology, literal imitation, decorative collage, random parts, implausible mechanics, excessive sci-fi, logos, watermark
```

Use compact English labels because long generated copy is unreliable. Never promise perfectly typeset paragraphs inside a generated image.

## Generate and Check

1. Call the built-in image generator; do not stop after returning a prompt.
2. Include the smallest number of recent images covering all references.
3. Generate one polished board unless variants are requested.
4. Check the organism, all seven sections, coherent evolution, selected concept, dominant render, A3 hierarchy, and obvious gibberish.
5. If a critical section is missing or the product identity drifts, iterate once with a targeted correction.
6. Return the image and briefly state the inferred product, palette, and main mapping.

## Quick Reference

| Element | Default |
|---|---|
| Tone | Warm white/light gray + one biological accent |
| Media | Photo, pencil analysis, sketches, semi-render, realistic render |
| Main view | Final product, three-quarter view |
| Product | Contemporary, plausible, manufacturable |

## Common Mistakes

- Mood board only → restore the complete evolution.
- Unrelated final form → repeat the selected silhouette and mapping.
- Crowded process → shorten labels before shrinking sketches.
- Literal imitation → translate principles such as folding, flexing, ribbing, airflow, or growth.
- “Print-ready” claim → A3 is the layout target; create an exact production file only when separately requested.
