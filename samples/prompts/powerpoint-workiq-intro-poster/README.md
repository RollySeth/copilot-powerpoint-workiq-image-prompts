# PowerPoint WorkIQ Intro Poster

![Screenshot of the prompt in use](./assets/demo.jpeg)

> [!IMPORTANT]
> This prompt uses Microsoft 365 WorkIQ and public profile information to generate a personalized visual. Depending on your data, generated outputs may include references to people you work with, projects, teams, roles, values, or organizational details.
>
> If you choose to share the output publicly, review it first and remove anything that could expose private, confidential, or security-sensitive information. Always follow your organization's privacy and information protection guidelines before publishing generated content.

## Summary

This prompt helps create a 16:9 introduction or title-slide poster in PowerPoint by editing a selected image in place. It preserves the subject's likeness while expanding the visual into a polished scrapbook-style design grounded in WorkIQ and a LinkedIn profile.

## Prompt

```text
Edit the selected image in place. Keep the exact same person likeness, face, skin tone, hair, expression, clothing, body proportions, and paper-cutout collage style.

CRITICAL OUTPUT SIZE: landscape 16:9 widescreen only (not square, not portrait). Match the selected picture frame aspect ratio 16:9. Full-bleed composition across the wide frame.

Composition:
- Subject remains the same cutout person holding a paint palette and brushes
- Person in focus and centered of the wide landscape space around which collage elements are there
- Looking above the palette
- Soft pastel pink background
- Giant translucent "MEET" typography behind the subject
- Red handwritten doodles, arrows, speech bubbles, stars, sparkles, sticky notes
- Editorial scrapbook / magazine collage, mixed media, premium graphic design
- visualizes my work life. Include my name, what I do, who I work with, my role, my values and what's important to me. Ground your research in Work IQ and the public profile for me on LinkedIn -<replace with LinkedIn profile url>

Identity lock:
- Do NOT replace or redesign the face
- Do NOT age, beautify, restyle, or re-gender the person
- Preserve facial features exactly from the reference/selected image
- Only extend background and collage elements to fill the landscape sides
- magazine cover design, creative branding poster
- social media introduction graphic, clean composition, aesthetic scrapbook journal style, premium graphic design, trendy Instagram visual identity, paper cutout effect, soft studio lighting, high detail, modern marketing artwork.

Avoid: square crop, 1:1, 9:16 portrait orientation, new face, different person, heavy face morphing.
```

## Description

This prompt is designed for Copilot in PowerPoint when a slide already contains a selected reference image. It combines image-editing instructions with WorkIQ grounding so Copilot can preserve the selected person's likeness while adding context-rich collage elements about their work, role, collaborators, values, and public professional profile.

## Use cases

- Introduce a new team member or new hire.
- Enhance title, profile, or intro slides.
- Create welcome slides for conferences, events, offsites, or team meetings.

## Contributors

[Rolly Seth](https://github.com/rollyseth)

## Version history

| Version | Date | Comments |
| ------- | ---- | -------- |
| 1.0 | July 17, 2026 | Initial release |

## Instructions

1. Open PowerPoint.
2. Add your reference image to a slide. This sample used a background-removed image placed in a landscape slide so Copilot had room to add design elements.
3. Select the image on the slide and open Copilot in PowerPoint.
4. Paste the prompt from the Prompt section.
5. Replace `<replace with LinkedIn profile url>` with the relevant LinkedIn profile URL.
6. Run the prompt in Copilot in PowerPoint. This prompt uses WorkIQ and Copilot's image edit functionality.
7. Review the generated image. The output should reference data from the LinkedIn profile and WorkIQ, while using the existing slide image as the basis for the poster-style design.

## Prerequisites

- Copilot in PowerPoint.
- WorkIQ enabled for your tenant.
- A selected image on a PowerPoint slide.
- A LinkedIn profile URL to ground the public profile context.

## Help

This sample is provided for community use and learning. If you run into issues, review your tenant's Copilot and WorkIQ availability, confirm that an image is selected before running the prompt, and check that the slide/image frame is set up as landscape 16:9.

## Disclaimer

**THIS CODE IS PROVIDED _AS IS_ WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**
