# Image Enhancement Technical Specifications

## Blur Correction for Left Side

### Sharpening Techniques
- **Unsharp Mask**: Apply with radius 1-2 pixels, amount 100-150%
- **High Pass Filter**: Overlay blend mode for edge enhancement
- **Deconvolution**: If blur is motion-related, apply directional deconvolution

### Edge Enhancement
- **Edge Detection**: Identify and enhance edge boundaries
- **Contrast Adjustment**: Increase local contrast in blurry regions
- **Noise Reduction**: Apply after sharpening to maintain clean results

## Hextech Style Implementation

### Color Scheme
```
Primary: #00D4FF (Bright Cyan)
Secondary: #0077BE (Deep Blue) 
Accent: #6B4BFF (Purple)
Energy: #FFFFFF (White glow)
Base: #1A1A2E (Dark background)
```

### Visual Effects
- **Crystal Structures**: Angular, faceted surfaces with internal light
- **Energy Channels**: Glowing lines following geometric paths
- **Particle Effects**: Small energy motes and sparkles
- **Material Blend**: Metallic surfaces with crystal overlays

### Lighting
- **Rim Lighting**: Highlight crystal edges
- **Internal Glow**: Light emanating from crystal cores
- **Caustics**: Light refraction through crystal surfaces
- **Bloom**: Soft glow around bright energy elements

## Processing Pipeline
1. **Blur Analysis**: Identify blur type and severity on left side
2. **Selective Sharpening**: Apply sharpening only to blurred regions
3. **Detail Enhancement**: Add hextech elements to launcher areas
4. **Color Grading**: Apply hextech color scheme
5. **Effects Overlay**: Add glow and energy effects
6. **Final Composite**: Blend all enhancements seamlessly