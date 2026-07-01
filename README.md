# omninfusion

Filter tags and badge images for Fusion and Omni.

## Files

- `fusion-tags.json` — 43 filters for Fusion (6 groups: Media Source, Resolution, HDR/Video, Audio, Channels, Special)
- `omni-tags.json` — Same filters converted to Omni customNames format
- `images/` — Badge PNG files

## Setup

```bash
git clone https://github.com/Magededward/omninfusion && cd omninfusion
chmod +x download-images.sh && ./download-images.sh
git add images/ && git commit -m "Add badge images" && git push
```
