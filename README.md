# Awesome 360° Resources [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for 360° video, panoramic photography, virtual tours, and immersive web experiences — cameras, players, hosting, editing tools, formats, and tutorials.

360° media is booming: real-estate virtual tours, travel content, VR experiences, and immersive marketing all build on the same stack of cameras, equirectangular formats, players, and hosting platforms. This list collects the pieces that actually work, in one place.

Contributions are welcome — see [Contributing](#contributing).

## Contents

- [Cameras](#cameras)
- [Hosting & Embedding](#hosting--embedding)
- [Players & Libraries](#players--libraries)
- [WordPress](#wordpress)
- [Editing & Stitching](#editing--stitching)
- [Command-line Tools](#command-line-tools)
- [Formats & Metadata](#formats--metadata)
- [Virtual Tour Builders](#virtual-tour-builders)
- [WebXR & Immersive Web](#webxr--immersive-web)
- [Tutorials & Guides](#tutorials--guides)
- [Communities](#communities)

## Cameras

Consumer and prosumer cameras that shoot full 360° photos and video.

- [Insta360](https://www.insta360.com/) — The X-series (X5, X4, X3) is the current consumer 360 benchmark; strong software ecosystem.
- [GoPro Max](https://gopro.com/) — Rugged 360 action camera with GoPro's stabilization pipeline.
- [Ricoh Theta](https://theta360.com/) — The pioneer of one-shot 360 photography; the Z1 remains a favorite for HDR panoramas and Google Street View work.
- [DJI Osmo 360](https://www.dji.com/) — DJI's entry into the 360 camera space.
- [Kandao QooCam](https://www.kandaovr.com/) — 360 and 3D-180 cameras aimed at VR content creators.

## Hosting & Embedding

Uploading a multi-gigabyte equirectangular file to a normal web server doesn't make a playable experience — these services encode, host, and serve 360 media with an embeddable player.

- [Mirame360](https://mirame360.com/) — Free 360° video & photo hosting with automatic encoding and lightweight iframe embeds; also supports multi-scene virtual tours. *(Maintainers of this list.)*
- [Kuula](https://kuula.co/) — Popular 360 photo hosting and virtual tour builder, widely used in real estate.
- [Momento360](https://www.momento360.com/) — Simple upload-and-share for 360 photos and videos.
- [360Cities](https://www.360cities.net/) — Large marketplace and gallery of licensed 360 panoramas.
- [Panoee](https://panoee.com/) — Virtual tour software with a free hosting tier.
- [CloudPano](https://www.cloudpano.com/) — Virtual tour platform oriented at real-estate agents.
- [YouTube](https://support.google.com/youtube/answer/6178631) — Native 360 video playback; requires spherical metadata injection.
- [Vimeo](https://vimeo.com/) — Supports 360 video upload and playback.

## Players & Libraries

Open-source viewers you can self-host or build on.

- [Pannellum](https://github.com/mpetroff/pannellum) — Lightweight, dependency-free WebGL panorama viewer; supports multires tiling.
- [Photo Sphere Viewer](https://github.com/mistic100/Photo-Sphere-Viewer) — Full-featured Three.js-based viewer with a rich plugin system (virtual tours, markers, video).
- [Marzipano](https://github.com/google/marzipano) — Google's 360 media viewer, excellent multiresolution support for gigapixel panoramas.
- [A-Frame](https://github.com/aframevr/aframe) — Declarative WebXR framework; `<a-sky>` makes a 360 scene in one HTML tag.
- [Three.js](https://github.com/mrdoob/three.js) — The foundation most web 360 players are built on; see the equirectangular video examples.
- [Panolens.js](https://github.com/pchen66/panolens.js) — Three.js-based panorama viewer with a simple API.
- [videojs-vr](https://github.com/videojs/videojs-vr) — 360/VR video plugin for the Video.js player.

## WordPress

- [Mirame360 Embed](https://github.com/mirame360/mirame360-wordpress-embed) — Embed Mirame360-hosted 360° videos, photos, and virtual tours with a Gutenberg block, shortcode, or by pasting a link; media is streamed from the platform, not your server.
- [Photo Sphere Viewer plugin](https://wordpress.org/plugins/photo-sphere-viewer/) — Self-hosted panoramas, tours, and 360 video in WordPress.
- [Panorama](https://wordpress.org/plugins/panorama/) — 360 image viewer plugin with Gutenberg and shortcode support.
- [Panorama Block](https://wordpress.org/plugins/panorama-block/) — Minimal Gutenberg block for panoramic images and videos.

## Editing & Stitching

- [Insta360 Studio](https://www.insta360.com/download) — Free desktop editor for Insta360 footage: reframing, stitching, export.
- [GoPro Player](https://gopro.com/en/us/info/gopro-player) — Desktop app for GoPro Max footage, reframing and export.
- [Adobe Premiere Pro](https://www.adobe.com/products/premiere.html) — VR mode with 360-aware effects, transitions, and headset preview.
- [Mistika VR](https://www.sgo.es/mistika-vr/) — Professional optical-flow stitching for multi-camera 360 rigs.
- [PTGui](https://ptgui.com/) — The industry standard for stitching high-resolution still panoramas.
- [Hugin](https://hugin.sourceforge.io/) — Free and open-source panorama stitcher.

## Command-line Tools

- [FFmpeg v360 filter](https://ffmpeg.org/ffmpeg-filters.html#v360) — Convert between equirectangular, cubemap, fisheye, and other projections; the Swiss-army knife of 360 processing.
- [Google Spatial Media Tools](https://github.com/google/spatial-media) — Inject the spherical metadata YouTube and players need to recognize a file as 360.
- [ExifTool](https://exiftool.org/) — Read and write GPano/XMP panorama metadata in photos.

## Formats & Metadata

- [Equirectangular projection](https://paulbourke.net/panorama/) — Paul Bourke's classic reference pages on panoramic projections and conversions.
- [Photo Sphere XMP metadata](https://developers.google.com/streetview/spherical-metadata) — Google's spec for 360 photo metadata (GPano).
- [Spherical video metadata spec](https://github.com/google/spatial-media/blob/master/docs/spherical-video-rfc.md) — The RFC used by YouTube and most players to flag 360 video.

## Virtual Tour Builders

- [3DVista](https://www.3dvista.com/) — Professional virtual tour suite with hotspots, floor plans, and offline export.
- [Matterport](https://matterport.com/) — 3D capture platform widely used for real-estate digital twins.
- [Lapentor](https://lapentor.com/) — Cloud virtual tour builder with self-hosting export.
- [Mirame360 Tours](https://mirame360.com/) — Multi-scene tours from uploaded panoramas with shareable embed links.

## WebXR & Immersive Web

- [Immersive Web](https://immersiveweb.dev/) — Entry point for WebXR: samples, docs, and browser support status.
- [MDN WebXR Device API](https://developer.mozilla.org/en-US/docs/Web/API/WebXR_Device_API) — Reference documentation for building VR experiences in the browser.

## Tutorials & Guides

- [360 Rumors](https://360rumors.com/) — News, reviews, and comparisons of 360 cameras and software.
- [Best settings for Insta360 X5](https://mirame360.com/blog/en/best-settings-for-insta360-x5-sports-travel-night-indoor-get-the-most-out-of-your-360-camera) — Practical setting recipes for sports, travel, night, and indoor shooting.
- [Insta360 camera family deep dive](https://mirame360.com/blog/en/insta360-today-deep-dive-into-the-mainline-360-camera-family-x5-x4-x3-x4-air) — How the X5, X4, X3, and X4 Air compare and which to pick.
- [DJI Osmo 360 deep dive](https://mirame360.com/blog/en/deep-dive-dji-osmo-360-what-it-is-what-works-and-when-you-should-use-it) — What works, what doesn't, and when to use it.

## Communities

- [r/360video](https://www.reddit.com/r/360video/) — Reddit community for 360 video creators.
- [r/Insta360](https://www.reddit.com/r/Insta360/) — Insta360 users, tips, and troubleshooting.
- [r/GoPro](https://www.reddit.com/r/gopro/) — GoPro community, including Max/360 content.

## Contributing

Found a great 360 resource that's missing? Contributions are very welcome!

1. Fork this repository
2. Add your resource in the right section, keeping the format: `[Name](url) — one-line description ending with a period.`
3. Open a pull request with a short note on why it belongs here

Please only suggest resources you have actually used. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work.
