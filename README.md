# ComfyUI workout graphs

Offline importable workflows. Not custom nodes.

**Zip:** https://github.com/OblivionKnight4209/comfy-workouts/archive/refs/heads/main.zip

## Put them here

1. Unzip anywhere (Desktop is fine).
2. Open ComfyUI.
3. Drag a numbered `.json` onto the canvas.

To pin in the sidebar, copy only the numbered jsons into:

`ComfyUI/user/default/workflows/`

Portable: `ComfyUI_windows_portable\\ComfyUI\\user\\default\\workflows\\`

Do **not** put them in `custom_nodes`.

## Files

| File | What |
|---|---|
| 01-txt2img.json | text to PNG |
| 02-img2img.json | photo restyle |
| 03-inpaint.json | mask a hole |
| 04-upscale.json | 2x ESRGAN |
| 05-controlnet.json | Canny lock |
| 06-txt2vid.json | text to mp4 (WAN) |
| 07-img2vid.json | still to mp4 (local Veo-style) |
| 08-vid2vid.json | clip restyle |
| 09-img2stl.json | photo to printable STL |
| 09b-img2mesh-native.json | photo to GLB (core Hunyuan) |

Red node = pick the checkpoint you already have on disk.
