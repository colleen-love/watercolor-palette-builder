# Daniel Smith pigment wheel

**[Try it out!](https://colleen-love.github.io/watercolor-palette-builder/)**

An interactive hue–chroma wheel of every Daniel Smith Extra Fine watercolor, for building a palette with the widest possible color range.

Tap paints to build a palette. The shaded wash shows the range your palette can reach, and the sidebar shows how much of the full Daniel Smith range (and of the range that meets your filters) you cover, which paints would widen it most, and which of your paints set the edge.

A Mixing section lets you pick up to five palette paints and see every pair as a strip from one pure paint to the other, with a water slider for dilution and texture where a component granulates.

Filter by lightfastness, single pigment vs. mixture, transparency, staining, granulation, and price series. Your palette and filters are saved in your browser.

## Data

- Color (CIELAB): Daniel Smith, [Watercolors CIE Lab Coordinates](https://danielsmith.com/daniel-smith-watercolors-cie-lab-coordinates/)
- Lightfastness, staining, granulation, transparency, series: Daniel Smith, [Pigment Characteristics sheet (May 2021)](https://danielsmith.com/wp-content/uploads/2021/05/DS-Watercolor-pigment-characteristics.pdf), plus retailer listings for King's Royal Blue and McCracken Black
- Nine newer paints are missing property data.

## Caveats

Reach is the area of the outline around your paints on the a\*b\* plane. Real mixtures bow inward between distant hues and can bulge outward between neighbors, so treat it as a guide. Mixing strips use [Mixbox](https://github.com/scrtwpns/mixbox) (CC BY-NC 4.0, loaded from jsDelivr), a pigment-like model rather than measured spectra. Each paint is a single measurement at one strength, and lightness isn't shown.

Not affiliated with Daniel Smith. Because Mixbox is licensed for non-commercial use, keep this project non-commercial or swap the mixing model.
