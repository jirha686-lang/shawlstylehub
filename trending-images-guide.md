# Trending Page – Images Guide (Shawl Style Hub)

Page: `trending.html`
Total images: **10** (1 hero + 5 Women + 4 Men)

## Common rules
- Size: **1200 × 800 px** (3:2 landscape), hero **1600 × 700 px**
- Format: **.webp** ya **.jpg**, size **100–200 KB** se kam (compress karo: squoosh.app)
- Folder: `shawlstylehub/images/trending/`
- Images sirf apni khud ki, AI-generated, ya free-licence (Unsplash / Pexels / Pixabay) use karo. Google se random images mat uthao (copyright / AdSense issue).
- Har image ko `alt` text zaroor do, aur `loading="lazy"` lagao (hero ke siwa).

---

## 0. Hero image (heading "Trending shawls this winter" ke neeche)
- **File name:** `trending-hero.jpg`
- **Kya image ho:** Winter setting mein 2–3 alag colour ke shawls ek sath folded ya hanging (beige, grey, maroon)
- **Search keywords:** `winter shawls collection`, `pashmina shawls folded`
- **Alt:** `Collection of trending winter shawls in neutral and bold colours`

## WOMEN

### 1. Light layers over heavy coats
- **File name:** `women-light-layers.jpg`
- **Kya image ho:** Aurat ne halka shawl / cape coat ya sweater ke upar liya hua
- **Keywords:** `woman layered shawl winter`, `woman cape shawl outfit`
- **Alt:** `Woman wearing a light shawl layered over a winter coat`

### 2. The shroud and stole shape
- **File name:** `women-stole-shroud.jpg`
- **Kya image ho:** Draped wrap stole, cashmere / silk, simple elegant look
- **Keywords:** `draped stole cashmere`, `woman wrap stole fashion`
- **Alt:** `Woman in a draped cashmere stole with a wrap-like shroud shape`

### 3. Neutrals first, bold colour second
- **File name:** `women-neutral-bold-colors.jpg`
- **Kya image ho:** Beige / grey / black shawls ke sath ek bold colour (red ya mustard) accent
- **Keywords:** `beige grey shawls`, `colorful shawl accent`
- **Alt:** `Neutral beige and grey shawls with one bold coloured accent shawl`

### 4. Embroidered and velvet shawls for events
- **File name:** `women-embroidered-velvet.jpg`
- **Kya image ho:** Velvet shawl par embroidery ka close-up, ya shaadi ke mauqe par pehni hui
- **Keywords:** `velvet embroidered shawl`, `pakistani wedding shawl`, `kashmiri embroidery shawl`
- **Alt:** `Close-up of a velvet shawl with detailed embroidery for wedding season`

### 5. Patterned and textured wool for daily wear
- **File name:** `women-textured-wool.jpg`
- **Kya image ho:** Patterned / checked wool shawl plain outfit ke sath
- **Keywords:** `woollen shawl pattern`, `textured wool wrap woman`
- **Alt:** `Woman wearing a patterned textured wool shawl over a plain outfit`

## MEN

### 6. Handloom shawls
- **File name:** `men-handloom-shawl.jpg`
- **Kya image ho:** Aadmi ke kandhon par handloom shawl natural drape ke sath, ya loom ka close-up
- **Keywords:** `handloom shawl men`, `men wool shawl shoulder`
- **Alt:** `Man wearing a handloom shawl that drapes naturally`

### 7. Shawl plus waistcoat
- **File name:** `men-shawl-waistcoat.jpg`
- **Kya image ho:** Shalwar kameez + waistcoat + shawl combination
- **Keywords:** `shalwar kameez waistcoat shawl`, `pakistani men winter wedding`
- **Alt:** `Man in shalwar kameez with a waistcoat and shawl for a winter wedding`

### 8. Texture over shine
- **File name:** `men-texture-over-shine.jpg`
- **Kya image ho:** Charcoal velvet shawl with fine gold embroidery ya woven border / fringe ka close-up
- **Keywords:** `charcoal velvet shawl gold embroidery`, `woven border shawl fringe`
- **Alt:** `Charcoal velvet men's shawl with fine gold embroidery and woven border`

### 9. Muted and deep colours
- **File name:** `men-deep-colors.jpg`
- **Kya image ho:** Royal red, bottle green, black, olive, grey shawls ek line mein
- **Keywords:** `men shawls colors`, `green maroon black wool shawl`
- **Alt:** `Men's winter shawls in royal red, bottle green, black, olive and grey`

---

## HTML code (copy–paste)

Har heading ke neeche `<p>` se pehle ya baad mein ye lagao. Example:

```html
<h3>Light layers over heavy coats</h3>
<img src="images/trending/women-light-layers.jpg"
     alt="Woman wearing a light shawl layered over a winter coat"
     width="1200" height="800" loading="lazy">
<p>Women are choosing shawls, ponchos, capes and shrugs ...</p>
```

### Hero (H1 ke neeche)
```html
<img src="images/trending/trending-hero.jpg"
     alt="Collection of trending winter shawls in neutral and bold colours"
     width="1600" height="700">
```

### CSS (style.css mein ek baar add karo)
```css
img {
  max-width: 100%;
  height: auto;
  border-radius: 10px;
  display: block;
  margin: 12px 0;
}
```

### Sab image names ek nazar mein
| # | Section | File name |
|---|---------|-----------|
| 0 | Hero | trending-hero.jpg |
| 1 | Light layers | women-light-layers.jpg |
| 2 | Shroud and stole | women-stole-shroud.jpg |
| 3 | Neutrals / bold | women-neutral-bold-colors.jpg |
| 4 | Embroidered velvet | women-embroidered-velvet.jpg |
| 5 | Textured wool | women-textured-wool.jpg |
| 6 | Handloom | men-handloom-shawl.jpg |
| 7 | Shawl + waistcoat | men-shawl-waistcoat.jpg |
| 8 | Texture over shine | men-texture-over-shine.jpg |
| 9 | Muted / deep colours | men-deep-colors.jpg |
