# Image Slideshow

A lightweight HTML + JavaScript slideshow that cycles through images from a list of URLs provided via query parameters.

## Features
- Cycles automatically through images
- Smooth fade transition between slides
- Scales all images to the same height (keeps aspect ratio)
- Accepts image URLs directly from the page URL

## Usage
- open github pages of this repo

[`https://alpel99.github.io/imgurlslideshow/`](https://alpel99.github.io/imgurlslideshow/)
- add url parameters after `?urls=`
- see **Example** for more info


## Notes
- URLs must be comma-separated
- If no `urls` parameter is provided, sample images are shown
- Works locally or from any web server — no dependencies required

**Example:**  
[`https://alpel99.github.io/imgurlslideshow?urls=https://picsum.photos/id/1011/800/600,https://picsum.photos/id/1025/800/600`](https://alpel99.github.io/imgurlslideshow?urls=https://picsum.photos/id/1011/800/600,https://picsum.photos/id/1025/800/600)