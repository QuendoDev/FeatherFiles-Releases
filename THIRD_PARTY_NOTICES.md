# Third-party notices

FeatherFiles includes or uses the third-party components listed below. Each one is distributed under its own
license.

| Component | Use | License | Source |
|---|---|---|---|
| FFmpeg (static build with libx264/libx265) | Video encoding. Shipped as a separate executable and run as its own process. | GPL v3 (because of libx264/libx265) | https://ffmpeg.org · https://www.gyan.dev/ffmpeg/builds/ · https://github.com/eugeneware/ffmpeg-static |
| FFprobe | Reading video metadata. Shipped as a separate executable. | GPL v3 | https://ffmpeg.org · https://github.com/joshwnj/ffprobe-static |
| libvips (through sharp) | Decoding, resizing and encoding images | LGPL v2.1+ | https://github.com/libvips/libvips · https://github.com/lovell/sharp |
| mozjpeg, libwebp, libaom, libheif (inside libvips) | Image codecs | BSD / LGPL | https://sharp.pixelplumbing.com/#licensing |
| libheif + libde265 (through heic-decode, WebAssembly) | Decoding HEIC photos | LGPL v3 | https://github.com/strukturag/libheif · https://github.com/catdad-experiments/heic-decode |
| ExifTool (through exiftool-vendored) | Copying EXIF/XMP metadata and file system dates | Artistic License / GPL | https://exiftool.org · https://github.com/photostructure/exiftool-vendored.js |
| exifr | Fast EXIF reading | MIT | https://github.com/MikeKovarik/exifr |
| Electron | Desktop application runtime | MIT | https://www.electronjs.org |
| React, Zustand, zod, lucide-react | User interface and validation | MIT / ISC | — |
| Inter, Sora (fonts) | Typography | SIL Open Font License 1.1 | https://rsms.me/inter · https://github.com/sora-xor/sora-font |

The web app's own components (jSquash, Mediabunny, libheif-js and others) are listed on the website's
[licenses page](https://featherfiles.pages.dev/licencias).

## Source code offer (GPL)

The bundled FFmpeg and FFprobe executables are unmodified builds from the projects listed above. Their complete
source code is available at those links. If you need it in another form, open an issue in
[FeatherFiles-Releases](https://github.com/QuendoDev/FeatherFiles-Releases/issues). We will provide it for at
least three years after the distribution of each release.
