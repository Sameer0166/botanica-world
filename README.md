<div align="center">

# 🌱 Botanica World — 220-Species Edible Plant Dual Visual & Audio Encyclopedia

**An interactive, zero-dependency educational atlas pairing 220 living global crops with their harvested edible forms, 10-language voice synthesis, nutrition meal-building labs, and certifiable botany assessments.**

[![Live Demo](https://img.shields.io/badge/Live_Demo-GitHub_Pages-059669?style=for-the-badge&logo=github)](https://sameer0166.github.io/botanica-world/)
[![Companion App](https://img.shields.io/badge/Companion_Atlas-Fauna_%26_Seafood_World_(225_Species)-0f2942?style=for-the-badge)](https://sameer0166.github.io/fauna-world/)
[![Species Count](https://img.shields.io/badge/Botanical_Specimens-220_Species_(440_Visuals)-d97706?style=for-the-badge)]()
[![Zero Dependencies](https://img.shields.io/badge/Architecture-Single--File_Vanilla_HTML5_%2F_CSS3_%2F_ES6-14532d?style=for-the-badge)]()

</div>

---

## 📖 Overview

Most agricultural and culinary resources show either a grocery ingredient on a plate *or* a botanical field guide—rarely side-by-side. **Botanica World** bridges that gap by pairing every single species with **two synchronized visuals**:

1. **Left Visual (`🌿 Living Plant / Tree / Vine`):** How the crop grows in nature (trees, shrubs, climbing vines, paddy grasses, or aquatic roots).
2. **Right Visual (`🍎 Edible Harvest / Crop`):** What is harvested, cooked, and eaten across global kitchens (fruits, vegetables, whole grains, pulses, nuts, seeds, herbs, and spices).

Engineered as a self-contained, single-file web application (`index.html`), it runs offline-ready on low-bandwidth connections, mobile devices, and classroom desktops with zero build steps or external frameworks.

---

## ✨ Key Features & Learning Architecture

### 🖼️ 1. Dual-Visual Discovery Engine (440 Paired Visuals)
* **Multi-Stage Wikimedia & Wikipedia Media Pipeline:** Automatically resolves distinct, non-duplicate real photography for both the living plant and its harvested edible form, with automatic `localStorage` caching (`v5`) and concurrency throttling.
* **Data Saver & Offline Vector Mode:** Instant toggle between **Real Dual Photos** and lightweight, zero-bandwidth **Botanical Vector Diagrams** for offline study or slow connections.
* **Side-by-Side Comparison Tray (`⚖️`):** Pin any two species (e.g., *Turmeric vs. Galangal* or *Quinoa vs. Amaranth*) to compare taxonomy, origins, nutrients, and culinary uses in a split modal.

### 🔊 2. 10-Language Pronunciation & Audio Narrator
* **Web Speech API Integration:** Supports native pronunciation in **English (US, UK, India), Hindi, Spanish, French, German, Arabic, Mandarin Chinese, and Japanese**.
* **Dual-Speed Controls:** Every card includes **🐢 Slow (0.56×)** for syllable-by-syllable phonetic learning and **⚡ Fast (1.02×)** for natural fluency, plus a **Full Lesson Narrator** inside every detail modal.
* **Phonetic Syllable Breakdowns & Letter Tiles:** Visualizes multi-syllable names (e.g., `PO-ME-GRAN-ATE`) and letter-by-letter spelling strips.

### 🧪 3. Interactive Study Modes & Gamified Labs
* **🥗 Interactive Plant Nutrition & Meal-Builder Lab:** Students complete guided dietary missions (e.g., *Vitamin C & Immunity Rainbow Bowl*, *Complete Plant Protein & Iron Thali*, *Brain & Heart Omega-3 Mix*) with **real-time nutrient progress meters** and per-ingredient diagnostic feedback.
* **🃏 Spaced-Repetition Flashcard Deck:** Flip-card practice deck prioritizing starred revision items with one-tap mastery tracking (`✓ Got It!` vs. `🔁 Need Practice`).
* **♾️ Endless 3-Hearts Survival Arena:** High-stakes identification streak challenge with persistent all-time high-score tracking.
* **🎯 6-Mode Quiz Arena & Canvas Certificate Generator:**
  1. *Plant & Harvest Detective*
  2. *Listen & Spell*
  3. *Culinary & World Uses*
  4. *Botanical Nutrition*
  5. *World Origin Geography*
  6. *Grand Botanist Mix*
  * Scoring **≥ 70%** unlocks a custom-rendered HTML5 Canvas **Botanical Mastery Certificate** downloadable as a high-resolution `.png` or printable landscape `.pdf`.

### ♿ 4. Accessibility, Geography & Portable Progress
* **Interactive SVG World Biome Map:** Filter all 220 species across 6 global agricultural cradles (*Americas & New World*, *Mediterranean & Fertile Crescent*, *East & Central Asia*, *Africa & Savanna Tropics*, *Indian Subcontinent*, and *Southeast Asia & Oceania*).
* **Classroom & Study Modes:** Includes **Student Mode** (kid-friendly summaries), **Memory Hide** (blurs names until hover for active recall), **Dark Mode**, **High-Legibility Dyslexia Spacing**, **Print-Optimized 2-Column Study Sheets**, and **Base64 Portable Progress Codes** (`Save / Load Progress`) to transfer mastery across devices without accounts.

---

## 🗂️ Botanical Taxonomy Coverage (220 Species)

| Category | Count | Sub-Groups Covered | Example Specimens |
| :--- | :---: | :--- | :--- |
| **🍎 Fruits** | **52** | Tropical & Subtropical, Citrus, Berries & Arils, Pome & Stone, Melons | Mango, Mangosteen, Key Lime, Pomegranate, Amla, Jackfruit, Fig |
| **🥕 Vegetables** | **54** | Roots & Tubers, Alliums, Leafy Greens, Cruciferous, Nightshades, Gourds, Fungi | Cassava, Lotus Stem, Kohlrabi, Okra, Bitter Gourd, Shiitake |
| **🌾 Grains & Cereals** | **24** | True Cereal Grasses, Millets & Sorghum, Pseudocereals | Basmati Rice, Finger Millet (Ragi), Sorghum, Quinoa, Amaranth, Teff |
| **🫘 Pulses & Legumes** | **24** | Lentils & Split Dals, Dried Beans & Peas, Oilseed & Pod Legumes | Chickpea, Pigeon Pea, Black Gram, Red Kidney Bean, Soybean, Lupini |
| **🌰 Nuts & Seeds** | **24** | Tree Nuts, Groundnuts, Aquatic Nuts, Culinary & Oil Seeds | Walnut, Cashew, Brazil Nut, Fox Nut (Makhana), Flaxseed, Chia, Sabja |
| **🌿 Culinary & Tea Herbs** | **20** | Fresh Culinary Leaves, Woody Mediterranean, Stalks, Medicinal & Tea | Holy Basil (Tulsi), Curry Leaves, Rosemary, Lemongrass, Camellia sinensis |
| **🧂 Aromatic Spices** | **22** | Roots & Rhizomes, Berries & Seeds, Pods & Fruits, Bark & Flowers | Turmeric, Black Pepper, Green Cardamom, Ceylon Cinnamon, Saffron, Vanilla |
| **Total Atlas** | **220** | **25 Botanical Sub-Groups** | **440 Paired Living + Harvest Visuals** |

---

## 🚀 Quick Start & Deployment

Because **Botanica World** is engineered with zero external dependencies, you can run or deploy it in seconds:

### Run Locally
```bash
git clone [https://github.com/Sameer0166/botanica-world.git](https://github.com/Sameer0166/botanica-world.git)
cd botanica-world
# Open index.html directly in any modern browser (Chrome, Edge, Safari, Firefox)
