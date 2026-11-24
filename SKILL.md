---
name: impression-card
description: Transform user-supplied photographs into scene-faithful romantic storybook illustrations with luminous impressionist light, an airy oil-led painterly finish, adaptive brushwork and natural depth. Work on any subject.
---

# Impression Card — Detailed Romantic Storybook Illustration with Impressionist Light

**Active approved version: v1.4.1 — FROZEN**
**Art direction:** detailed romantic storybook illustration; Monet-inspired light; oil painting with visible but light, nuanced brushwork and a touch of watercolor-like airiness.
**Version discipline:** keep this as the core photo-to-illustration skill. Poster styling is a SEPARATE future layer and must not silently change these rules.

## Priority 1 — Edit the actual source image
When a user supplies a photograph, **use an image-to-image editing/transformation tool conditioned on the actual attached photo**, not a text-only description of a photograph.
The original image is the sole authority for *what objects exist and where they are*: maintain its subjects, people count, clothing, poses, skyline, building placement, road geometry, shoreline, mountain contour, principal vegetation, landforms, transport and landmarks. Preserve its viewpoint, framing, aspect ratio and original spatial relationships.
**Restyle the image; never redesign the location.** Do not invent iconic structures or replace a quiet bay with a harbour landmark scene, a meadow with a lake, or a two-person portrait with a group portrait. Do not mix subjects across multiple input photos.
If faithful source-conditioned image editing is unavailable, make that limitation explicit rather than claiming a text-to-image recreation is an exact transformation.

## Priority 2 — Complete illustrated reconstruction
**Repaint the whole photo** into a coherent illustration: foreground, middle ground and background; people, vehicles and background alike. Never apply an art filter only to the sky or replace just the background.
Maintain recognisable identity while introducing a unified hand-painted visual language.

## Priority 3 — Pictorial depth, NOT new objects
Depth is the natural separation of existing foreground, middle ground and background through perspective, scale, occlusion, reflected light, atmospheric softness, edge hierarchy and colour.
**Enrich what already exists; do not invent new scene objects.** Enhance the shape, detail and natural overlap of existing foliage, grass, branches, flowers, rocks, waves or reflections. Only modestly extend leaves or twigs from a plant already entering the frame at its edge when helpful for natural framing. Do not add a new tree, garden, bridge, boat, person, house or other independent object merely to increase complexity.
Preserve meaningful visual breathing room; layered does not mean crowded.

## Adaptive Detail and Brushwork — CRITICAL
The more structurally intricate the source, the more restrained its surface texture should be.
**Dense cities, façades, interiors, crowded streets:** preserve accurate windows, railings, cornices, masonry, signs, street furniture and perspective in controlled fine illustration. Keep architectural edges precise; emphasize painterly handling in foliage, dappled light, coloured shadows, clouds and reflections. Never make every surface equally busy.
**Open landscapes, meadows, mountains, beaches, lakes, skies:** allow more expressive directional oil marks and broken colours in light, clouds, vegetation and water while retaining actual landforms and positions.
Complexity must come from illustrated content, not relentless brush marks.

## Material — airy impressionist oil painting
Lean toward **oil paint**, with layered colour, some visible paint body and differentiated short/long directional strokes. Maintain **watercolor-like softness and lightness** in skies, distant atmosphere and subtle transitions, so the image never becomes visually heavy.
Avoid uniformly thick impasto, coarse palette-knife slabs, all-over canvas texture, translucent watercolor as the sole medium, or flat photographic realism.
Brushwork serves sunlight, reflected colour, shadows, leaves, clouds, water and selective highlights rather than covering highly detailed geometry.

## Colour and light
Convey Monet-inspired luminous light mainly through coloured shadows, atmospheric perspective, reflected hue and nuanced complementary colour.
Maintain scene-appropriate colours and time-of-day. Do not impose universal golden-hour lighting, an automatic lavender palette, compulsory Paris façades or flowers.

## People and transport
Human figures should be **less micro-detailed than the architecture** and gently painterly, not photo-real and not cartoonish. Simplify facial micro-detail, hair strands, fabric precision and skin texture while keeping believable anatomy, number, body shape, gestures and positions. Paint clothing folds and shadow transitions with natural visible oil strokes.
Vehicles retain type, silhouette, perspective, placement and interactions; gently paint body surfaces and reflections rather than leaving them as photographic cutouts. Do not toy-ify or distort vehicles.

## Separate each image
For multiple photographs, use one isolated source photo per operation and output one independent, full-bleed image for each. Keep original aspect ratio/orientation. No collage, multi-panel sheet, mockup, added title, frame, signature, logo or watermark unless explicitly requested.

## Quality gate: compare to source
Before accepting, compare output to its source image: subjects and their number, poses, layout, road direction, shoreline, mountain ridges, major trees, vehicles, architecture, landmark identities and viewpoint. Reject any result that introduces a different setting or arbitrary objects, changes person count, uses collage layout, is only a background swap, or buries detailed structures beneath heavy texture.

## One-image operational prompt
Use this when transforming a photograph:
```text
Edit the ACTUAL attached source photo, as an image-to-image transformation. Preserve all original scene content, person count, poses, object placement, perspective, skyline, road direction, shorelines and contours. Do not invent landmarks, people, houses, vehicles, lakes, bridges or new trees. Do not substitute a text-only scene recreation.

Repaint the ENTIRE image as a richly layered, refined romantic storybook illustration with luminous Monet-inspired light. Build pictorial foreground-to-background depth mainly through existing objects, atmospheric perspective, natural overlap, softened distant edges, reflected light and coloured shadows. Enrich existing foliage/grass/reflections; only modestly extend foliage of plants already present at the frame edge.

Adaptive brushwork: keep architecture and visually dense scenes legible, geometrically coherent and finely drawn with restrained marks. Allow freer directional strokes in existing trees, sky, water, clouds, grasses and light. Use an airy oil-led painterly finish with layered pigments, selective visible brushstrokes and delicate watercolor-like softness in atmosphere—never uniform heavy impasto or a heavy all-over filter.

People: modestly simplified, visibly hand-painted rather than photographic; preserve their real number, poses and proportions. Vehicles: correct silhouettes, softened painted reflection details. Keep natural source-specific colours. Output exactly ONE full-bleed painting at source aspect ratio; no collage, new text, border or watermark.
```

## Frozen history
- v1.0 — adaptive detail and brushwork baseline; retained in versions.
- v1.1 — painterly treatment for people and transport; retained in versions.
- v1.2 — experiment reducing photographic people detail.
- v1.3 — refined oil-led painting.
- v1.4 — airy impressionist oil finish with limited watercolor lightness.
- **v1.4.1 — current / approved:** exact v1.4 style intent, with strict source-conditioned editing and depth from existing features rather than inserted objects.

When iterating on poster typography/layout, keep this version unchanged and build poster prompts in a separate file/skill.
