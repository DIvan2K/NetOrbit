# Contributing to NetOrbit


I'm excited to see your interest in the project! Since NetOrbit is growing fast, here is how you can help:

```txt
Note: As the project is in its early stages, I am not yet ready for extensive code reviews or major architectural changes. I am currently focusing on stabilizing the core features and will provide a detailed technical contribution guide soon. For now, the best way to help is through themes, bug reports, and feature suggestions.
```

## Themes & Design
I want to replace the simple --color flag with a proper --theme <name> system. If you want to suggest a new color palette, please open an Issue and follow this template:

Theme Name: (e.g., "Cyberpunk", "Nord", "Sakura")

### Map Colors
Background: #XXXXXX

Grid: #XXXXXX (muted color)

Land: #XXXXXX

Coastline: #XXXXXX

Home Point: #XXXXXX

Markers: #XXXXXX

### Interface & Animation
Panel Borders: #XXXXXX

Stats (Captured): #XXXXXX

Stats (Mapped): #XXXXXX

Stats (Geo Miss): #XXXXXX

Marker (In Motion): #XXXXXX

Marker (Arrival): #XXXXXX

Marker (Reached): #XXXXXX

If you want to code it: Feel free to submit a PR with a theme engine implementation that uses these palettes.

## Bug Reports & Features
Found a bug? Open an Issue and describe what happened (especially on macOS or different Linux distros).

Want a new feature? Suggest it in the Issues! I'm currently looking into adding Latency/Ping and Fractional FPS.