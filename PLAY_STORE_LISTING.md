# Play Store listing — Maqueen Lite Field Guide (دليل ماكوين لايت الميداني)

Draft copy for Google Play Console "Main store listing" page. Play Console accepts separate translations per language — upload all three.

---

## Metadata (common to all languages)

- **Package name**: `org.workshopdiy.maqueenactivities`
- **Category**: `Books & Reference` (primary), `Education` (secondary if allowed)
- **Tags**: Islamic studies, Arabic, trilingual, education, al-Ghazali
- **Contact email**: `abdelhak.bourdim@gmail.com`
- **Website**: `https://workshop-diy.org`
- **Privacy policy URL**: REQUIRED — host a simple page (see template at end of this file).
- **Content rating**: Everyone (no violence, no gambling, no mature content).
- **Ads**: No.
- **In-app purchases**: No.
- **Data safety**: No data collected, no data shared.

---

## Arabic (ar) — primary

### App name (≤30 chars)
```
دليل ماكوين لايت الميداني
```

### Short description (≤80 chars)
```
٨٥ نشاطًا لروبوت ماكوين لايت — بثلاث لغات.
```

### Full description (≤4000 chars)
```
🤖 دليل ماكوين لايت الميداني — ٨٥ نشاطًا

دليل ميداني للروبوت DFRobot Maqueen Lite v4.

✨ المزايا
• ٨٥ نشاطًا في ٩ فئات
• ستة مسارات تعلم متدرجة
• أكواد جاهزة بـ JavaScript و Python
• اتصال BLE مباشر
• ثلاث لغات (AR/EN/FR)

من workshop-diy.org
```

---

## English (en)

### App name
```
Maqueen Lite Field Guide — Maqueen Lite Field Guide
```

### Short description
```
85 activities for the micro:bit Maqueen Lite robot — trilingual.
```

### Full description
```
🤖 Maqueen Lite Field Guide — 85 Activities

Field guide for the DFRobot Maqueen Lite v4 micro:bit robot.

✨ Features
• 85 activities in 9 categories
• 6 progressive learning paths
• JavaScript + Python code samples
• Direct BLE pairing
• Trilingual EN/FR/AR

From workshop-diy.org
```

---

## French (fr)

### App name
```
Maqueen Lite Field Guide — Maqueen Lite · Guide Terrain
```

### Short description
```
85 activités pour le robot Maqueen Lite — trilingue FR/EN/AR.
```

### Full description
```
🤖 Maqueen Lite Guide Terrain — 85 activités

Guide terrain pour le robot Maqueen Lite v4 micro:bit.

✨ Fonctionnalités
• 85 activités en 9 catégories
• 6 parcours d'apprentissage progressifs
• Code JavaScript + Python
• Appairage BLE direct
• Trilingue FR/EN/AR

De workshop-diy.org
```

---

## Graphics needed (minimum)

| Asset | Size | Source |
|---|---|---|
| App icon | 512×512 PNG | `store-assets/play-store-icon-512.png` (regenerate per book) |
| Feature graphic | 1024×500 PNG | `store-assets/feature-graphic.png` (render from `feature-graphic.html`) |
| Phone screenshots | min 2, 320–3840px, 16:9 portrait | Capture from emulator / real device |
| 7" tablet screenshots (optional) | min 2, 1024×600+ | Run emulator with tablet profile |

Screenshots to capture (book-specific — adjust list to actual app screens):
1. Home / cover / introduction
2. Main content navigation
3. Reading or interaction mode
4. Quiz or self-assessment (if applicable)
5. Theme switch (optional — shows the 3 variants)

---

## Privacy policy template

Copy to a public page (GitHub Pages works). Change email + date.

```
Privacy Policy — Maqueen Lite Field Guide
Last updated: 2026-05-19

The Maqueen Lite Field Guide app does not collect, store, transmit, or share any personal
data. All content is bundled with the app and runs entirely on your device.
The app does not use analytics, advertising networks, crash reporters, or
third-party SDKs.

The app requires no special permissions beyond internet access, which is
used only to load the occasional external link (e.g. workshop-diy.org) if
you tap it — never silently in the background.

If you have questions, contact: abdelhak.bourdim@gmail.com
```
