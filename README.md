# SMART 3D

English · **[한국어](README_KO.md)**

A web-based 3D modeling tool — modeling, animation and AI image / video rendering in one program.
Free to use as a **Windows program (SMART3D.exe)** that runs without installation, or as an **HTML version** that opens in your browser.

![SMART 3D screen](docs/images/overview_en.jpg)

## Download

**[⬇ Get it from the Releases page](https://github.com/xxxxskyxxx/SMART-3D/releases/latest)**

| File | Language | Description |
|---|---|---|
| `SMART3D_EN_v1.2.exe` | English | Windows executable — double-click to run (no installation) |
| `SMART3D_KO_v1.2.exe` | Korean | Windows executable (Korean UI) |
| `SMART-3D_EN_v1.2_html.zip` | English | HTML version for Chrome / Edge + help |
| `SMART-3D_KO_v1.2_html.zip` | Korean | HTML version (Korean UI) + help |

> **First run:** if Windows shows “Windows protected your PC”, click **More info → Run anyway**. (It appears because this independent program is not code-signed.)

## Features

- **Modeling** — primitives and splines, Modify Poly / Modify Spline editing (Extrude, Inset, Bevel, Chamfer, Bridge…), modifier stack (Multi Select, Projection Spline, Pattern surface tiling (tri · quad · hex), Shell, Noise, FloorGen — straight / herringbone / chevron floor boards…), Boolean, Mirror, SMART Utils ▸ Drop Surface · Extrude keeps a constant thickness at corners · Ctrl+A selects all in a sub-object level
- **Copy** — Shift+drag with Move, Rotate or Scale, then set a count: fill between original and copy / more at the same spacing (rotated copies make circular arrays)
- **Materials** — Material Editor (M): PBR presets (matte · glossy · metal · glass · soap bubble · light), measured metal types, physically based glass (colour absorbed by thickness) and thin film / iridescence, **AO**, gradient Diffuse, Roughness / Bump / Normal / Opacity maps with texture-set loading, Diffuse adjustments (Hue · Tint · Saturation · Gamma · Exposure), rendered previews, Random mapping, Color correct
- **Mapping modifier** — Box · Box Blur (soft seams) · Plane (Bend · Lattice) · Cylinder · Sphere · Spline
- **GI Render** (F9) — GPU path tracing: soft shadows, bounced light, reflections, refraction, with **AI denoise** (Intel Open Image Denoise, WebGPU) and **Live** updates · HDRI environment · background colour · **Lights**: Rect · Disk · Sphere · Spot with IES and a spot Target · Hide in Render
- **Cameras** — Interior / Exterior / Product presets, 2-point perspective (vertical correction), Safe Frame ratios
- **Animation** — timeline, ● REC auto key, keys for move · rotate · scale · parameters · cameras, box-select / move / copy keys, RAM preview
- **Import · Export** — pick a format in File ▸ Import… / Export…: GLB (with animation) · FBX · OBJ · STL · PLY, video (MP4/WebM) · PNG sequence
- **AI Render** — images and videos in one window
  - Google Gemini (image) · **Google Veo (video)**
  - **Higgsfield API** (key) · **Higgsfield Login** (plan credits, exe only) — model lists load automatically
  - AI video from the animation capture (first / last frame + reference clip), before/after compare, viewport overlay

| Animation | AI video |
|---|---|
| ![Animation](docs/images/anim_en.jpg) | ![AI video](docs/images/aivid_en.jpg) |

## Help

- In the program: **Help ▸ Feature guide (with pictures)** · hotkey list **F1**
- Separately: [docs/SMART3D_Help_EN.html](docs/SMART3D_Help_EN.html) (download and open in a browser)

## Requirements

- **exe**: Windows 10 / 11 (64-bit)
- **HTML**: current Chrome or Edge (WebGL 2; WebGPU for the AI denoise)
- AI features need an internet connection and your own account / API key for each service.

## About the AI services

- API keys and login tokens are stored on your PC and sent only to the service you select, to authenticate requests — never to the SMART 3D developer. The GI render needs no key or account.
- Generation costs (credits) and terms of use are those of each service (Google, Higgsfield).
- A Higgsfield API key (open.higgsfield.ai) and a Higgsfield account login (higgsfield.ai) are different services. Account login works **in the exe only**.

## License

**Freeware** — free for personal and commercial work. Everything you create with the program is yours.
Selling, modifying / redistributing or reverse-engineering the program itself is not allowed. See [LICENSE.md](LICENSE.md).

Open-source components: [THIRD_PARTY_LICENSES.md](THIRD_PARTY_LICENSES.md) (three.js, three-bvh-csg, three-mesh-bvh, Electron — MIT)

3ds Max is a trademark of Autodesk, Inc. SMART 3D is an independent product, not affiliated with Autodesk. Google, Gemini, Veo, Higgsfield and Claude (Anthropic) are trademarks of their respective owners.

## About this project

I built SMART 3D as a personal project for my own 3D modeling and AI rendering work, together with Claude (Anthropic), an AI coding assistant. I did the planning and testing, and the code was written through conversations with Claude. SMART 3D is an independent program and is not affiliated with Anthropic.

## Author

**xxxsky** · YouTube [joycg](https://youtube.com/joycg) · [Naver Cafe](https://cafe.naver.com/xxxsky)
