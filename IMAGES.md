# Image map — mathias-sedo.com

How to swap images: replace the file in `images/` with your new photo,
keeping the **exact same filename**. Refresh the browser and the site updates.
No code changes needed.

---

## Hero grid (top of page)
Six images across the full width. Left to right, top row first.

| Slot | File | Currently showing |
|------|------|-------------------|
| Hero 1 (top left) | `images/hero-c.jpg` | FR SCAN — C |
| Hero 2 | `images/work-05.jpg` | FR SCAN — B |
| Hero 3 | `images/work-06.jpg` | FR SCAN — N |
| Hero 4 | `images/work-04.jpg` | FR SCAN — E |
| Hero 5 | `images/photo-08.jpg` | FR SCAN — D |
| Hero 6 (top right) | `images/hero-f.jpg` | FR SCAN — F |

---

## Work — Farvesvøb smeltevand
| Slot | File |
|------|------|
| Image 1 | `images/farvesvob-01.jpg` |
| Image 2 | `images/farvesvob-02.jpg` |
| Image 3 | `images/farvesvob-03.jpg` |
| Image 4 | `images/farvesvob-04.jpg` |

---

## Work — Kemirend
| Slot | File |
|------|------|
| Image 1 | `images/kemirend-01.jpg` |
| Image 2 | `images/kemirend-02.jpg` |
| Image 3 | `images/kemirend-03.jpg` |

---

## Work — FR SCAN

**Diptych (G / Gg):**
| Slot | File |
|------|------|
| Left — positive | `images/photo-01.jpg` |
| Right — negative | `images/frscan-gg.jpg` |

**Grid (3 images below diptych):**
| Slot | File |
|------|------|
| Image 1 | `images/work-01.jpg` |
| Image 2 | `images/work-03.jpg` |
| Image 3 | `images/work-06.jpg` |

---

## Work — Pinholes
| Slot | File |
|------|------|
| Image 1 | `images/photo-06.jpg` |
| Image 2 | `images/pinholes-02.jpg` |
| Image 3 | `images/pinholes-03.jpg` |

---

## Work — Zenits facetter
| Slot | File |
|------|------|
| Image 1 | `images/photo-05.jpg` |
| Image 2 | `images/zenits-02.jpg` |
| Image 3 | `images/zenits-03.jpg` |

---

## Visuals — hero image
Save your orange room installation photo here:

```
images/visuals-hero.jpg
```

Then open `index.html` and find the Visuals section. Replace:
```html
<div class="vis-hero-ph"></div>
```
with:
```html
<img src="images/visuals-hero.jpg" alt="Carousel projection installation">
```

---

## Prints
| Slot | File | Currently showing |
|------|------|-------------------|
| Print 1 | `images/print-01.jpg` | FR SCAN — A |
| Print 2 | `images/print-03.jpg` | FR SCAN — G |
| Print 3 | `images/print-02.jpg` | FR SCAN — N |
| Print 4 | `images/print-04.jpg` | FR SCAN — E |

---

## Adding a new series

1. Copy this block and paste it inside `#work` in `index.html`, above the comment that says `ADD NEW SERIES ABOVE THIS LINE`:

```html
<div class="series">
  <div class="series-head">
    <span class="series-name">Your Series Name</span>
    <div class="series-rule"></div>
  </div>
  <div class="grid-photo">
    <div class="pi" data-title="Series Name — 1">
      <img src="images/your-image-01.jpg" alt="Series Name — 1">
    </div>
    <div class="pi" data-title="Series Name — 2">
      <img src="images/your-image-02.jpg" alt="Series Name — 2">
    </div>
    <div class="pi" data-title="Series Name — 3">
      <img src="images/your-image-03.jpg" alt="Series Name — 3">
    </div>
  </div>
</div>
```

2. Save your images to `images/` with the filenames you used above.
3. Refresh the browser.

---

## Tips
- JPG or WebP both work fine
- Aim for 1800–2400px on the long edge
- Keep files under ~500 KB (compress at squoosh.app)
- Use lowercase filenames with hyphens, no spaces
