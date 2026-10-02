# Chatixia AI identity

A new folded-aperture emblem: two ribbons open a window between ideas. Amber and sky blue on midnight navy connect it to the Blueprint Cast and the visual language of [chatixia.net](https://chatixia.net/).

| Asset | Use |
| --- | --- |
| `chatixia-avatar.png` | 512 × 512 PNG, ready for the GitHub organization avatar |
| `chatixia-icon-master.png` | 1254 × 1254 PNG, original artwork |
| `chatixia-banner.png` | 2172 × 724 PNG, organization profile header |
| `guide-chronicle.webp` | Tink, the Chronicle guide from chatixia.net |
| `guide-mesh.webp` | Pip, the Mesh guide from chatixia.net |
| `studio-lsp.jpg` | Published Studio thumbnail for the Language Server Protocol film |
| `generation-prompts.md` | Exact built-in imagegen prompts and source references |

Reference colors from the website: navy `#081A31`, sky blue `#7CC7FF`, amber `#FFB45E`, and pale ink `#E8F2FF`. The generated artwork uses gentle tonal variation around these colors.

The emblem was designed from scratch using the built-in imagegen tool, then recolored to match the website. The banner combines the new emblem with the website's Blueprint Cast. Neither uses the old C-shaped speech-bubble icon. The old asset set has been retired.

Keep the square avatar background and its generous padding; the mark fits inside a circular crop. To export the avatar again:

```sh
sips -Z 512 profile/assets/chatixia-icon-master.png --out profile/assets/chatixia-avatar.png
```

The avatar must be uploaded in [GitHub organization profile settings](https://github.com/organizations/Chatixia-AI/settings/profile); updating this repository publishes the landing page but does not set the organization avatar.

The public organization landing page is `profile/README.md`. Its project descriptions and development statuses were checked against chatixia.net and the public repository READMEs on October 3, 2026.
