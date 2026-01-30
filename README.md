# media-craft-skill

A [skills.sh](https://skills.sh)-compatible skill that teaches AI agents how to generate, edit, transform, and enhance images, videos, and music using the [obra](https://obra.ai) CLI.

## Installation

```bash
npx skills add NanHeSam/media-craft-skill
```

## Prerequisites

1. Install the obra CLI:
   ```bash
   npm install -g obra
   ```

2. Configure your API key:
   ```bash
   obra config set kie.apiKey YOUR_API_KEY
   ```

## Capabilities

### Images
- Text-to-image generation (Flux, Recraft, Ideogram, Grok, DALL-E 4o, and more)
- Image-to-image editing
- Upscaling
- Background removal
- Reframing / outpainting
- Character remix

### Videos
- Text-to-video generation (Kling, Sora, Wan, Hailuo, and more)
- Image-to-video
- Video-to-video style transfer
- Video upscaling
- Watermark removal
- Motion control
- AI avatars
- Speech-to-video
- Storyboard generation

### Music
- Text-to-music generation (multiple model versions)
- Instrumental tracks
- Custom mode with style and title control
- Lyrics generation
- Music video creation
- Synchronized lyrics / timestamps

## License

MIT
