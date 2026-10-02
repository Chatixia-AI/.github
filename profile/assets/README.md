# Chatixia AI identity

A simple conversation bubble shaped like a **C**, with one dot for an idea entering the conversation. It keeps the previous icon's indigo-and-white identity.

| Asset | Use |
| --- | --- |
| `chatixia-icon.png` | 512 × 512 PNG, ready for the GitHub organization avatar |
| `chatixia-icon.svg` | Editable tile icon, scalable to any size |
| `chatixia-mark.svg` | Transparent indigo mark for light backgrounds |
| `chatixia-mark-light.svg` | Transparent white mark for dark backgrounds |
| `chatixia-banner.svg` | Organization profile banner |

Colors: indigo `#635BFF`, ink `#24213D`, and pale lavender `#F5F4FF`.
Keep generous space around the mark and preserve its proportions. The avatar artwork fits inside a circular crop.

To rebuild the PNG from the SVG, install Cairo and run from the repository root:

```sh
uv run --with cairosvg python -c 'import cairosvg; cairosvg.svg2png(url="profile/assets/chatixia-icon.svg", write_to="profile/assets/chatixia-icon.png", output_width=512, output_height=512)'
```

On Apple silicon with Homebrew Cairo, prefix the command with `DYLD_FALLBACK_LIBRARY_PATH=/opt/homebrew/lib`.

The public organization landing page is `profile/README.md`.
