# Frontend checklist

## Why?

Frontend is extremely complicated. There are (too) many topics to cover for a single person as part of a development team.
This checklist helps reducing the failure by compensating for potential limits and human memory and attention. It helps
to ensure consistency and completeness.

## Table of contents

- [Performance](#performance)
  - [Images](#images)
- [References](#references)

## Performance

### Images

- [ ] Use WebP images to reduce filesize
- [ ] Use image CDN's to transform, optimize and deliver images
- [ ] Serve responsive images and use srcset and sizes attributes to serve images to different display densities
- [ ] Use imagemin to compress images
- [ ] Replace animated GIF's with video for faster page loads
- [ ] Use lazy-loading to improve loading speed to reduce initial page load time, initial page weight and system resource usage

## References

- https://web.dev/vitals/