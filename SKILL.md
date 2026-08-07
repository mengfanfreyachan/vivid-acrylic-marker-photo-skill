---
name: vivid-acrylic-marker-photo-skill
description: "Transform a user-supplied everyday still life or landscape photo into a vertical 3:4 acrylic-marker color-block illustration for Xiaohongshu. Use when the user wants to preserve the original subject, composition, proportions, spatial relationships, and palette while converting photographic detail into opaque, handmade, unoutlined color fields."
---

# Vivid Acrylic Marker Photo

Transform the supplied photograph into a bright, tactile acrylic-marker illustration. Preserve the photograph's identity; change its material language, not its scene.

## Non-negotiable priorities

Resolve conflicts in this order:

1. Preserve the core subject, proportions, perspective, and key spatial relationships.
2. Preserve the source's dominant palette and color relationships.
3. Build the image from adjacent opaque color fields, not from outlines or tonal rendering.
4. Simplify detail without replacing real scene elements or inventing generic scenery.
5. Keep the result as a clean 3:4 vertical social-post image unless the user requests another aspect ratio.

## Read the photo first

Create an internal scene card before writing a prompt:

- **Core subjects:** one to three elements that identify this exact photo.
- **Spatial anchors:** horizon, ridge, table edge, vessel, path, stream, window, major silhouette, or overlap that must remain unchanged.
- **Color map:** dominant hues, their relative brightness, and the darkest/brightest masses.
- **Major planes:** sky/background, middle-distance structure, foreground, and any focal object.
- **Detail to merge:** repetitive leaves, grass, stones, branches, reflections, brick, fabric texture, or small clutter.

Do not treat the photo as a loose inspiration. Keep all source anchors recognizable.

## Acrylic-marker visual grammar

Use strong, opaque acrylic-marker coverage on a matte, lightly toothed paper surface.

- Construct every form from a small number of broad, flat or gently irregular color fields.
- Let neighboring colors create every boundary. Use hue, value, and area contrast rather than linework.
- Permit slight hand-painted irregularity along color-field edges, but keep the image graphic and intentional.
- Use high-chroma colors only where the source supports them. Preserve the source palette rather than applying a generic rainbow treatment.
- Let dark colors act as broad interior shadow shapes, never as a trace around an object.
- Use small independent white or pale highlight shapes sparingly; never use them as a halo or outline.

### Absolute no-outline rule

Do not use black, navy, brown, or any dark contour line around mountains, trees, clouds, objects, rocks, water, or furniture. Do not use line drawing, cel-shading outlines, edge tracing, uniform borders, or ink sketches.

If a boundary is weak, alter the adjacent color field instead of adding a line.

### Simplification by subject

- **Landscapes:** turn mountains into connected rock, shadow, and grass planes; group trees into solid tapered or clustered masses; make water a small number of flowing color ribbons.
- **Clouds and sky:** use broad sky fields and layered chunky white/pale-blue cloud shapes, not airbrushed gradients.
- **Still lifes:** retain object silhouettes, scale, and placement; use solid local-color planes and restrained shadow blocks.
- **Foliage:** combine repeated leaves and needles into grouped shapes. Avoid leaf-by-leaf rendering.

## Generation workflow

1. Inspect the photo and make the scene card.
2. Use the supplied photo as the edit target. If changing to 3:4 would crop a necessary anchor, expand the surrounding scene subtly rather than cropping, stretching, or distorting it.
3. Compile a focused prompt that specifies the source anchors, palette, major color planes, and no-outline rule.
4. Generate with the built-in image-generation tool.
5. Inspect at normal and thumbnail size.
6. Regenerate once only when a clear defect remains; name the one defect and the exact correction.

## Prompt shape

Write the final generation prompt in four compact paragraphs:

1. **Preservation:** exact subject, compositional anchors, intended 3:4 canvas, and palette relationships to retain.
2. **Color-block conversion:** the major planes and how to simplify the photo into opaque acrylic-marker fields.
3. **Material rule:** matte paper tooth, hand-painted edge quality, and absolute no-outline requirement.
4. **Hard avoids:** no gradients, tonal realism, airbrushing, linework, added objects, text, logos, or watermarks.

## Targeted correction

Correct only the visible failure:

- **Too photographic:** merge texture into larger opaque planes and remove continuous rendering.
- **Outlines appear:** remove every contour and rebuild separation through neighboring field colors.
- **Scene drift:** restore the missing source anchor and original relative placement.
- **Over-simplified subject:** restore its key silhouette or plane, not incidental micro-detail.
- **Generic colors:** return to the source's palette hierarchy.
- **Weak color blocks:** reduce the number of tones, enlarge fields, and make their boundaries more decisive.

## Hard avoids

Avoid black outlines, dark contour tracing, white halos, watercolor washes, oil impasto, smooth gradients, photorealistic texture, airbrush shading, 3D rendering, anime styling, collage, frames, paper mockups, text, logos, watermarks, people or objects not present in the source, and generic replacement scenery.

## Quality gate

Before returning, verify:

- Does the image still read as this exact photo?
- Are the main subject, perspective, and spatial anchors preserved?
- Do the major palette relationships remain recognizable?
- Are color blocks substantial, opaque, and decisive?
- Are all edges formed by adjacent colors rather than drawn outlines?
- Has repetitive detail been grouped without erasing the scene's identity?
- Is the result 3:4 and ready for a Xiaohongshu post?
- Is there no text, logo, watermark, or added scenery unless requested?

## Output

Return the generated image and one short Chinese sentence naming the principal source-preservation decision and the main color-block treatment. Do not reveal the full prompt unless the user asks.
