---
name: impression-card
description: Transform uploaded photographs or specified scenes into finely detailed, romantic storybook illustrations with subtle Monet-inspired light, adaptive brushwork, rich spatial depth and natural element interweaving. Works with any subject, not only Paris.
---

# Impression Card — Detailed Storybook Illustration with Impressionist Light
**Active prompt version: v1.1** (Adaptive Detail and Brushwork — Critical, plus selective painterly strokes for people and vehicles).

## Version history and rollback
- `versions/adaptive-detail-brushwork-v1.0.md`: approved baseline; adaptive detail and brushwork, no extra figure/vehicle stroke instruction.
- `versions/adaptive-detail-brushwork-v1.1.md`: current; v1.0 plus **only** slightly more visible fine painterly strokes on figures and vehicles.
- To roll back, set the active version to v1.0 and omit the v1.1 addition. Never silently replace the baseline with a newer experimental variant.
- `references/prompts.md`: operational prompt using v1.1.
- `references/monet-style.md`: optional colour and lighting guidance, not a source of mandatory Parisian or floral objects.
- `references/examples.md` and `references/paintings/`: examples/reference material only, never mandatory scene content.

## Primary priority: source content fidelity
If an image is uploaded, the image defines what is depicted. Preserve recognizable subjects, location identity, viewpoint, framing, aspect ratio, main object positions, scale, perspective, relationships and source-appropriate light. Do not replace or redesign the setting.
Parisian façades, towers, gardens, flowers and other romantic motifs are **not mandatory**, and should not appear unless present in the source or explicitly requested.
When a user asks for a new illustration without a source photograph, compose the specified subject faithfully without forcing it into a Parisian setting.

## Core visual identity
Richly detailed, clean and elegant storybook illustration first; impressionism primarily through light, colour, atmosphere and **selective** brushwork.
Avoid both photorealistic pasted-in elements and uniform oil-paint texture.
Every part of the image should be artistically rendered with a coherent illustrative language.

## Non-negotiable: detail, depth and interweaving
- **Rich discoverable detail:** articulate existing architectural ornament, windows, railings, branches, leaves, cloth, paths, reflections, rocks, clouds or other scene-relevant elements. High fidelity in focal details, controlled simplification farther away. Richness is from depicted forms, not texture overload.
- **Three spatial planes:** distinguish foreground, middle ground and background using size, perspective, softening, tonal hierarchy and atmospheric distance. Do not invent large foreground flowers or other additions just to fill space.
- **Natural interweaving:** preserve believable overlap and partial occlusion between existing forms: branches against sky and façades, people among street furniture, roofs layered by distance, reflections connecting land/water/light. Integrate elements rather than isolating them like stickers.
- **Full-scene transformation:** render foreground and moving objects as carefully as background; no background-only replacement or surface-level filter.

## Adaptive Detail and Brushwork — Critical (v1.0 baseline)
- Dense architectural/urban/interior scenes: precise architecture and street geometry; very restrained surface brushwork; fine illustration on windows, cornices, street furniture, signs and masonry.
- Open landscapes/water/meadows/skies: more expressive strokes permitted, particularly in light, clouds, vegetation, reflections and atmosphere.
- Monet influence comes chiefly from luminous light, delicate reflected hues, soft coloured shadows, subtle broken colour and atmospheric depth.
- The more intricate the subject, the more **selective and quiet** the brushwork. Never apply chunky or uniform impasto across the canvas.
- Keep nuanced, harmonious and source-adapted local colours. Avoid automatic golden-hour lighting or excessive orange/lavender treatment.

## v1.1 addition — people and vehicles ONLY
People and traffic/transport should retain **slightly more visible, delicate hand-painted brushstrokes** than the surrounding precisely drawn buildings and street.
Use subtle painterly strokes on clothing folds, hair, skin shadow transitions, silhouettes, vehicle body panels, glass, reflected light, wheels and contours.
The goal is a natural hand-painted presence, not realistic photo cut-outs. **Do not** cartoonize, exaggerate, distort anatomy, simplify heavily, change vehicle geometry, or make figures toy-like.
Maintain accurate pose, proportions, perspective, scale, recognizable scene identity and original placement.
**Do not change architecture, street treatment, lighting style, palette or other v1.0 parameters as a side effect of this addition.**

## Output rules
- One standalone, full-bleed image **per source image**, unless the user explicitly requests a different arrangement or number.
- Keep the source's aspect ratio and orientation; for wholly new images with no ratio specified, default to portrait 2:3.
- No collage, panels, frames, border, layout, mockup, captions, added text, logo, signature or watermark.
- Existing real-world signs may be represented when necessary for scene fidelity; do not invent new lettering.
- Do not copy signatures or watermarks from visual style references.

## Workflow and quality gate
1. Inspect source image and identify existing focal subjects, dense vs. open areas, lighting, foreground/middle/background and naturally overlapping elements.
2. Preserve composition and all important spatial relationships before applying styling.
3. Apply v1.0 adaptive detail rules; then apply the **single v1.1 delta only to people and vehicles** where present.
4. Verify whole-scene illustration, fine detail, believable spatial depth, natural interweaving, readable structures and coherent light. Reject background-only swaps, uniform texture, cartoon figures, photoreal vehicles and arbitrary additions.
