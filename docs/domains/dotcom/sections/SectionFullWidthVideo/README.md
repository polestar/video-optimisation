# SectionFullWidth

The purpose of a Section Full Width is to engage and inspire users. It serves as a way to showcase and highlight the key aspects, features, or capabilities in a visually compelling and engaging manner.

A Section Full Width can either be used with an Autoplay video or a Video player.

## Default
![default image](./image-default.png)
---
<!--
SectionFullWidthVideo
Storybook: http://localhost:6006/?path=/story/organisms-sectionfullwidthvideo--default
-->

### Autoplay (without audio)

| Device  | Aspect ratio | Size         | File size threshold                   | Duration                    | Format | Autoplay | Audio | Preset        |
| ------- | ------------ | ------------ | ------------------------------------- | --------------------------- | ------ | -------- | ----- | ------------- |
| Desktop | 16:9         | 1920x1080px  | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Tablet  | 16:9         | 912x513px    | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Mobile  | 16:9         | 720x405px    | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |


### Video Player (audio optional)

| Device  | Aspect ratio | Size         | File size threshold                      | Duration | Format | Autoplay | Audio    | Preset        |
| ------- | ------------ | ------------ | ---------------------------------------- | -------- | ------ | -------- | -------- | ------------- |
| Desktop | 16:9         | 1920x1080px  | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |
| Tablet  | 16:9         | 912x513px    | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |
| Mobile  | 16:9         | 720x405px    | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |


---

## Compact
![default image](./image-compact.png)
---
<!--
SectionFullWidthVideo
Storybook: http://localhost:6006/?path=/story/organisms-sectionfullwidthvideo--compact
-->

### Autoplay (without audio)

| Device  | Aspect ratio | Size        | File size threshold                   | Duration                    | Format | Autoplay | Audio | Preset        |
| ------- | ------------ | ----------- | ------------------------------------- | --------------------------- | ------ | -------- | ----- | ------------- |
| Desktop | 16:9         | 1056x594px  | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Mobile  | 4:5          | 680x850px   | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |


### Video Player (audio optional)

| Device  | Aspect ratio | Size        | File size threshold                      | Duration | Format | Autoplay | Audio    | Preset        |
| ------- | ------------ | ----------- | ---------------------------------------- | -------- | ------ | -------- | -------- | ------------- |
| Desktop | 16:9         | 1056x594px  | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |
| Mobile  | 4:5          | 680x850px   | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |

---

## Expandable
![default image](./image-expandable.png)
---
<!--
SectionFullWidthVideo - Expandable
Storybook: http://localhost:6006/?path=/story/organisms-sectionfullwidthvideo--expandable
-->

### Autoplay (without audio)

| Device  | Aspect ratio | Size        | File size threshold                   | Duration                    | Format | Autoplay | Audio | Preset        |
| ------- | ------------ | ----------- | ------------------------------------- | --------------------------- | ------ | -------- | ----- | ------------- |
| Desktop | 16:9         | 1925x1080px | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Mobile  | 4:5          | 960x1200px  | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |


### Video Player (audio optional)

| Device  | Aspect ratio | Size        | File size threshold                      | Duration | Format | Autoplay | Audio    | Preset        |
| ------- | ------------ | ----------- | ---------------------------------------- | -------- | ------ | -------- | -------- | ------------- |
| Desktop | 16:9         | 1925x1080px | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |
| Mobile  | 4:5          | 960x1200px  | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |


---
### TBD:

> Because this video will scale based on viewport height we should consider adding an additional video for large desktops,
> for example 1440p. On a 1440p displays the video will currently stretch beyond the current desktop resolution,
> causing it to become blurry.


---

## Cinematic

The purpose of a *Section Cinematic Video* is to engage and inspire users. It serves as a way to showcase and highlight the key aspects, features, or capabilities in a visually compelling and engaging manner.

Image quality may be prioritized over file size, but it's still important to optimize as much as possible.

<!--
SectionFullWidthVideo - Cinematic
Storybook: http://localhost:6007/?path=/story/organisms-sectionfullwidthvideo--cinematic
-->

### Autoplay (without audio)

![default image](./image-cinematic-autoplay.jpg)


| Device  | Aspect ratio | Size        | File size threshold                   | Duration                    | Format | Autoplay | Audio | Preset        |
| ------- | ------------ | ----------- | ------------------------------------- | --------------------------- | ------ | -------- | ----- | ------------- |
| Desktop | 21:9         | 1925x825px  | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Tablet  | 21:9         | 896x348px   | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |
| Mobile  | 4:5          | 720x900px   | 5-10MB, preferably in the lower range | Preferably under 10 seconds | .mp4   | Yes      | No    | [Download](#) |


### Video Player (audio optional)

When the cinematic video is displayed as an video player (i.e. not atutoplay) image quality may be prioritized over file size. But it's still important to optimize as much as possible.

![default image](./image-cinematic-video-player.jpg)


| Device  | Aspect ratio | Size        | File size threshold                      | Duration | Format | Autoplay | Audio    | Preset        |
| ------- | ------------ | ----------- | ---------------------------------------- | -------- | ------ | -------- | -------- | ------------- |
| Desktop | 21:9         | 1925x825px  | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |
| Tablet  | 21:9         | 896x348px   | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) |
| Mobile  | 4:5          | 720x900px   | No more than 15MB per minute of playback | Variable | .mp4   | No       | Optional | [Download](#) | 


## Personal(?)
