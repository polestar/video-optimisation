# SectionVideoContentOverlay

Having the smallest file size possible is recommended. Experiment with different bitrate values and consider shortening the video if a desirable image quality cannot be attained within the file size threshold.

Ensure that the copy passes the accessibility tests by adjusting the video to be either dark or light enough in the specific areas.

![section image](section-video-content-overlay.jpg)

---
<!--
SectionVideoContentOverlay
Storybook:
http://localhost:6007/?path=/docs/organisms-sectionvideocontentoverlay--default-story
-->

![Section Video Content Overlay](section-video-content-overlay.jpg)

| Device  | Aspect ratio | Size        | File size threshold                   | Duration                    | Format | Autoplay | Audio | Preset        |
| ------- | ------------ | ----------- | ------------------------------------- | --------------------------- | ------ | -------- | ----- | ------------- |
| Desktop | 16:9         | 1920x1080px | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Tablet  | 4:5          | 960x1200px  | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Mobile  | 9:16         | 774x1376px  | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |


### TBD:
> Because this video will scale based on viewport height we should consider adding an additional video for large desktops,
>  for example 1440p. On a 1440p displays the video will currently stretch beyond the current desktop resolution,
> causing it to become blurry.
