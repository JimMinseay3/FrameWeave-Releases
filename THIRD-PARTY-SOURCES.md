# Third-party components

FrameWeave's proprietary notice does not replace or restrict third-party licenses.
The installer retains dependency license files and THIRD-PARTY-NOTICES.txt.

- CPython 3.12.13: https://www.python.org/downloads/source/ ; runtime license is bundled.
- FFmpeg/FFprobe: unmodified gyan.dev GPLv3 essentials build. Origin and download checksum are bundled in runtime/tools/FFmpeg-source.txt; GNU GPL license is bundled in runtime/tools/FFmpeg-LICENSE.txt.
- FFmpeg 9.0.2 upstream source: https://ffmpeg.org/releases/ffmpeg-9.0.2.tar.xz
- The upstream source commit referenced by the binary distributor: https://github.com/FFmpeg/FFmpeg/commit/946fcce07b
- Build provider, included libraries and source references: https://www.gyan.dev/ffmpeg/builds/
- OpenCV and third-party media support: https://github.com/opencv/opencv-python ; licenses retained in the cv2 package.
- PyJianYingDraft: Apache-2.0, original license retained in its distribution metadata.
- YuNet model: MIT, source/commit/license retained under packages/media/models.

Dependency names, versions, license metadata and retained license files are listed
in runtime/dependencies.json and the individual *.dist-info directories.
Third-party components remain replaceable and retain the permissions granted by
their original licenses. No restriction in the proprietary notice overrides those rights.
