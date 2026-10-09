# ffmpeg-builder-test-public

A test consumer of [ffmpeg-builder](https://github.com/ryan-morris/ffmpeg-builder): an open-source distributor that
publishes LGPL and GPL FFmpeg builds as public releases, using the engine's reusable workflows.

- `ffmpeg-build.yml` and `ffmpeg.lock`: what is built.
- `release`: builds and publishes; `ci`: builds pull requests; `update`: lock updates.
- `product/`: a product that fetches a published build and runs it (`product`, `product-update`).
