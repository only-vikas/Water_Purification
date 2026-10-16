# 💧 Atomberg Intellon Pro-Sense | atomQUEST 2026 Interactive Pitch Deck

Interactive Single-Page Application (SPA) Pitch Deck submitted for **atomQUEST 2026 (Track 2: Advanced Water Purification)**. Designed for standalone desktop/mobile viewing and embedded full-page integration within Google Sites.

---

## 🌐 Live View & Deployment

- **Google Sites Live Pitch Deck:** [Atomberg Intellon Pro-Sense Google Sites Pitch Page](https://sites.google.com/d/1yUAQaZfN6ALSraDleTOA0ROTqPZegyWw/p/1SVBg66z_91vzvfyy0N_AUrVCsa-9wNyO/edit)
- **GitHub Repository:** [https://github.com/only-vikas/Water_Purification.git](https://github.com/only-vikas/Water_Purification.git)

---

## 📸 Screenshots

### 1. Interactive Hero & Quantified Pain Points

<img width="1862" height="901" alt="image" src="https://github.com/user-attachments/assets/e7f68489-83a8-4fe7-8c91-08ec9ffcdd25" />


Quantified Consumer & Environmental Pain Points
<img width="1861" height="898" alt="image" src="https://github.com/user-attachments/assets/9480b4eb-10f8-4ffe-be30-10e685b4fb3c" />


<br/>

---

### 2. Live Hydraulic Simulator & Performance Matrix
> *Real-time closed-loop mass balance simulator with Chart.js dynamic flow distribution donut and radar analysis.*



Interactive Hydraulic & Electronic Block Diagram
<img width="1851" height="893" alt="image" src="https://github.com/user-attachments/assets/bc9de079-b58b-497d-8605-eafdf9d2d433" />



Baseline vs Target Performance Matrix
<img width="1862" height="898" alt="image" src="https://github.com/user-attachments/assets/f0f5d4a2-cbde-45e8-9913-eae48228cebb" />



<br/>

---

## ✨ Key Features & Web Application Highlights

### 1. 🎨 Fluid Design System & Custom Tokens
- **Atomberg Palette:** Built using custom HSL tokens for deep blue primary trust colors (`hsl(215, 80%, 45%)`), warm orange CTAs (`hsl(28, 90%, 55%)`), and soft neutral raised card surfaces.
- **Responsive Typography:** Clamp-based fluid scale for headers (`.text-display`, `.text-h1`, `.text-h2`) for seamless rendering on mobile, tablet, and ultra-wide screens.

### 2. 📊 Quantified Pain Points with Animated Counters
- **Live Count-Up Visuals:** Dynamic `requestAnimationFrame` + `easeOutExpo` animations showcasing critical consumer metrics:
  - Acoustic noise reduction target: **62 dB ➔ ≤48 dB**
  - Conventional RO brine waste ratio: **300%**
  - Essential mineral stripping ($\text{Ca}^{2+} / \text{Mg}^{2+}$): **95%**
  - Annual consumable saving with SS-316 auto-flush mesh: **₹0**

### 3. 🧩 Solution Bento Grid
Modern 3-card structural grid detailing key engineering mechanisms:
- **Closed-Loop Proportional Blending** ($\alpha = 0.0 \text{ to } 1.0$)
- **Multi-Sensor Telemetry Array** (Dual $\Delta P$, optical turbidity, TDS, pH)
- **Auto-Flush & Tool-Free DIY Servicing** ($< 30\text{s}$ bayonet cartridges)

### 4. 🛠️ Interactive Hydraulic Block Diagram
- Stage-by-stage architecture grid with hover interactions.
- Inspect real-time operational state, active sensors, and fluid routing details without external heavy visual assets.

### 5. ⚡ Live Closed-Loop Hydraulic Control Law Simulator
Embedded mathematical control algorithm:

$$\alpha = \text{clip}\left(\frac{C_{\text{in}} - C_{\text{target}}}{R_{\text{RO}} \cdot C_{\text{in}}}, 0, 1\right)$$

- Adjustable user controls for **Input TDS**, **Optical Turbidity**, **Electrochemical pH**, and **Geogenic Safety Lock**.
- Dynamic real-time calculation of Output TDS, Water Recovery %, and Mineral Retention % synced to a live Chart.js flow allocation donut chart.

### 6. 🎯 Baseline vs Target Performance Matrix & Radar Evaluation
- Comprehensive comparison table contrasting **Standard Fixed RO** vs **Intellon Pro-Sense** vs **BIS IS 10500 standards**.
- Integrated multi-metric comparative Chart.js Radar plot.

### 7. 🚀 Rapid Execution Timeline & Single-Unit BOM
- **₹11,736 Prototype Retail Cost Breakdown** displayed via Chart.js component distribution chart.
- **12-Day Round 2 rapid development roadmap** detailing procurement, assembly, testing, and video submission.

### 8. 🖼️ Google Sites Auto-Resize Compatibility
- Integrated `postMessage` height broadcaster continuously syncing document scroll dimensions to parent iframes to prevent double scrollbars inside Google Sites embeds.

---

## 🛠️ Technology Stack

- **Markup & Layout:** HTML5, Tailwind CSS (via CDN)
- **Data Visualizations:** Chart.js (Canvas-rendered radar, doughnut, and pie charts)
- **Interactivity & State:** Pure Vanilla JavaScript (ES6+, IntersectionObserver, requestAnimationFrame)
- **Typography & Icons:** Native CSS system font stack & Unicode icon indicators

---

## 📁 Repository Structure

```text
Water_Purification/
├── index.html          # Main single-page interactive application
├── README.md           # Repository documentation
└── assets/             # Screenshots and image media
    ├── screenshot1.png # Hero & Problem section screenshot
    └── screenshot2.png # Hydraulic Simulator & Radar section screenshot
```

---

## 🚀 How to Run Locally

1. **Clone this repository:**
   ```bash
   git clone https://github.com/only-vikas/Water_Purification.git
   ```

2. **Navigate into the directory:**
   ```bash
   cd Water_Purification
   ```

3. **Open `index.html`:**
   - Double-click `index.html` in your file explorer to open it in any web browser, or
   - Launch using VS Code / IDE Live Server or local HTTP server:
     ```bash
     npx serve .
     ```

---

## 📜 License & Credits

- Designed & Developed for **atomQUEST 2026 • Track 2 Engineering Pitch**.
- Verified against **WHO Kozisek (2005)** and **BIS IS 10500:2012** drinking water standards.
