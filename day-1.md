# Daily Learning
## Review Morning Planning
## Review

1. Item 1
1. Item 2
3. Item 3
2. Item 4

- [ ] Item 1
- [ ] Item 2
- [x] Item 2
- [] I

## Review
Convert an image or video from dark mode to light mode using [ffmpeg](https://www.ffmpeg.org)

```bash
ffmpeg -i input.mp4 -vf "negate,hue=h=180,eq=contrast=1.2:saturation=1.1" output.mp4
```
