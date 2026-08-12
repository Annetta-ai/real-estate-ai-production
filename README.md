# Real Estate AI Production

Open-source framework for AI-powered production workflows in real estate marketing and architectural visualization.

## Vision

Build an open standard for AI-driven real estate content production.

This project documents professional workflows for transforming architectural CGI into high-end marketing assets using modern AI tools.

## Scope

- CGI → Photorealistic Images
- Images → Cinematic Video
- AI Prompt Engineering
- Architectural Visualization
- Presentation Workflows
- Quality Standards
- Production Pipelines
- AI Automation
Production standards

Every deliverable must preserve the property’s architecture while improving realism, atmosphere, and marketing quality.

CGI → Photorealistic Images

* Preserve geometry, proportions, materials, camera angle, and major design elements.
* Use believable lighting, reflections, shadows, textures, landscaping, and scale.
* Remove AI artifacts: warped lines, repeated objects, floating details, plastic materials, and inconsistent reflections.
* Quality gate: The image must look like professional real-estate photography at 100% zoom without architectural distortion.

Images → Cinematic Video

* Preserve the source image’s architecture, composition, skyline, landscape, and object placement.
* Use slow, controlled camera movement with realistic depth, parallax, and motion blur.
* Prevent structural morphing, texture drift, flicker, sudden zooms, and unintended object movement.
* Quality gate: Review the full clip frame by frame. Fixed architectural elements must remain stable from first frame to last.

Prompt Engineering

* Define the subject, preservation constraints, camera behavior, lighting, atmosphere, motion, and output format.
* Separate required changes from elements that must remain unchanged.
* Specify duration, aspect ratio, lens, movement direction, speed, and subject position.
* Record the prompt, model, settings, source asset, and version for every approved output.
* Quality gate: Another producer must be able to reproduce the intended result from the documented prompt and settings.

Architectural Visualization

* Treat plans, approved CGI, and client-provided references as the source of truth.
* Never invent structural features, views, amenities, finishes, or surroundings unless clearly labeled as conceptual.
* Maintain believable dimensions, perspective, circulation, furniture scale, and material behavior.
* Separate verified visualization from creative marketing concepts.
* Quality gate: Compare the final asset with the source references and obtain client or architectural approval before publication.
## Prompt library

Reusable prompt templates for real-estate AI production. Replace all text in brackets with project-specific information.

### CGI → Photorealistic Image

Transform this architectural CGI into a high-end photorealistic real-estate photograph.

Preserve the original architecture, geometry, proportions, materials, camera position, perspective, composition, openings, and structural details. Do not redesign, crop, extend, or move architectural elements.

Improve natural lighting, material texture, reflections, shadows, landscaping, depth, and atmospheric realism. Use realistic scale and physically believable light behavior.

Style: [luxury editorial / daylight / sunset / blue hour]  
Camera: [lens and camera height]  
Output: [aspect ratio and resolution]

Avoid warped lines, altered geometry, plastic materials, repeated objects, artificial HDR, excessive sharpness, and visible AI artifacts.

### Image → Cinematic Video

Create a cinematic real-estate video from the provided image.

Preserve the architecture, composition, materials, furniture, skyline, landscaping, and object placement exactly as shown. Use a slow, controlled [dolly-in / dolly-out / lateral slide / subtle orbit] with realistic depth and gentle parallax.

Duration: [number] seconds  
Aspect ratio: [ratio]  
Camera speed: very slow and stable  
Motion: natural and physically believable

No structural morphing, flicker, texture drift, sudden zoom, camera shake, moving walls, bending lines, or newly generated objects. Fixed architectural elements must remain stable from the first frame to the last.

### Luxury Interior Visualization

Create a photorealistic editorial visualization of this luxury interior.

Preserve the approved layout, architecture, dimensions, furniture placement, materials, and camera perspective. Improve lighting, texture detail, reflections, depth, and atmosphere without redesigning the space.

