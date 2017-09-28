# LabHacker’s CSS Styleguide

A guide to writing stylesheet files (CSS/Scss) for LabHacker projetcs.

## Best Practices
Our model is generally based on [RSCSS](rscss.io).

### Componentization
Try to worry on writing just elements, mostly. Eventually you will identify which elements should actually be components, then just convert them. In other words: only generalize something when there is a second occurence of it.

### Styles
- Write the zero on decimals under 1 (e.g.: 0.5em);
- Hexadecimal color with lowercase;
- Black and white (colors) should have no variables and be written as `#000` and `#fff` respectively;
- Shades of gray (colors) should have no variables and be written as hsl(0, 0%, XX%);
- Maximum of 4 levels of nesting (using ampersands [&] is not actually nesting, so no stress);
- You may nest components in order to add contextual style that do not affect its appearance (e.g.: layouting styles);

## WIP
Define what kind of nomenclature 'variants' may or may not have (can they be written as a two-word name with an `- `?).

