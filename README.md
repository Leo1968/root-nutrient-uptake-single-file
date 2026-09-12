# How Roots Really Get Nutrients

A single-file, self-contained interactive web explainer on how plant roots acquire nutrients — and why the popular mental image of "roots foraging through the soil" is wrong.

**Live preview:** https://leo1968.github.io/Root-nutrient-uptake/ ([English](https://leo1968.github.io/Root-nutrient-uptake/en.html) · [中文](https://leo1968.github.io/Root-nutrient-uptake/))

## The idea in one sentence

Roots do not actively hunt for nutrients — nutrients are **delivered to the root surface** by three transport mechanisms, and the whole process is embedded in a plant-wide water–carbon coupled system.

## What the page covers

| Section | Content |
|---|---|
| The Myth | Why "root interception" contributes far less than intuition suggests |
| The Scale | The 0.1 → 50 mm distance span across which the mechanisms operate — two orders of magnitude apart |
| The Contribution | Per-nutrient breakdown (N, P, K, etc.) of how much each mechanism supplies versus demand |
| The Mechanisms | Interception, mass flow, and diffusion explained and visualized |
| The Coupling | A whole-plant water–carbon model: transpiration drives xylem flow upward, photosynthates return via the phloem — with an interactive well-watered vs. drought scenario toggle |
| The Implications | What this means for irrigation, fertilization placement, and soil management |
| The References | 11 core sources, checked against the classic literature |

## Features

- **Truly single file** — all media (video, illustrations) are base64-embedded in `index.html`; no external assets, works fully offline
- **Interactive diagrams** — animated SVG flow diagrams; a wet/drought toggle shows how stomata close and the whole water–carbon chain responds
- **No build step, no dependencies** — open `index.html` in any modern browser
- **Responsive** — from phones to desktops; honors `prefers-reduced-motion`

## Run it locally

```bash
git clone https://github.com/Leo1968/Root-nutrient-uptake.git
open Root-nutrient-uptake/index.html   # or just double-click it
```

No server, install, or network connection required.

## Sources

Compiled from *土壤的复杂性及根系吸收养分的关键* ("The Complexity of Soil and the Keys to Nutrient Uptake by Roots"), cross-checked against the classic literature, including:

- Barber, *Soil Nutrient Bioavailability: A Mechanistic Approach*
- Marschner, *Marschner's Mineral Nutrition of Higher Plants*
- Taiz & Zeiger, *Plant Physiology and Development*
- Geelen et al. (2018), *Plant Empowerment: The Basic Principles*

> Note: the page is available in two languages — Chinese (`index.html`) and English (`en.html`). Both are single-file and fully self-contained.

## Credits

Compiled and built by **FoisonX Lab**.

Acknowledgments: **Xiaoyu He**

## License

Released under the [MIT License](LICENSE).