Use soft natural light, controlled highlights, realistic shadows, accurate material response, and restrained luxury styling. The result must feel sophisticated, believable, and professionally photographed.

Avoid generic luxury clichés, excessive decoration, distorted furniture, incorrect scale, oversaturated colors, and artificial-looking materials.

### Luxury Exterior Visualization

Create a photorealistic architectural visualization of this luxury property exterior.

Preserve the building design, massing, façade, windows, landscape layout, surroundings, and camera position. Improve environmental realism, vegetation, sky, reflections, shadows, and material detail.

Lighting: [daylight / sunset / blue hour]  
Atmosphere: refined, natural, and cinematic  
Camera: architectural photography with straight vertical lines

Do not invent floors, windows, balconies, amenities, views, neighboring buildings, or structural features. Avoid distorted geometry, unrealistic vegetation, dramatic fake skies, excessive glow, and artificial HDR.

## Production workflow

### 1. Source review

- Collect the original CGI, plans, reference images, brand guidelines, and delivery requirements.
- Confirm the approved architecture, materials, views, aspect ratios, resolutions, and deadlines.
- Identify elements that must remain unchanged.

### 2. Reference preparation

- Select references for lighting, atmosphere, camera style, materials, landscaping, and motion.
- Separate architectural references from creative mood references.
- Do not use references to introduce unapproved structural changes.

### 3. Prompt development

- Define the requested transformation and preservation constraints.
- Specify camera, lens, lighting, atmosphere, movement, duration, aspect ratio, and output resolution.
- Save the prompt, model, settings, source asset, and version number.

### 4. Image production

- Generate several controlled variations from the approved source.
- Select the result with the strongest realism and architectural accuracy.
- Refine only the areas that fail quality review.

### 5. Image quality control

- Compare the result with the original CGI, plans, and approved references.
- Check geometry, perspective, materials, reflections, landscaping, furniture scale, and AI artifacts.
- Approve the image for video production only after it passes the image quality gate.

### 6. Video production

- Choose one simple camera movement for each shot.
- Generate short test clips before producing the final sequence.
- Preserve fixed architectural elements and avoid unnecessary environmental motion.

### 7. Video quality control

- Review the full clip and inspect critical moments frame by frame.
- Reject clips with flicker, morphing, texture drift, unstable lines, camera shake, or newly generated objects.
- Confirm that the first and final frames remain architecturally consistent.

### 8. Export and delivery

- Export approved assets in the required resolution, aspect ratio, codec, and file format.
- Use clear filenames with the project, scene, format, and version.
- Deliver final assets together with the approved prompts and production settings.
- Archive source files, references, prompts, working versions, and final outputs.

## Example projects

### Luxury Waterfront Residence

**Objective:** Transform approved architectural CGI into photorealistic marketing images and short cinematic video sequences.

**Source assets:**

- Exterior and interior CGI
- Architectural references
- Material and lighting references
- Client-approved compositions

**Workflow:**

1. Review source assets and define preservation constraints.
2. Convert CGI into photorealistic images.
3. Compare each result with the approved architecture.
4. Generate short video clips using slow, controlled camera movement.
5. Review clips frame by frame for structural stability.
6. Export approved assets in web, social media, and presentation formats.

**Quality requirements:**

- Architecture and camera perspective remain unchanged.
- Materials, lighting, reflections, and landscaping appear physically believable.
- Video contains no flicker, morphing, texture drift, or newly generated objects.
- Final assets are approved before delivery.

**Deliverables:**

- Photorealistic exterior images
- Photorealistic interior images
- Cinematic video clips
- Final prompts and production settings

## Roadmap

- [x] Production standards
- [x] Prompt library
- [x] Workflow documentation
- [x] Quality checklists
- [x] Example projects
- [ ] AI agents
- [ ] Open-source tools


## Contributing

Contributions, ideas and discussions are welcome.