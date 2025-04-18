# Arrow Sweep Navigation Effect

A simple and fun hover animation for navigation links where an arrow sweeps through each word, replacing characters one by one to create a smooth motion effect.

## Effect

When you hover over a link:

contact
>ontact 
->ntact 
-->tact 
c-->act 
co-->ct 
con-->t 
cont--> 
conta-- 
contac- 
contact

## Customization

The default "arrow" is `-->`, but you can easily change it to other characters for different effects:

- `-->` → smooth classic arrow
- `/\\/` → glitchy slash style
- `|||` → scanner beam
- `***` → sparkly trail

## Preventing Navbar Shake

To avoid visual shaking or layout shifts during animation:

- Use a **monospace font** (e.g., `font-family: monospace;`)
- Apply a **fixed width** to links (e.g., `width: 8ch;`)
- Consider **stacking links vertically** to isolate layout changes
