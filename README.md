# Blobbi Design Assets

This folder contains organized design assets and SVGs for all stages of Blobbi development. These are reference copies with self-contained styling for easy preview and reuse.

## Folder Structure

### `/egg-stage/`
Contains all visual assets for the egg stage of Blobbi development:

**Core Assets:**
- `egg-base.svg` - Basic egg shape with warmth glow effects
- `egg-cracking.svg` - Egg with crack patterns for hatching animation

**Special Marks:**
- `special-mark-sigil-eye.svg` - Mystical eye sigil with glow effects
- `special-mark-shimmer-band.svg` - High-tech shimmer bands
- `special-mark-glow-crack-pattern.svg` - Glowing crack energy patterns
- `special-mark-oval-spots.svg` - Organic oval spot patterns
- `special-mark-ring.svg` - Circular ring markings
- `special-mark-rune.svg` - Ancient rune symbols
- `special-mark-dot-center.svg` - Central dot marking
- `special-mark-blush-sides.svg` - Side blush effects

**Styles:**
- `styles/special-marks.css` - Animation and styling for special marks
- `styles/egg-animations.css` - Egg-specific animations (sway, warmth, cracking)

### `/baby-stage/`
Contains visual assets for baby Blobbi:

**Core Assets:**
- `blobbi-baby-base.svg` - Basic baby Blobbi with happy expression
- `blobbi-baby-sleeping.svg` - Sleeping baby Blobbi with Z's
- `blobbi-baby-accessories.svg` - Hat, glasses, and other accessories

**Styles:**
- `styles/blobbi-animations.css` - Baby Blobbi animations (jump, bounce, wiggle, glow)

### `/adult-stage/`
Contains visual assets for all adult evolution forms:

**Evolution Forms:**
- `pandi-base.svg` - Panda-like form with circular body and distinctive markings
- `owli-base.svg` - Owl-like form with large eyes and feather details
- `catti-base.svg` - Cat-like form with whiskers and curved tail
- `froggi-base.svg` - Frog-like form with pop-out eyes and webbed feet
- `crysti-base.svg` - Crystal form with faceted body and sparkle effects
- `starri-base.svg` - Star form with cosmic elements and constellation patterns
- `flammi-base.svg` - Fire-like form with flame patterns and warm colors
- `droppi-base.svg` - Water droplet form with fluid characteristics
- `cloudi-base.svg` - Cloud-like form with soft, airy appearance and floating wisps
- `bloomi-base.svg` - Flower form with petals, leaves, and natural beauty
- `breezy-base.svg` - Wind form with flowing wisps and ethereal movement
- `rocky-base.svg` - Rock form with angular, crystalline structure and gem accents
- `cacti-base.svg` - Cactus form with spines, arms, and desert flower blooms
- `mushie-base.svg` - Mushroom form with cap, spots, and forest charm
- `leafy-base.svg` - Plant form with multiple leaves and natural green tones
- `rosey-base.svg` - Rose form with layered petals, thorns, and romantic elegance

**Styles:**
- `styles/evolution-animations.css` - Form-specific animations and universal evolution effects

## Design Principles

### Self-Contained SVGs
All SVG files include:
- Embedded gradients and filters
- Inline styling where possible
- Default colors for clear preview
- Proper viewBox for scaling

### Color Schemes
- **Egg Stage**: Cool blues for low warmth, warm yellows/oranges for high warmth
- **Baby Stage**: Purple gradients (#8b5cf6 to #6d28d9) with white highlights
- **Adult Stage**: Form-specific color palettes:
  - Pandi: Black/white/gray with panda markings
  - Owli: Brown/tan earth tones with feather details
  - Catti: Orange/amber warm tones with cat features
  - Froggi: Green nature tones with amphibian characteristics
  - Crysti: Purple/rainbow crystal tones with faceted surfaces
  - Starri: Deep space blues with gold cosmic accents
  - Flammi: Red/orange fire tones with flame patterns
  - Droppi: Blue water tones with fluid transparency
  - Cloudi: White/light blue with soft, airy textures
  - Bloomi: Pink/yellow flower tones with petal gradients
  - Breezy: Light blue/white with flowing wind effects
  - Rocky: Gray/brown stone tones with gem highlights
  - Cacti: Green desert tones with flower accents
  - Mushie: Red/white mushroom colors with natural spots
  - Leafy: Various green tones with leaf textures
  - Rosey: Pink/red rose colors with romantic elegance

### Animation Guidelines
- Subtle movements (1-2 degree rotations, small scale changes)
- Smooth easing functions (ease-in-out)
- Reasonable durations (1.5-4 seconds)
- Reduced motion support
- Mobile performance optimizations

## Usage Notes

### For Developers
- SVGs can be used directly in HTML or imported into React components
- CSS files provide animation classes that can be applied to elements
- All assets are designed to scale proportionally
- Gradients use relative positioning for consistent appearance

### For Designers
- SVGs use standard web colors and can be easily modified
- Gradient definitions are clearly labeled
- Animation keyframes are documented with descriptive names
- Color schemes follow accessibility guidelines

### Performance Considerations
- SVGs are optimized for web use
- Animations include reduced motion preferences
- Mobile-specific duration adjustments
- GPU-accelerated transforms where possible

## File Naming Convention

- `{form}-base.svg` - Standard appearance
- `{form}-{state}.svg` - Specific states (sleeping, happy, etc.)
- `special-mark-{name}.svg` - Special markings for eggs
- `{category}-animations.css` - Animation definitions

## Browser Support

All assets are designed to work in modern browsers with:
- SVG 1.1 support
- CSS3 animations
- CSS custom properties (for dynamic theming)
- Responsive design principles

## Contributing

When adding new assets:
1. Follow the established naming convention
2. Include self-contained styling
3. Add appropriate animation classes
4. Test across different sizes
5. Ensure accessibility compliance
6. Update this README if adding new categories

## License

These design assets are part of the Blobbi project and follow the same licensing terms as the main application.