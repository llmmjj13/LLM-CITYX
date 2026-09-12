# Website video

Published building-style videos:

- `building-styles-original.mp4`: first Footprint demonstration
- `building-styles.mp4`: latest Footprint demonstration
- `scene-authoring.mp4`: daylight → darkness → road lights → dawn → fog workflow
- `object-authoring.mp4`: building transforms → nearby buildings → interactive river workflow

After `scripts/render_building_style_video.py` finishes successfully in Blender,
it updates `building-styles.mp4`. Set `PUBLISH_WEBSITE_VIDEO = False` in the
script to disable that copy.

For the widest browser support, encode the published file as H.264 video in an
MP4 container. The page already uses `autoplay`, `muted`, `loop`, and
`playsinline`.
