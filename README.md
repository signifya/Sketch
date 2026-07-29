# SketchNote Landing Page

## Before you go live — 2 things to finish

### 1. Add your 6 Cosmofeed payment links
Open `index.html`, find this block near the top of the `<script>` section
(search for `COSMOFEED_LINKS`), and replace each placeholder with your real link:

```js
var COSMOFEED_LINKS = {
  pencil_1:      'PASTE YOUR PENCIL – 1 FACE LINK HERE',
  pencil_2:      'PASTE YOUR PENCIL – 2 FACE LINK HERE',
  pencil_3plus:  'PASTE YOUR PENCIL – 3+ FACE LINK HERE',
  colour_1:      'PASTE YOUR COLOUR – 1 FACE LINK HERE',
  colour_2:      'PASTE YOUR COLOUR – 2 FACE LINK HERE',
  colour_3plus:  'PASTE YOUR COLOUR – 3+ FACE LINK HERE'
};
```

### 2. Add your 6 gallery photos
Drop them into the `images/` folder, named exactly:
`sketch-1.jpg` through `sketch-6.jpg` (see `images/README.txt`).

That's it — everything else (pricing, WhatsApp number, footer) is already wired up.
