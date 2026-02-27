# 🏙️ Bangkok CBD Condominiums Explorer

An interactive web app for exploring condominium projects in Bangkok's Central Business District (CBD), built with Vue.js 3 and Leaflet.js. Includes AI-powered semantic search via the OpenAI API.

**[🔗 Live Demo](https://Makers-of-Architecture-Innovations.github.io/bangkok_cbd_condo/index.html)**

![Bangkok CBD Condominiums Explorer](https://img.shields.io/badge/Vue.js-3-42b883?logo=vue.js) ![Leaflet](https://img.shields.io/badge/Leaflet-1.9.4-199900?logo=leaflet) ![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4o--mini-412991?logo=openai) ![License](https://img.shields.io/badge/License-MIT-blue)

---

## ✨ Features

**📋 Table View** — Sortable, filterable data table with color-coded zone badges and price tiers. Filter by zone, developer, price range, and launch year simultaneously.

**🗺️ Map View** — Interactive Leaflet map with OpenStreetMap tiles. Each project is plotted as a color-coded marker (by price tier) with a popup showing key details. The map stays in sync with active filters.

**🤖 AI Semantic Search** — Natural language search in Thai or English powered by GPT-4o-mini. Describe what you're looking for ("luxury condo near BTS with large rooms", "คอนโดหรูสถาปนิกระดับโลก") and the AI ranks the most relevant projects with reasoning.

---

## 📊 Dataset

25 condominium projects in Bangkok's CBD zones covering 2021–2026, including:

| Field | Description |
|-------|-------------|
| ชื่อโครงการ | Project name (Thai & English) |
| สถานที่ | Location / address |
| ดีเวลลอปเปอร์ | Developer |
| สถาปนิก | Architect |
| พื้นที่ขาย | Total sales area (sqm) |
| ราคา/ตร.ม. | Price per sqm (THB) |
| ขนาดห้องเล็กสุด | Minimum unit size (sqm) |
| ขนาดห้องใหญ่สุด | Maximum unit size (sqm) |

**Zones covered:** Sukhumvit · Silom · Sathorn · Ploenchit/Langsuan · Wireless Road · Chidlom · Riverside · Asoke/Rama 4

> ⚠️ **Disclaimer:** Prices and data are approximate estimates based on publicly available information at the time of each project's launch. Always verify directly with developers before making any investment or purchase decisions.

---

## 🚀 Getting Started

### Option 1 — Open directly (no install needed)
Download `Bangkok_CBD_Condominiums.html` and open it in any modern browser. No server required.

### Option 2 — GitHub Pages
1. Fork this repository
2. Go to **Settings → Pages**
3. Set source to `main` branch, `/ (root)` folder
4. Access at `https://your-username.github.io/your-repo-name/Bangkok_CBD_Condominiums.html`

### Using AI Search
1. Get an API key from [platform.openai.com](https://platform.openai.com)
2. Open the **🤖 AI Search** tab
3. Paste your API key (it is never stored or sent anywhere except directly to OpenAI)
4. Type your query in Thai or English and press **ค้นหา**

---

## 🛠️ Tech Stack

- **[Vue.js 3](https://vuejs.org/)** — Reactive UI (loaded via CDN, no build step)
- **[Leaflet.js 1.9](https://leafletjs.com/)** — Interactive maps
- **[OpenStreetMap](https://www.openstreetmap.org/)** — Free map tiles
- **[OpenAI API](https://platform.openai.com/)** — GPT-4o-mini for semantic search

No npm, no build step, no dependencies to install — just a single `.html` file.

---

## 📁 Repository Structure

```
├── Bangkok_CBD_Condominiums.html   # Main web application (self-contained)
├── Bangkok_CBD_Condominiums.xlsx   # Source data in Excel format
├── README.md
└── LICENSE
```

---

## 🤝 Contributing

Contributions are welcome! If you have updated pricing, new projects, or corrections to existing data, please open a Pull Request with your changes and a source reference.

1. Fork the repo
2. Create a branch: `git checkout -b add-new-project`
3. Commit your changes with a source reference in the commit message
4. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see [LICENSE](LICENSE) for details.

Data is compiled from publicly available sources and is provided for informational purposes only.
