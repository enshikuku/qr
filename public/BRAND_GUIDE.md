# CALATECH Brand Guide

Always write CALATECH in uppercase letters, never lowercase or mixed case. The brand name should be used consistently across all platforms and materials to maintain a clear, recognizable identity.


**What to use, where to place it.**

---

## 🎨 Colors

| Name    | Hex       | Usage                               |
| ------- | --------- | ----------------------------------- |
| Primary | `#004d00` | Buttons, headings, primary elements |
| Dark    | `#003300` | Hover states, dark sections         |
| Light   | `#006600` | Accents, secondary elements         |
| Lighter | `#008000` | Light accents, hover effects        |
| Pale    | `#e6f2e6` | Background fills, light sections    |
| Theme   | `#1a1a2e` | PWA theme, dark backgrounds         |

**Tailwind CSS:**

```javascript
colors: {
  'calatech': {
    'primary': '#004d00',
    'dark': '#003300',
    'light': '#006600',
    'lighter': '#008000',
    'pale': '#e6f2e6',
  },
}
```

---

## 🔤 Fonts

**Family:** Century Gothic

| File                     | Weight | Usage              |
| ------------------------ | ------ | ------------------ |
| `centurygothic.ttf`      | 400    | Body text          |
| `centurygothic_bold.ttf` | 700    | Headings, emphasis |

**CSS:**

```css
@font-face {
	font-family: "Century Gothic";
	src: url("/branding/font/centurygothic.ttf") format("truetype");
	font-weight: 400;
	font-display: swap;
}

@font-face {
	font-family: "Century Gothic";
	src: url("/branding/font/centurygothic_bold.ttf") format("truetype");
	font-weight: 700;
	font-display: swap;
}
```

---

## 🎯 Logos

| File              | Use                                                                               |
| ----------------- | --------------------------------------------------------------------------------- |
| `cover_logo.png`  | Hero sections, navigation bar (already has brand name and tagline), large displays |
| `logo.png`        | Footer, smaller sections                                                          |
| `main_logo.png`   | General purpose, default use                                                      |
| `square_logo.png` | Social media, 1:1 ratio                                                           |

**Location:** `/branding/logo/`

---

## 🔗 Favicons

| File                         | Size    | Use                   |
| ---------------------------- | ------- | --------------------- |
| `favicon.ico`                | 32x32   | Browser tab fallback  |
| `favicon-16x16.png`          | 16x16   | Small browser tab     |
| `favicon-32x32.png`          | 32x32   | Standard browser tab  |
| `apple-touch-icon.png`       | 180x180 | iOS home screen       |
| `android-chrome-192x192.png` | 192x192 | Android app drawer    |
| `android-chrome-512x512.png` | 512x512 | Android splash screen |
| `site.webmanifest`           | -       | PWA configuration     |

**Location:** `/branding/favicon/`

**HTML Links:**

```html
<link rel="icon" type="image/x-icon" href="/branding/favicon/favicon.ico" />
<link rel="icon" type="image/png" sizes="16x16" href="/branding/favicon/favicon-16x16.png" />
<link rel="icon" type="image/png" sizes="32x32" href="/branding/favicon/favicon-32x32.png" />
<link rel="apple-touch-icon" sizes="180x180" href="/branding/favicon/apple-touch-icon.png" />
<link rel="icon" type="image/png" sizes="192x192" href="/branding/favicon/android-chrome-192x192.png" />
<link rel="icon" type="image/png" sizes="512x512" href="/branding/favicon/android-chrome-512x512.png" />
<link rel="manifest" href="/branding/favicon/site.webmanifest" />
```

---

## 📍 Asset Locations

```
public/branding/
├── logo/
│   ├── cover_logo.png
│   ├── logo.png
│   ├── main_logo.png
│   └── square_logo.png
├── font/
│   ├── centurygothic.ttf
│   └── centurygothic_bold.ttf
└── favicon/
    ├── favicon.ico
    ├── favicon-16x16.png
    ├── favicon-32x32.png
    ├── apple-touch-icon.png
    ├── android-chrome-192x192.png
    ├── android-chrome-512x512.png
    └── site.webmanifest
```

---

## 🚀 Quick Implementation Paths

**Font:** `/branding/font/`  
**Logo:** `/branding/logo/`  
**Favicon:** `/branding/favicon/`

---

**Brand Owner:** CALATECH - Emmanuel Nabwana Shikuku  
**Website:** https://www.calatech.or.ke
