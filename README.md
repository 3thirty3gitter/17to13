# 17to13

A lightweight browser app to:

- upload a PNG that contains many separate images,
- detect each separate image region,
- rearrange them into a new PNG that is exactly **12 inches wide at 300 DPI** (3600 px),
- keep each image region at the exact original dimensions (no scaling).

## Run

No build step is required.

Open `/home/runner/work/17to13/17to13/index.html` in a browser.

## Notes

- Input must be a PNG.
- Region detection is based on non-transparent pixels (alpha > 0).
- Output PNG includes 300 DPI metadata (`pHYs` chunk).
