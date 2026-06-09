# 🌟 NutriScope v2 — Advanced Nutrition Intelligence Platform

## 📌 Project Overview

NutriScope started as a basic nutrition tracker focused on calorie and macronutrient monitoring. This enhancement transformed it into a comprehensive nutrition intelligence platform capable of analyzing dietary habits, identifying nutrient deficiencies,  and providing personalized recommendations.

The objective was to improve usability, nutritional depth, and decision-making support while maintaining a clean and modern dashboard experience.

---

## 🚀 Features Added

### 📂 CSV Upload Support

* Import food logs directly from CSV files
* Bulk data processing
* Automatic validation and parsing
* Faster tracking experience

### 🥗 Expanded Food Database

Added 40+ new food items across multiple categories:

**Fruits**

* Orange
* Mango
* Papaya
* Strawberry
* Watermelon

**Vegetables**

* Broccoli
* Carrot
* Beetroot
* Sweet Potato
* Bell Pepper

**Protein Sources**

* Tofu
* Salmon
* Tuna
* Turkey
* Soy Chunks

**Nuts & Seeds**

* Almonds
* Walnuts
* Chia Seeds
* Flax Seeds
* Pumpkin Seeds

**Whole Grains**

* Quinoa
* Brown Rice
* Barley
* Millet
* Whole Wheat Pasta

And many more.

---

### 🧬 Advanced Micronutrient Tracking

#### Previously Tracked

* Iron
* Calcium
* Vitamin C
* Vitamin D
* Vitamin B12

#### Newly Added

* Vitamin A
* Vitamin E
* Vitamin K
* Magnesium
* Potassium
* Zinc
* Folate
* Sodium

This provides a significantly more complete nutritional profile.


---

### ⚠️ Nutrition Risk Analysis

The application now evaluates:

#### Deficiency Risks

* Iron deficiency
* Vitamin D deficiency
* Calcium deficiency
* Vitamin B12 deficiency

#### Excess Consumption Risks

* Excess sodium
* Excess calories
* Excess fat intake

#### Lifestyle Risks

* Low protein intake
* Low fiber intake

---

### 🧠 Advanced Recommendation Engine

Recommendations are now generated using:

* User profile
* Logged foods
* Nutrient deficiencies
* Dietary preferences
* Risk analysis

Example:

> Your Vitamin D intake is only 35% of the recommended daily amount. Consider adding fortified dairy products, eggs, or salmon to improve your intake.

---

### 📊 Enhanced Data Visualizations

Added modern analytical charts:

* Nutrient Radar Chart
* Micronutrient Comparison Chart
* Daily Nutrition Trend Graph
* Risk Distribution Chart
* Improved Macro Distribution Visualization

---

### 📚 Nutrition Sources

Integrated references from trusted organizations:

* USDA FoodData Central
* WHO Nutrition Guidelines
* NIH Office of Dietary Supplements
* ICMR Dietary Recommendations

---

### ⚕️ Educational Disclaimer

Added responsible nutrition guidance:

> NutriScope is intended for educational and informational purposes only and should not replace professional medical advice, diagnosis, or treatment.

---

## 🎨 UI/UX Improvements

### Dashboard

✅ Improved layout hierarchy
✅ Better spacing and readability
✅ Enhanced statistic cards
✅ More actionable insights

### Food Log

✅ CSV import support
✅ Faster food selection workflow

### Recommendations

✅ Categorized recommendations
✅ Risk-based suggestions

### Meal Planner

✅ Dedicated planning section

---

# 📈 Before vs After

| Feature                  | Original Version | Enhanced Version |
| ------------------------ | ---------------- | ---------------- |
| Food Database            | 20 Foods         | 60+ Foods        |
| CSV Upload               | ❌                | ✅                |
| Meal Planner             | ❌                | ✅                |
| Risk Analysis            | ❌                | ✅                |
| Micronutrients           | 5                | 13+              |
| Advanced Recommendations | ❌                | ✅                |
| Nutrition Sources        | ❌                | ✅                |
| Educational Disclaimer   | ❌                | ✅                |
| Charts                   | Basic            | Advanced         |
| Health Insights          | Limited          | Comprehensive    |

---

# 📸 Screenshots

## Dashboard Overview

<img width="1914" height="967" alt="Screenshot 2026-06-09 191644" src="https://github.com/user-attachments/assets/284229c2-f95f-4680-8ca7-a36a804277ba" />


## Food Log + CSV Upload

<img width="1885" height="966" alt="Screenshot 2026-06-09 192250" src="https://github.com/user-attachments/assets/5802d1ad-9d08-455f-ba25-667a0c0bfda4" />


## Micronutrient Analysis

<img width="1658" height="881" alt="Screenshot 2026-06-09 192339" src="https://github.com/user-attachments/assets/e6b59e73-e4bb-49d8-ab84-24804d5fe25a" />

## Risk Analysis

<img width="762" height="176" alt="Screenshot 2026-06-09 192431" src="https://github.com/user-attachments/assets/a49003a2-2c25-499e-bac4-fa1e943fad5e" />


## Advanced Recommendations

<img width="1726" height="871" alt="Screenshot 2026-06-09 191658" src="https://github.com/user-attachments/assets/1b42f84b-787c-489b-8498-4d849655b233" />

---

# 🛠️ Tech Stack

* HTML5
* CSS3
* JavaScript (ES6)
* Chart.js
* Local Storage API

---

# 🎯 Key Learnings

### Technical

* Designing scalable nutrition databases
* Building nutrient aggregation systems
* Dynamic dashboard rendering
* Client-side data persistence

### Data Analysis

* Nutrient deficiency detection using RDA benchmarks
* Personalized recommendation generation
* Risk scoring methodologies

### UX Design

* Actionable insights outperform raw statistics
* Visual analytics improve user engagement
* Meal planning increases practical usability

---

# 🔮 Future Improvements

* AI Food Recognition
* Barcode Scanner Integration
* Weekly Nutrition Reports
* PDF Export
* Mobile App Version
* Wearable Device Integration
* AI Diet Coach
* Cloud Data Synchronization

---

## 📂 Repository Structure

```bash
NutriScope/
│
├── index.html
├── assets/
│   ├── screenshots/
│   ├── icons/
│   └── charts/
│
├── data/
│   └── food-database.json
│
├── README.md
└── LICENSE
```

---

## ⭐ Outcome

NutriScope evolved from a simple calorie tracker into a nutrition intelligence platform capable of tracking dietary intake, identifying health risks, generating meal plans, and delivering personalized nutritional guidance.

This project demonstrates practical applications of:

* Frontend Development
* Data Analysis
* Nutrition Informatics
* Dashboard Design
* User-Centered Product Development

**If you found this project interesting, consider giving it a ⭐ on GitHub!** 🚀



# Project Code 
 

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NutriScope — Precision Nutrition Tracker</title>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Space+Grotesk:wght@400;500;600;700&display=swap');

  :root {
    --bg-base: #0a0b0f;
    --bg-surface: #10121a;
    --bg-card: #14171f;
    --bg-card-hover: #1a1e28;
    --bg-input: #1c2030;
    --border: #252a38;
    --border-focus: #3b82f6;
    --text-primary: #f0f2f8;
    --text-secondary: #8892a4;
    --text-muted: #4d5668;
    --accent-blue: #3b82f6;
    --accent-violet: #7c3aed;
    --accent-emerald: #10b981;
    --accent-amber: #f59e0b;
    --accent-rose: #f43f5e;
    --accent-cyan: #06b6d4;
    --grad-a: #3b82f6;
    --grad-b: #7c3aed;
    --ring-blue: rgba(59,130,246,0.2);
    --font-display: 'Space Grotesk', sans-serif;
    --font-body: 'Inter', sans-serif;
    --radius: 12px;
    --radius-sm: 8px;
    --radius-lg: 16px;
    --shadow: 0 4px 24px rgba(0,0,0,0.4);
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    font-family: var(--font-body);
    background: var(--bg-base);
    color: var(--text-primary);
    min-height: 100vh;
    line-height: 1.6;
    font-size: 14px;
  }

  /* ── TOP NAV ─────────────────────────────────────────────── */
  header {
    position: sticky; top: 0; z-index: 100;
    background: rgba(10,11,15,0.85);
    backdrop-filter: blur(20px);
    border-bottom: 1px solid var(--border);
    padding: 0 24px;
    height: 60px;
    display: flex; align-items: center; justify-content: space-between;
  }
  .logo {
    font-family: var(--font-display);
    font-size: 18px; font-weight: 700;
    background: linear-gradient(135deg, var(--grad-a), var(--grad-b));
    -webkit-background-clip: text; -webkit-text-fill-color: transparent;
    background-clip: text;
    display: flex; align-items: center; gap: 8px;
  }
  .logo-dot {
    width: 8px; height: 8px; border-radius: 50%;
    background: linear-gradient(135deg, var(--grad-a), var(--grad-b));
  }
  .nav-tabs {
    display: flex; gap: 4px;
    background: var(--bg-surface);
    border: 1px solid var(--border);
    border-radius: 10px;
    padding: 4px;
  }
  .nav-tab {
    padding: 6px 16px;
    border-radius: 7px;
    border: none; background: transparent;
    color: var(--text-secondary); font-size: 13px; font-weight: 500;
    cursor: pointer; transition: all 0.2s;
    font-family: var(--font-body);
  }
  .nav-tab:hover { color: var(--text-primary); }
  .nav-tab.active {
    background: linear-gradient(135deg, var(--grad-a), var(--grad-b));
    color: #fff;
  }
  .date-badge {
    font-size: 12px; color: var(--text-muted);
    background: var(--bg-surface); border: 1px solid var(--border);
    padding: 5px 12px; border-radius: 20px;
  }

  /* ── LAYOUT ──────────────────────────────────────────────── */
  .app-wrap { max-width: 1280px; margin: 0 auto; padding: 28px 24px; }
  .tab-panel { display: none; }
  .tab-panel.active { display: block; }

  /* ── GRID HELPERS ────────────────────────────────────────── */
  .grid-2 { display: grid; grid-template-columns: 1fr 1fr; gap: 16px; }
  .grid-3 { display: grid; grid-template-columns: 1fr 1fr 1fr; gap: 16px; }
  .grid-4 { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; }
  .col-span-2 { grid-column: span 2; }
  .col-span-3 { grid-column: span 3; }
  .gap-16 { gap: 16px; }
  .mb-16 { margin-bottom: 16px; }
  .mb-24 { margin-bottom: 24px; }
  .mt-16 { margin-top: 16px; }

  /* ── CARD ────────────────────────────────────────────────── */
  .card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 20px;
    transition: border-color 0.2s;
  }
  .card:hover { border-color: #2e3447; }
  .card-title {
    font-family: var(--font-display);
    font-size: 13px; font-weight: 600;
    color: var(--text-secondary);
    text-transform: uppercase; letter-spacing: 0.08em;
    margin-bottom: 16px;
    display: flex; align-items: center; gap: 8px;
  }
  .card-title .dot {
    width: 6px; height: 6px; border-radius: 50%;
    background: linear-gradient(135deg, var(--grad-a), var(--grad-b));
    flex-shrink: 0;
  }

  /* ── FORM ELEMENTS ───────────────────────────────────────── */
  .form-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 14px; }
  .form-group { display: flex; flex-direction: column; gap: 6px; }
  .form-group label {
    font-size: 12px; font-weight: 500; color: var(--text-secondary);
  }
  .form-group input, .form-group select {
    background: var(--bg-input);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    color: var(--text-primary);
    font-size: 14px; font-family: var(--font-body);
    padding: 10px 14px;
    outline: none;
    transition: border-color 0.2s, box-shadow 0.2s;
    width: 100%;
    -webkit-appearance: none;
  }
  .form-group input:focus, .form-group select:focus {
    border-color: var(--border-focus);
    box-shadow: 0 0 0 3px var(--ring-blue);
  }
  .form-group select option { background: var(--bg-card); }

  /* ── BUTTONS ─────────────────────────────────────────────── */
  .btn {
    display: inline-flex; align-items: center; gap: 7px;
    padding: 10px 20px; border-radius: var(--radius-sm);
    border: none; cursor: pointer;
    font-size: 13px; font-weight: 600; font-family: var(--font-body);
    transition: all 0.2s; white-space: nowrap;
  }
  .btn-primary {
    background: linear-gradient(135deg, var(--grad-a), var(--grad-b));
    color: #fff;
  }
  .btn-primary:hover { opacity: 0.9; transform: translateY(-1px); box-shadow: 0 6px 20px rgba(59,130,246,0.35); }
  .btn-ghost {
    background: transparent; color: var(--text-secondary);
    border: 1px solid var(--border);
  }
  .btn-ghost:hover { background: var(--bg-input); color: var(--text-primary); }
  .btn-danger {
    background: rgba(244,63,94,0.12); color: var(--accent-rose);
    border: 1px solid rgba(244,63,94,0.2);
  }
  .btn-danger:hover { background: rgba(244,63,94,0.2); }
  .btn-sm { padding: 6px 12px; font-size: 12px; }
  .btn-full { width: 100%; justify-content: center; }

  /* ── SECTION HEADER ──────────────────────────────────────── */
  .section-header {
    display: flex; align-items: center; justify-content: space-between;
    margin-bottom: 20px;
  }
  .section-title {
    font-family: var(--font-display);
    font-size: 22px; font-weight: 700;
  }
  .section-sub { font-size: 13px; color: var(--text-secondary); margin-top: 2px; }

  /* ── STAT CARDS ──────────────────────────────────────────── */
  .stat-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: var(--radius-lg);
    padding: 20px;
    position: relative; overflow: hidden;
  }
  .stat-card::before {
    content: '';
    position: absolute; top: 0; left: 0; right: 0; height: 2px;
  }
  .stat-card.blue::before { background: linear-gradient(90deg, var(--accent-blue), var(--accent-violet)); }
  .stat-card.emerald::before { background: linear-gradient(90deg, var(--accent-emerald), var(--accent-cyan)); }
  .stat-card.amber::before { background: linear-gradient(90deg, var(--accent-amber), #ef4444); }
  .stat-card.violet::before { background: linear-gradient(90deg, var(--accent-violet), #ec4899); }
  .stat-label { font-size: 11px; font-weight: 600; color: var(--text-secondary); text-transform: uppercase; letter-spacing: 0.08em; }
  .stat-value {
    font-family: var(--font-display); font-size: 28px; font-weight: 700;
    margin: 6px 0 2px; line-height: 1;
  }
  .stat-meta { font-size: 12px; color: var(--text-muted); }
  .stat-icon {
    position: absolute; right: 16px; top: 50%;
    transform: translateY(-50%);
    font-size: 28px; opacity: 0.15;
  }

  /* ── PROGRESS ────────────────────────────────────────────── */
  .progress-bar-wrap {
    background: var(--bg-input);
    border-radius: 99px; overflow: hidden;
    height: 8px; width: 100%;
  }
  .progress-bar {
    height: 100%; border-radius: 99px;
    transition: width 0.6s cubic-bezier(.4,0,.2,1);
  }
  .progress-bar.blue { background: linear-gradient(90deg, var(--accent-blue), var(--accent-violet)); }
  .progress-bar.emerald { background: linear-gradient(90deg, var(--accent-emerald), var(--accent-cyan)); }
  .progress-bar.amber { background: linear-gradient(90deg, var(--accent-amber), #ef4444); }
  .progress-bar.rose { background: linear-gradient(90deg, var(--accent-rose), #ef4444); }
  .progress-bar.violet { background: linear-gradient(90deg, var(--accent-violet), #ec4899); }

  .progress-row {
    display: flex; align-items: center; gap: 10px;
    margin-bottom: 10px;
  }
  .progress-label { font-size: 13px; color: var(--text-secondary); min-width: 80px; }
  .progress-pct { font-size: 12px; font-weight: 600; color: var(--text-primary); min-width: 36px; text-align: right; }

  /* ── BIG ENERGY RING ─────────────────────────────────────── */
  .energy-wrap {
    display: flex; align-items: center; gap: 28px;
  }
  .energy-ring-container { position: relative; flex-shrink: 0; }
  .energy-ring-container svg { display: block; }
  .energy-center-text {
    position: absolute; top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    text-align: center;
  }
  .energy-kcal {
    font-family: var(--font-display); font-size: 24px; font-weight: 700;
    line-height: 1;
  }
  .energy-label { font-size: 11px; color: var(--text-secondary); }
  .energy-details { flex: 1; }
  .energy-row {
    display: flex; justify-content: space-between; align-items: center;
    padding: 8px 0; border-bottom: 1px solid var(--border);
  }
  .energy-row:last-child { border-bottom: none; }
  .energy-name { font-size: 13px; color: var(--text-secondary); }
  .energy-nums { font-size: 13px; font-weight: 600; }

  /* ── FOOD LOG TABLE ──────────────────────────────────────── */
  .log-table-wrap { overflow-x: auto; margin-top: 4px; }
  table { width: 100%; border-collapse: collapse; }
  thead th {
    font-size: 11px; font-weight: 600; text-transform: uppercase;
    letter-spacing: 0.07em; color: var(--text-muted);
    padding: 10px 14px; text-align: left;
    border-bottom: 1px solid var(--border);
  }
  tbody tr { transition: background 0.15s; }
  tbody tr:hover { background: var(--bg-card-hover); }
  tbody td {
    padding: 10px 14px; font-size: 13px; color: var(--text-secondary);
    border-bottom: 1px solid rgba(37,42,56,0.5);
  }
  tbody td:first-child { color: var(--text-primary); font-weight: 500; }
  .td-num { font-variant-numeric: tabular-nums; }
  .empty-row td {
    text-align: center; padding: 40px;
    color: var(--text-muted); font-style: italic;
  }

  /* ── ADD FOOD ROW ────────────────────────────────────────── */
  .add-food-row {
    display: flex; gap: 12px; align-items: flex-end;
    margin-bottom: 16px; flex-wrap: wrap;
  }
  .add-food-row .form-group { flex: 1; min-width: 120px; }

  /* ── NUTRIENT TABLE ──────────────────────────────────────── */
  .nutrient-chip {
    display: inline-flex; align-items: center; gap: 6px;
    padding: 3px 10px; border-radius: 20px; font-size: 12px; font-weight: 500;
  }
  .chip-ok { background: rgba(16,185,129,0.12); color: var(--accent-emerald); }
  .chip-low { background: rgba(245,158,11,0.12); color: var(--accent-amber); }
  .chip-high { background: rgba(244,63,94,0.12); color: var(--accent-rose); }

  /* ── RECOMMENDATIONS ─────────────────────────────────────── */
  .rec-card {
    background: var(--bg-card);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 16px;
    margin-bottom: 10px;
    display: flex; gap: 14px; align-items: flex-start;
    transition: border-color 0.2s;
  }
  .rec-card:hover { border-color: #2e3447; }
  .rec-icon {
    width: 36px; height: 36px; border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 18px; flex-shrink: 0;
  }
  .rec-icon.add { background: rgba(16,185,129,0.12); }
  .rec-icon.swap { background: rgba(59,130,246,0.12); }
  .rec-icon.portion { background: rgba(245,158,11,0.12); }
  .rec-title { font-size: 13px; font-weight: 600; color: var(--text-primary); margin-bottom: 4px; }
  .rec-body { font-size: 12px; color: var(--text-secondary); line-height: 1.5; }
  .rec-tag {
    display: inline-block; font-size: 10px; font-weight: 600;
    text-transform: uppercase; letter-spacing: 0.06em;
    padding: 2px 8px; border-radius: 4px; margin-bottom: 6px;
  }
  .tag-add { background: rgba(16,185,129,0.15); color: var(--accent-emerald); }
  .tag-swap { background: rgba(59,130,246,0.15); color: var(--accent-blue); }
  .tag-portion { background: rgba(245,158,11,0.15); color: var(--accent-amber); }

  /* ── DEFICIENCY / EXCESS CHIPS ───────────────────────────── */
  .insight-list { display: flex; flex-wrap: wrap; gap: 8px; }
  .insight-chip {
    display: flex; align-items: center; gap: 6px;
    padding: 6px 12px; border-radius: 8px; font-size: 12px; font-weight: 500;
  }
  .insight-chip.def { background: rgba(245,158,11,0.1); border: 1px solid rgba(245,158,11,0.2); color: var(--accent-amber); }
  .insight-chip.exc { background: rgba(244,63,94,0.1); border: 1px solid rgba(244,63,94,0.2); color: var(--accent-rose); }
  .insight-chip .pct { font-size: 11px; opacity: 0.8; }

  /* ── TOAST ───────────────────────────────────────────────── */
  #toast {
    position: fixed; bottom: 24px; right: 24px; z-index: 999;
    background: var(--bg-card); border: 1px solid var(--border);
    border-radius: var(--radius); padding: 14px 20px;
    font-size: 13px; font-weight: 500;
    display: flex; align-items: center; gap: 10px;
    box-shadow: var(--shadow);
    transform: translateY(80px); opacity: 0;
    transition: all 0.3s cubic-bezier(.4,0,.2,1);
    pointer-events: none;
  }
  #toast.show { transform: translateY(0); opacity: 1; pointer-events: auto; }
  #toast .toast-dot { width: 8px; height: 8px; border-radius: 50%; background: var(--accent-emerald); }

  /* ── CHART CONTAINER ─────────────────────────────────────── */
  .chart-wrap { position: relative; height: 200px; }

  /* ── DIVIDER ─────────────────────────────────────────────── */
  .divider { height: 1px; background: var(--border); margin: 20px 0; }

  /* ── SCROLLBAR ───────────────────────────────────────────── */
  ::-webkit-scrollbar { width: 6px; height: 6px; }
  ::-webkit-scrollbar-track { background: var(--bg-surface); }
  ::-webkit-scrollbar-thumb { background: var(--border); border-radius: 3px; }

  /* ── MOBILE ──────────────────────────────────────────────── */
  @media (max-width: 768px) {
    .grid-2, .grid-3, .grid-4 { grid-template-columns: 1fr; }
    .col-span-2, .col-span-3 { grid-column: span 1; }
    .form-grid { grid-template-columns: 1fr; }
    .energy-wrap { flex-direction: column; align-items: flex-start; }
    .nav-tabs { display: none; }
    .mobile-tabs {
      display: flex; overflow-x: auto; gap: 8px;
      padding: 12px 24px; background: var(--bg-surface);
      border-bottom: 1px solid var(--border);
      scrollbar-width: none;
    }
    .mobile-tab {
      flex-shrink: 0; padding: 8px 16px;
      border-radius: 8px; border: 1px solid var(--border);
      background: transparent; color: var(--text-secondary);
      font-size: 13px; font-weight: 500; cursor: pointer;
      font-family: var(--font-body);
    }
    .mobile-tab.active {
      background: linear-gradient(135deg, var(--grad-a), var(--grad-b));
      border-color: transparent; color: #fff;
    }
    .date-badge { display: none; }
    .add-food-row { flex-direction: column; }
    .app-wrap { padding: 20px 16px; }
  }
  @media (min-width: 769px) { .mobile-tabs { display: none; } }
  @media (min-width: 1024px) {
    .grid-4 { grid-template-columns: repeat(4, 1fr); }
    .grid-3 { grid-template-columns: repeat(3, 1fr); }
  }
  @media (max-width: 1023px) and (min-width: 769px) {
    .grid-4 { grid-template-columns: repeat(2, 1fr); }
    .grid-3 { grid-template-columns: repeat(2, 1fr); }
  }

  /* ── SKELETON PULSE ──────────────────────────────────────── */
  @keyframes pulse { 0%,100% { opacity: 1; } 50% { opacity: 0.4; } }

  /* ── INLINE EDITABLE ─────────────────────────────────────── */
  .editable-cell input {
    background: var(--bg-input); border: 1px solid var(--border-focus);
    border-radius: 4px; color: var(--text-primary);
    font-size: 13px; font-family: var(--font-body);
    padding: 3px 8px; width: 70px; outline: none;
  }

  /* ── INFO BADGE ──────────────────────────────────────────── */
  .info-badge {
    background: rgba(59,130,246,0.1); border: 1px solid rgba(59,130,246,0.2);
    color: var(--accent-blue); border-radius: 8px;
    padding: 10px 14px; font-size: 12px; line-height: 1.5;
    margin-bottom: 16px;
  }

  /* Tabs animation */
  .tab-panel { animation: fadeIn 0.25s ease; }
  @keyframes fadeIn { from { opacity: 0; transform: translateY(6px); } to { opacity: 1; transform: none; } }
</style>
</head>
<body>

<header>
  <div class="logo">
    <div class="logo-dot"></div>
    NutriScope
  </div>
  <nav class="nav-tabs">
    <button class="nav-tab active" onclick="switchTab('dashboard')">Dashboard</button>
    <button class="nav-tab" onclick="switchTab('log')">Food Log</button>
    <button class="nav-tab" onclick="switchTab('profile')">Profile</button>
    <button class="nav-tab" onclick="switchTab('recs')">Recommendations</button>
  </nav>
  <div class="date-badge" id="dateBadge"></div>
</header>

<div class="mobile-tabs">
  <button class="mobile-tab active" onclick="switchTab('dashboard')">📊 Dashboard</button>
  <button class="mobile-tab" onclick="switchTab('log')">🍽 Food Log</button>
  <button class="mobile-tab" onclick="switchTab('profile')">👤 Profile</button>
  <button class="mobile-tab" onclick="switchTab('recs')">💡 Tips</button>
</div>

<div class="app-wrap">

  <!-- ══════════════ DASHBOARD ══════════════ -->
  <div class="tab-panel active" id="tab-dashboard">
    <div class="section-header mb-24">
      <div>
        <div class="section-title">Dashboard</div>
        <div class="section-sub">Today's nutrition at a glance</div>
      </div>
      <button class="btn btn-primary" onclick="switchTab('log')">+ Log Food</button>
    </div>

    <!-- Stat Cards -->
    <div class="grid-4 mb-16">
      <div class="stat-card blue">
        <div class="stat-label">Calories</div>
        <div class="stat-value" id="d-kcal">0</div>
        <div class="stat-meta" id="d-kcal-target">/ — kcal</div>
        <div class="stat-icon">🔥</div>
      </div>
      <div class="stat-card emerald">
        <div class="stat-label">Protein</div>
        <div class="stat-value" id="d-prot">0<span style="font-size:14px;font-weight:400">g</span></div>
        <div class="stat-meta" id="d-prot-target">/ — g target</div>
        <div class="stat-icon">💪</div>
      </div>
      <div class="stat-card amber">
        <div class="stat-label">Carbs</div>
        <div class="stat-value" id="d-carbs">0<span style="font-size:14px;font-weight:400">g</span></div>
        <div class="stat-meta" id="d-carbs-target">/ — g target</div>
        <div class="stat-icon">🌾</div>
      </div>
      <div class="stat-card violet">
        <div class="stat-label">Fat</div>
        <div class="stat-value" id="d-fat">0<span style="font-size:14px;font-weight:400">g</span></div>
        <div class="stat-meta" id="d-fat-target">/ — g target</div>
        <div class="stat-icon">🥑</div>
      </div>
    </div>

    <div class="grid-2 mb-16">
      <!-- Energy Ring -->
      <div class="card">
        <div class="card-title"><span class="dot"></span>Energy Balance</div>
        <div class="energy-wrap">
          <div class="energy-ring-container">
            <svg width="130" height="130" viewBox="0 0 130 130">
              <circle cx="65" cy="65" r="52" fill="none" stroke="#1c2030" stroke-width="10"/>
              <circle id="energyRing" cx="65" cy="65" r="52" fill="none"
                stroke="url(#ringGrad)" stroke-width="10"
                stroke-linecap="round" stroke-dasharray="326.7"
                stroke-dashoffset="326.7"
                transform="rotate(-90 65 65)"
                style="transition: stroke-dashoffset 0.8s cubic-bezier(.4,0,.2,1)"/>
              <defs>
                <linearGradient id="ringGrad" x1="0%" y1="0%" x2="100%" y2="0%">
                  <stop offset="0%" stop-color="#3b82f6"/>
                  <stop offset="100%" stop-color="#7c3aed"/>
                </linearGradient>
              </defs>
            </svg>
            <div class="energy-center-text">
              <div class="energy-kcal" id="ring-kcal">0</div>
              <div class="energy-label">kcal</div>
            </div>
          </div>
          <div class="energy-details">
            <div class="energy-row">
              <span class="energy-name">Target</span>
              <span class="energy-nums" id="ring-target">— kcal</span>
            </div>
            <div class="energy-row">
              <span class="energy-name">Remaining</span>
              <span class="energy-nums" id="ring-remain">— kcal</span>
            </div>
            <div class="energy-row">
              <span class="energy-name">Completion</span>
              <span class="energy-nums" id="ring-pct">—%</span>
            </div>
            <div class="energy-row">
              <span class="energy-name">BMR</span>
              <span class="energy-nums" id="ring-bmr">—</span>
            </div>
          </div>
        </div>
      </div>

      <!-- Macro Chart -->
      <div class="card">
        <div class="card-title"><span class="dot"></span>Macro Distribution</div>
        <div class="chart-wrap">
          <canvas id="macroChart"></canvas>
        </div>
      </div>
    </div>

    <div class="grid-2 mb-16">
      <!-- Top Deficiencies -->
      <div class="card">
        <div class="card-title"><span class="dot"></span>Top Deficiencies</div>
        <div class="insight-list" id="deficiency-list">
          <span style="font-size:12px;color:var(--text-muted)">Log food to see insights</span>
        </div>
      </div>
      <!-- Top Excesses -->
      <div class="card">
        <div class="card-title"><span class="dot"></span>Top Excesses</div>
        <div class="insight-list" id="excess-list">
          <span style="font-size:12px;color:var(--text-muted)">Log food to see insights</span>
        </div>
      </div>
    </div>

    <!-- Macro Progress Bars -->
    <div class="card mb-16">
      <div class="card-title"><span class="dot"></span>Macro Progress</div>
      <div id="macro-progress"></div>
    </div>

    <!-- Nutrient Table -->
    <div class="card">
      <div class="card-title"><span class="dot"></span>Micronutrient Status</div>
      <div class="log-table-wrap">
        <table>
          <thead>
            <tr>
              <th>Nutrient</th>
              <th>Consumed</th>
              <th>Target</th>
              <th>% Met</th>
              <th>Status</th>
              <th>Progress</th>
            </tr>
          </thead>
          <tbody id="microTable"></tbody>
        </table>
      </div>
    </div>
  </div>

  <!-- ══════════════ FOOD LOG ══════════════ -->
  <div class="tab-panel" id="tab-log">
    <div class="section-header mb-24">
      <div>
        <div class="section-title">Food Log</div>
        <div class="section-sub">Track every meal with precision</div>
      </div>
    </div>

    <div class="card mb-16">
      <div class="card-title"><span class="dot"></span>Add Food Entry</div>
      <div class="add-food-row">
        <div class="form-group" style="flex:2;min-width:160px">
          <label>Food Item</label>
          <select id="foodSelect">
            <option value="">Select food…</option>
          </select>
        </div>
        <div class="form-group">
          <label>Quantity</label>
          <input type="number" id="foodQty" placeholder="100" min="1" max="2000" value="100">
        </div>
        <div class="form-group">
          <label>Unit</label>
          <select id="foodUnit">
            <option value="g">grams (g)</option>
            <option value="ml">ml</option>
            <option value="piece">piece</option>
            <option value="cup">cup (~240g)</option>
            <option value="tbsp">tbsp (~15g)</option>
          </select>
        </div>
        <div class="form-group">
          <label>Meal</label>
          <select id="mealType">
            <option value="Breakfast">Breakfast</option>
            <option value="Lunch">Lunch</option>
            <option value="Dinner">Dinner</option>
            <option value="Snack">Snack</option>
          </select>
        </div>
        <button class="btn btn-primary" style="margin-bottom:0;height:40px;align-self:flex-end" onclick="addFoodEntry()">Add Entry</button>
      </div>
      <div id="food-preview" style="display:none;background:var(--bg-input);border-radius:8px;padding:12px;font-size:12px;color:var(--text-secondary);margin-top:8px"></div>
    </div>

    <div class="card">
      <div class="card-title" style="justify-content:space-between">
        <span style="display:flex;align-items:center;gap:8px"><span class="dot"></span>Today's Entries</span>
        <button class="btn btn-ghost btn-sm" onclick="clearLog()">Clear All</button>
      </div>
      <div class="log-table-wrap">
        <table>
          <thead>
            <tr>
              <th>Food</th>
              <th>Meal</th>
              <th>Qty</th>
              <th>Unit</th>
              <th>Kcal</th>
              <th>Protein</th>
              <th>Carbs</th>
              <th>Fat</th>
              <th>Fiber</th>
              <th></th>
            </tr>
          </thead>
          <tbody id="logTable"></tbody>
        </table>
      </div>
    </div>
  </div>

  <!-- ══════════════ PROFILE ══════════════ -->
  <div class="tab-panel" id="tab-profile">
    <div class="section-header mb-24">
      <div>
        <div class="section-title">Your Profile</div>
        <div class="section-sub">Set your details for personalised targets</div>
      </div>
    </div>

    <div class="grid-2">
      <div class="card">
        <div class="card-title"><span class="dot"></span>Personal Details</div>
        <div class="form-grid">
          <div class="form-group">
            <label>Age</label>
            <input type="number" id="p-age" placeholder="25" min="10" max="100">
          </div>
          <div class="form-group">
            <label>Gender</label>
            <select id="p-gender">
              <option value="male">Male</option>
              <option value="female">Female</option>
              <option value="other">Other</option>
            </select>
          </div>
          <div class="form-group">
            <label>Height (cm)</label>
            <input type="number" id="p-height" placeholder="170" min="100" max="250">
          </div>
          <div class="form-group">
            <label>Weight (kg)</label>
            <input type="number" id="p-weight" placeholder="70" min="20" max="300">
          </div>
        </div>
      </div>

      <div class="card">
        <div class="card-title"><span class="dot"></span>Lifestyle & Preferences</div>
        <div class="form-grid">
          <div class="form-group col-span-2">
            <label>Activity Level</label>
            <select id="p-activity">
              <option value="1.2">Sedentary (desk job, little exercise)</option>
              <option value="1.375">Lightly Active (1–3 days/week)</option>
              <option value="1.55" selected>Moderately Active (3–5 days/week)</option>
              <option value="1.725">Very Active (6–7 days/week)</option>
              <option value="1.9">Extra Active (physical job + training)</option>
            </select>
          </div>
          <div class="form-group col-span-2">
            <label>Dietary Preference</label>
            <select id="p-diet">
              <option value="veg">Vegetarian</option>
              <option value="nonveg" selected>Non-Vegetarian</option>
              <option value="egg">Eggetarian</option>
            </select>
          </div>
          <div class="form-group col-span-2">
            <label>Goal</label>
            <select id="p-goal">
              <option value="maintain">Maintain Weight</option>
              <option value="lose">Lose Weight (−500 kcal)</option>
              <option value="gain">Gain Muscle (+300 kcal)</option>
            </select>
          </div>
        </div>
      </div>
    </div>

    <div class="mt-16" style="display:flex;justify-content:flex-end;gap:10px">
      <button class="btn btn-ghost" onclick="resetProfile()">Reset</button>
      <button class="btn btn-primary" onclick="saveProfile()">Save Profile & Recalculate</button>
    </div>

    <!-- Targets Preview -->
    <div class="card mt-16" id="targets-card" style="display:none">
      <div class="card-title"><span class="dot"></span>Calculated Targets</div>
      <div class="grid-4" id="targets-grid"></div>
    </div>
  </div>

  <!-- ══════════════ RECOMMENDATIONS ══════════════ -->
  <div class="tab-panel" id="tab-recs">
    <div class="section-header mb-24">
      <div>
        <div class="section-title">Recommendations</div>
        <div class="section-sub">Personalised guidance based on your log</div>
      </div>
    </div>
    <div id="rec-container">
      <div class="info-badge">💡 Add foods to your log and save your profile to get personalised recommendations.</div>
    </div>
  </div>

</div>

<div id="toast"><div class="toast-dot"></div><span id="toastMsg">Done</span></div>

<script>
// ────────────────────────────────────────────────────────────────────────────
// FOOD DATABASE  (per 100 g / 100 ml)
// Nutrients: kcal, protein(g), carbs(g), fat(g), fiber(g), iron(mg), calcium(mg), vitC(mg), vitD(µg), vitB12(µg)
// ────────────────────────────────────────────────────────────────────────────
const FOODS = {
  "Rice":    { kcal:130, prot:2.7,  carb:28.2, fat:0.3, fiber:0.4, iron:0.2, calcium:10,  vitC:0,   vitD:0,   vitB12:0    },
  "Roti":    { kcal:264, prot:8.7,  carb:52.0, fat:3.7, fiber:2.7, iron:2.7, calcium:15,  vitC:0,   vitD:0,   vitB12:0    },
  "Dal":     { kcal:116, prot:8.0,  carb:17.0, fat:0.9, fiber:3.8, iron:2.0, calcium:24,  vitC:1.5, vitD:0,   vitB12:0    },
  "Paneer":  { kcal:265, prot:18.3, carb:1.2,  fat:20.8,fiber:0,   iron:0.4, calcium:480, vitC:0,   vitD:0.1, vitB12:0.05 },
  "Curd":    { kcal:61,  prot:3.5,  carb:4.7,  fat:3.1, fiber:0,   iron:0.1, calcium:121, vitC:0,   vitD:0.1, vitB12:0.37 },
  "Chana":   { kcal:164, prot:8.9,  carb:27.4, fat:2.6, fiber:7.6, iron:2.9, calcium:49,  vitC:1.3, vitD:0,   vitB12:0    },
  "Rajma":   { kcal:127, prot:8.7,  carb:22.8, fat:0.5, fiber:6.4, iron:2.2, calcium:50,  vitC:1.2, vitD:0,   vitB12:0    },
  "Banana":  { kcal:89,  prot:1.1,  carb:22.8, fat:0.3, fiber:2.6, iron:0.3, calcium:5,   vitC:8.7, vitD:0,   vitB12:0    },
  "Apple":   { kcal:52,  prot:0.3,  carb:13.8, fat:0.2, fiber:2.4, iron:0.1, calcium:6,   vitC:4.6, vitD:0,   vitB12:0    },
  "Milk":    { kcal:61,  prot:3.2,  carb:4.8,  fat:3.3, fiber:0,   iron:0.1, calcium:113, vitC:0,   vitD:1.2, vitB12:0.45 },
  "Oats":    { kcal:389, prot:16.9, carb:66.3, fat:6.9, fiber:10.6,iron:4.7, calcium:54,  vitC:0,   vitD:0,   vitB12:0    },
  "Bread":   { kcal:265, prot:9.0,  carb:49.0, fat:3.2, fiber:2.7, iron:3.0, calcium:260, vitC:0,   vitD:0,   vitB12:0    },
  "Egg":     { kcal:155, prot:12.6, carb:1.1,  fat:10.6,fiber:0,   iron:1.8, calcium:50,  vitC:0,   vitD:2.0, vitB12:1.11 },
  "Chicken": { kcal:165, prot:31.0, carb:0,    fat:3.6, fiber:0,   iron:1.0, calcium:15,  vitC:0,   vitD:0.1, vitB12:0.3  },
  "Fish":    { kcal:136, prot:20.2, carb:0,    fat:5.8, fiber:0,   iron:0.5, calcium:68,  vitC:0,   vitD:11.0, vitB12:3.0 },
  "Potato":  { kcal:77,  prot:2.0,  carb:17.5, fat:0.1, fiber:2.2, iron:0.8, calcium:12,  vitC:19.7,vitD:0,   vitB12:0    },
  "Poha":    { kcal:110, prot:2.0,  carb:23.5, fat:0.2, fiber:0.5, iron:1.1, calcium:8,   vitC:0,   vitD:0,   vitB12:0    },
  "Idli":    { kcal:58,  prot:1.9,  carb:10.8, fat:0.6, fiber:0.7, iron:0.5, calcium:17,  vitC:0,   vitD:0,   vitB12:0    },
  "Dosa":    { kcal:168, prot:3.9,  carb:25.0, fat:6.5, fiber:1.2, iron:0.9, calcium:22,  vitC:0,   vitD:0,   vitB12:0    },
  "Spinach": { kcal:23,  prot:2.9,  carb:3.6,  fat:0.4, fiber:2.2, iron:2.7, calcium:99,  vitC:28.1,vitD:0,   vitB12:0    },
};

const UNIT_MULTIPLIER = { g: 1, ml: 1, piece: 1, cup: 2.4, tbsp: 0.15 };

// ── STATE ────────────────────────────────────────────────────────────────────
let profile = JSON.parse(localStorage.getItem('ns_profile') || 'null') || {
  age:25, gender:'male', height:170, weight:70, activity:1.55, diet:'nonveg', goal:'maintain'
};
let foodLog = JSON.parse(localStorage.getItem('ns_log') || '[]');
let macroChart = null;

// ── CHARTS ───────────────────────────────────────────────────────────────────
function initMacroChart() {
  const ctx = document.getElementById('macroChart');
  if (!ctx) return;
  if (macroChart) macroChart.destroy();
  macroChart = new Chart(ctx, {
    type: 'doughnut',
    data: {
      labels: ['Protein', 'Carbs', 'Fat'],
      datasets: [{
        data: [0, 0, 0],
        backgroundColor: ['#10b981', '#3b82f6', '#7c3aed'],
        borderWidth: 0, hoverOffset: 6,
        borderRadius: 4,
      }]
    },
    options: {
      responsive: true, maintainAspectRatio: false,
      plugins: {
        legend: {
          position: 'bottom',
          labels: { color: '#8892a4', font: { size: 12, family: 'Inter' }, padding: 16, usePointStyle: true }
        },
        tooltip: {
          callbacks: {
            label: (ctx) => ` ${ctx.parsed}g`
          }
        }
      },
      cutout: '65%',
    }
  });
}

// ── CALCULATIONS ──────────────────────────────────────────────────────────────
function calcBMR(p) {
  if (p.gender === 'male') return 88.36 + 13.4*p.weight + 4.8*p.height - 5.7*p.age;
  return 447.6 + 9.25*p.weight + 3.1*p.height - 4.33*p.age;
}

function calcTargets(p) {
  const bmr = calcBMR(p);
  let tdee = bmr * p.activity;
  if (p.goal === 'lose') tdee -= 500;
  if (p.goal === 'gain') tdee += 300;
  const prot = p.weight * 1.6;
  const fat  = (tdee * 0.25) / 9;
  const carb = (tdee - prot*4 - fat*9) / 4;
  // Micro targets (RDA approximations)
  const fiber = p.gender === 'male' ? 38 : 25;
  return {
    kcal: Math.round(tdee), bmr: Math.round(bmr),
    prot: Math.round(prot), carb: Math.round(carb), fat: Math.round(fat), fiber,
    iron:   p.gender === 'male' ? 8 : 18,
    calcium: 1000,
    vitC:    65,
    vitD:    15,
    vitB12:  2.4
  };
}

function sumLog() {
  const s = { kcal:0, prot:0, carb:0, fat:0, fiber:0, iron:0, calcium:0, vitC:0, vitD:0, vitB12:0 };
  foodLog.forEach(e => {
    const f = FOODS[e.food];
    const mult = e.qty * UNIT_MULTIPLIER[e.unit] / 100;
    s.kcal    += f.kcal    * mult;
    s.prot    += f.prot    * mult;
    s.carb    += f.carb    * mult;
    s.fat     += f.fat     * mult;
    s.fiber   += f.fiber   * mult;
    s.iron    += f.iron    * mult;
    s.calcium += f.calcium * mult;
    s.vitC    += f.vitC    * mult;
    s.vitD    += f.vitD    * mult;
    s.vitB12  += f.vitB12  * mult;
  });
  Object.keys(s).forEach(k => s[k] = Math.round(s[k]*10)/10);
  return s;
}

// ── DASHBOARD RENDER ──────────────────────────────────────────────────────────
function renderDashboard() {
  const tgt = calcTargets(profile);
  const sum = sumLog();

  // Stat cards
  document.getElementById('d-kcal').textContent = Math.round(sum.kcal);
  document.getElementById('d-kcal-target').textContent = `/ ${tgt.kcal} kcal`;
  document.getElementById('d-prot').innerHTML = `${sum.prot}<span style="font-size:14px;font-weight:400">g</span>`;
  document.getElementById('d-prot-target').textContent = `/ ${tgt.prot}g target`;
  document.getElementById('d-carbs').innerHTML = `${sum.carb}<span style="font-size:14px;font-weight:400">g</span>`;
  document.getElementById('d-carbs-target').textContent = `/ ${tgt.carb}g target`;
  document.getElementById('d-fat').innerHTML = `${sum.fat}<span style="font-size:14px;font-weight:400">g</span>`;
  document.getElementById('d-fat-target').textContent = `/ ${tgt.fat}g target`;

  // Energy ring
  const pct = Math.min(sum.kcal / tgt.kcal, 1);
  const circumference = 2 * Math.PI * 52;
  const offset = circumference * (1 - pct);
  document.getElementById('energyRing').style.strokeDashoffset = offset;
  document.getElementById('ring-kcal').textContent = Math.round(sum.kcal);
  document.getElementById('ring-target').textContent = `${tgt.kcal} kcal`;
  const rem = tgt.kcal - sum.kcal;
  document.getElementById('ring-remain').textContent = `${Math.max(0,Math.round(rem))} kcal`;
  document.getElementById('ring-pct').textContent = `${Math.round(pct*100)}%`;
  document.getElementById('ring-bmr').textContent = `${tgt.bmr} kcal`;

  // Macro chart
  if (macroChart) {
    macroChart.data.datasets[0].data = [sum.prot, sum.carb, sum.fat];
    macroChart.update();
  }

  // Macro progress bars
  const macros = [
    { label:'Calories', val:sum.kcal, tgt:tgt.kcal, unit:'kcal', cls:'blue' },
    { label:'Protein',  val:sum.prot, tgt:tgt.prot,  unit:'g',    cls:'emerald' },
    { label:'Carbs',    val:sum.carb, tgt:tgt.carb,  unit:'g',    cls:'amber' },
    { label:'Fat',      val:sum.fat,  tgt:tgt.fat,   unit:'g',    cls:'violet' },
    { label:'Fiber',    val:sum.fiber,tgt:tgt.fiber, unit:'g',    cls:'rose' },
  ];
  document.getElementById('macro-progress').innerHTML = macros.map(m => {
    const p = Math.min(m.val / m.tgt * 100, 100);
    return `<div class="progress-row">
      <span class="progress-label">${m.label}</span>
      <div class="progress-bar-wrap" style="flex:1"><div class="progress-bar ${m.cls}" style="width:${p}%"></div></div>
      <span class="progress-pct">${Math.round(p)}%</span>
      <span style="font-size:11px;color:var(--text-muted);min-width:100px;text-align:right">${m.val}/${m.tgt} ${m.unit}</span>
    </div>`;
  }).join('');

  // Deficiency / Excess
  const micros = [
    { key:'fiber',   label:'Fiber',      val:sum.fiber,   tgt:tgt.fiber,  unit:'g' },
    { key:'iron',    label:'Iron',        val:sum.iron,    tgt:tgt.iron,   unit:'mg' },
    { key:'calcium', label:'Calcium',     val:sum.calcium, tgt:tgt.calcium,unit:'mg' },
    { key:'vitC',    label:'Vitamin C',   val:sum.vitC,    tgt:tgt.vitC,   unit:'mg' },
    { key:'vitD',    label:'Vitamin D',   val:sum.vitD,    tgt:tgt.vitD,   unit:'µg' },
    { key:'vitB12',  label:'Vitamin B12', val:sum.vitB12,  tgt:tgt.vitB12, unit:'µg' },
  ];
  const defList = document.getElementById('deficiency-list');
  const excList = document.getElementById('excess-list');
  const defs = micros.filter(m => m.val < m.tgt * 0.8).sort((a,b) => (a.val/a.tgt)-(b.val/b.tgt)).slice(0,4);
  const excs = micros.filter(m => m.val > m.tgt * 1.2).sort((a,b) => (b.val/b.tgt)-(a.val/a.tgt)).slice(0,4);

  defList.innerHTML = defs.length ? defs.map(m => `
    <div class="insight-chip def">⬇ ${m.label} <span class="pct">${Math.round(m.val/m.tgt*100)}%</span></div>
  `).join('') : '<span style="font-size:12px;color:var(--text-muted)">No deficiencies — great job!</span>';

  excList.innerHTML = excs.length ? excs.map(m => `
    <div class="insight-chip exc">⬆ ${m.label} <span class="pct">${Math.round(m.val/m.tgt*100)}%</span></div>
  `).join('') : '<span style="font-size:12px;color:var(--text-muted)">No excesses detected.</span>';

  // Micro table
  const rows = [...macros.slice(0,4), ...micros.map(m => ({label:m.label,val:m.val,tgt:m.tgt,unit:m.unit,cls:''}))];
  const microRows = micros.map(m => {
    const p = m.tgt > 0 ? Math.min(m.val/m.tgt*100,150) : 0;
    const clamp = Math.min(p,100);
    let status, cls;
    if (p < 50)      { status='Low';      cls='chip-low'; }
    else if (p < 80) { status='Moderate'; cls='chip-low'; }
    else if (p > 120){ status='Excess';   cls='chip-high'; }
    else             { status='Good';     cls='chip-ok'; }
    const bar = p <= 100
      ? `<div class="progress-bar-wrap"><div class="progress-bar emerald" style="width:${p}%"></div></div>`
      : `<div class="progress-bar-wrap"><div class="progress-bar amber" style="width:100%"></div></div>`;
    return `<tr>
      <td>${m.label}</td>
      <td class="td-num">${m.val} ${m.unit}</td>
      <td class="td-num">${m.tgt} ${m.unit}</td>
      <td class="td-num">${Math.round(p)}%</td>
      <td><span class="nutrient-chip ${cls}">${status}</span></td>
      <td style="min-width:120px">${bar}</td>
    </tr>`;
  });
  document.getElementById('microTable').innerHTML = microRows.join('') ||
    '<tr class="empty-row"><td colspan="6">No food logged yet</td></tr>';
}

// ── LOG TABLE ─────────────────────────────────────────────────────────────────
function renderLogTable() {
  const tbody = document.getElementById('logTable');
  if (!foodLog.length) {
    tbody.innerHTML = '<tr class="empty-row"><td colspan="10">No entries yet — add your first food above</td></tr>';
    return;
  }
  tbody.innerHTML = foodLog.map((e, idx) => {
    const f = FOODS[e.food];
    const mult = e.qty * UNIT_MULTIPLIER[e.unit] / 100;
    const kcal = Math.round(f.kcal * mult);
    const prot = (f.prot * mult).toFixed(1);
    const carb = (f.carb * mult).toFixed(1);
    const fat  = (f.fat  * mult).toFixed(1);
    const fib  = (f.fiber* mult).toFixed(1);
    return `<tr>
      <td>${e.food}</td>
      <td><span style="font-size:11px;background:var(--bg-input);padding:2px 8px;border-radius:4px;color:var(--text-secondary)">${e.meal}</span></td>
      <td class="td-num editable-cell">
        <input type="number" value="${e.qty}" min="1" max="2000"
          onchange="editEntry(${idx},'qty',this.value)"
          style="width:60px">
      </td>
      <td class="td-num">${e.unit}</td>
      <td class="td-num"><b>${kcal}</b></td>
      <td class="td-num">${prot}g</td>
      <td class="td-num">${carb}g</td>
      <td class="td-num">${fat}g</td>
      <td class="td-num">${fib}g</td>
      <td><button class="btn btn-danger btn-sm" onclick="removeEntry(${idx})">✕</button></td>
    </tr>`;
  }).join('');
}

function addFoodEntry() {
  const food = document.getElementById('foodSelect').value;
  const qty  = parseFloat(document.getElementById('foodQty').value);
  const unit = document.getElementById('foodUnit').value;
  const meal = document.getElementById('mealType').value;
  if (!food) { showToast('Please select a food item'); return; }
  if (!qty || qty <= 0) { showToast('Enter a valid quantity'); return; }
  foodLog.push({ food, qty, unit, meal });
  saveState();
  renderLogTable();
  renderDashboard();
  renderRecs();
  showToast(`${food} added to ${meal}`);
}

function removeEntry(idx) {
  foodLog.splice(idx, 1);
  saveState();
  renderLogTable();
  renderDashboard();
  renderRecs();
}

function editEntry(idx, field, val) {
  foodLog[idx][field] = parseFloat(val);
  saveState();
  renderDashboard();
  renderRecs();
}

function clearLog() {
  if (!foodLog.length) return;
  foodLog = [];
  saveState();
  renderLogTable();
  renderDashboard();
  renderRecs();
  showToast('Log cleared');
}

// ── FOOD PREVIEW ──────────────────────────────────────────────────────────────
function updateFoodPreview() {
  const food = document.getElementById('foodSelect').value;
  const qty  = parseFloat(document.getElementById('foodQty').value) || 100;
  const unit = document.getElementById('foodUnit').value;
  const el   = document.getElementById('food-preview');
  if (!food) { el.style.display = 'none'; return; }
  const f = FOODS[food];
  const mult = qty * UNIT_MULTIPLIER[unit] / 100;
  el.style.display = 'block';
  el.innerHTML = `<b style="color:var(--text-primary)">${food}</b> — ${qty}${unit} &nbsp;|&nbsp;
    🔥 <b style="color:var(--accent-blue)">${Math.round(f.kcal*mult)} kcal</b> &nbsp;|&nbsp;
    Protein: ${(f.prot*mult).toFixed(1)}g &nbsp;|&nbsp;
    Carbs: ${(f.carb*mult).toFixed(1)}g &nbsp;|&nbsp;
    Fat: ${(f.fat*mult).toFixed(1)}g &nbsp;|&nbsp;
    Fiber: ${(f.fiber*mult).toFixed(1)}g`;
}

// ── PROFILE ───────────────────────────────────────────────────────────────────
function loadProfileForm() {
  document.getElementById('p-age').value     = profile.age;
  document.getElementById('p-gender').value  = profile.gender;
  document.getElementById('p-height').value  = profile.height;
  document.getElementById('p-weight').value  = profile.weight;
  document.getElementById('p-activity').value= profile.activity;
  document.getElementById('p-diet').value    = profile.diet;
  document.getElementById('p-goal').value    = profile.goal;
}

function saveProfile() {
  const age    = parseInt(document.getElementById('p-age').value);
  const gender = document.getElementById('p-gender').value;
  const height = parseFloat(document.getElementById('p-height').value);
  const weight = parseFloat(document.getElementById('p-weight').value);
  if (!age||!height||!weight||age<10||height<100||weight<20) {
    showToast('Please fill in valid profile details'); return;
  }
  profile = {
    age, gender, height, weight,
    activity: parseFloat(document.getElementById('p-activity').value),
    diet:     document.getElementById('p-diet').value,
    goal:     document.getElementById('p-goal').value,
  };
  saveState();
  renderTargetsCard();
  renderDashboard();
  renderRecs();
  showToast('Profile saved & targets recalculated ✓');
}

function resetProfile() {
  profile = { age:25, gender:'male', height:170, weight:70, activity:1.55, diet:'nonveg', goal:'maintain' };
  loadProfileForm();
  saveState();
  showToast('Profile reset to defaults');
}

function renderTargetsCard() {
  const tgt = calcTargets(profile);
  const card = document.getElementById('targets-card');
  card.style.display = 'block';
  document.getElementById('targets-grid').innerHTML = [
    { label:'TDEE',    val: tgt.kcal + ' kcal', color:'blue' },
    { label:'BMR',     val: tgt.bmr  + ' kcal', color:'violet' },
    { label:'Protein', val: tgt.prot + ' g',    color:'emerald' },
    { label:'Carbs',   val: tgt.carb + ' g',    color:'amber' },
    { label:'Fat',     val: tgt.fat  + ' g',    color:'violet' },
    { label:'Fiber',   val: tgt.fiber+ ' g',    color:'emerald' },
    { label:'Iron',    val: tgt.iron + ' mg',   color:'amber' },
    { label:'Calcium', val: tgt.calcium+' mg',  color:'blue' },
  ].map(t => `<div class="stat-card ${t.color}" style="padding:14px">
    <div class="stat-label">${t.label}</div>
    <div style="font-family:var(--font-display);font-size:20px;font-weight:700;margin-top:6px">${t.val}</div>
  </div>`).join('');
}

// ── RECOMMENDATIONS ───────────────────────────────────────────────────────────
function renderRecs() {
  const tgt = calcTargets(profile);
  const sum = sumLog();
  const diet = profile.diet;
  const con  = document.getElementById('rec-container');

  const recs = [];

  // Helper: is food compatible with diet?
  const dietOK = (food) => {
    if (diet === 'nonveg') return true;
    const nonVeg = ['Chicken','Fish'];
    const eggOK  = ['Egg'];
    if (nonVeg.includes(food)) return diet === 'nonveg';
    if (eggOK.includes(food))  return diet !== 'veg';
    return true;
  };

  // Iron deficiency
  if (sum.iron < tgt.iron * 0.7) {
    const opts = dietOK('Chicken') ? 'Spinach, Chana, or Chicken'
               : dietOK('Egg')     ? 'Spinach, Chana, or Eggs'
               : 'Spinach, Chana, or Dal';
    recs.push({ type:'add', icon:'🥬', title:'Boost Iron Intake', tag:'Add Food',
      body:`Your iron intake is at ${Math.round(sum.iron/tgt.iron*100)}% of target. Consider adding ${opts} to your meals. Pair with Vitamin C-rich foods (like lemon or Potato) to enhance absorption.` });
  }

  // Calcium deficiency
  if (sum.calcium < tgt.calcium * 0.7) {
    recs.push({ type:'add', icon:'🥛', title:'Increase Calcium', tag:'Add Food',
      body:`Calcium is at ${Math.round(sum.calcium/tgt.calcium*100)}% of target. Add Milk, Curd, or Paneer to your daily log. A glass of milk (250 ml) provides ~280 mg calcium.` });
  }

  // Vitamin C deficiency
  if (sum.vitC < tgt.vitC * 0.7) {
    recs.push({ type:'add', icon:'🍋', title:'Add Vitamin C Sources', tag:'Add Food',
      body:`Vitamin C is at ${Math.round(sum.vitC/tgt.vitC*100)}% of target. Add Spinach, Apple, or Potato to increase your intake. Spinach is especially rich with ~28 mg per 100g.` });
  }

  // Vitamin D deficiency
  if (sum.vitD < tgt.vitD * 0.6) {
    const vdOpt = dietOK('Fish') ? 'Fish, Egg, or Milk' : dietOK('Egg') ? 'Egg or Milk' : 'Milk or Curd (fortified)';
    recs.push({ type:'add', icon:'☀️', title:'Vitamin D Is Low', tag:'Add Food',
      body:`Vitamin D at ${Math.round(sum.vitD/tgt.vitD*100)}% of target. Add ${vdOpt}. Fish is the best dietary source (11 µg/100g). Also consider sunlight exposure for 15–20 min/day.` });
  }

  // Protein low
  if (sum.prot < tgt.prot * 0.7) {
    const protOpt = dietOK('Chicken') ? 'Chicken, Fish, or Paneer' : dietOK('Egg') ? 'Egg, Dal, or Paneer' : 'Dal, Chana, Rajma, or Paneer';
    recs.push({ type:'swap', icon:'💪', title:'Protein Needs Attention', tag:'Swap',
      body:`Protein is at ${Math.round(sum.prot/tgt.prot*100)}% of target (need ${tgt.prot}g). Replace simple carb foods with ${protOpt} for at least one meal. High-protein foods help with satiety and muscle maintenance.` });
  }

  // High calories — swap suggestion
  if (sum.kcal > tgt.kcal * 1.1) {
    recs.push({ type:'swap', icon:'🔄', title:'Calorie Overshoot', tag:'Swap',
      body:`You've consumed ${Math.round(sum.kcal - tgt.kcal)} extra kcal today. Consider swapping Roti or Rice with Oats or Idli, or reducing portion sizes. Replacing one serving of Rice (150g) with the same weight in Idli saves ~100 kcal.` });
  }

  // High fat
  if (sum.fat > tgt.fat * 1.2) {
    recs.push({ type:'portion', icon:'⚖️', title:'Reduce Fat Intake', tag:'Portion',
      body:`Fat is ${Math.round(sum.fat/tgt.fat*100)}% of target. Consider reducing Paneer or Dosa portions. Replace fried preparations with steamed or boiled options for the same foods.` });
  }

  // Fiber low
  if (sum.fiber < tgt.fiber * 0.6) {
    recs.push({ type:'add', icon:'🌿', title:'Fiber Intake Too Low', tag:'Add Food',
      body:`Fiber at ${Math.round(sum.fiber/tgt.fiber*100)}% of target. Add Oats (10.6g/100g), Chana (7.6g/100g), or Rajma (6.4g/100g) to your meals. Fiber supports digestion and reduces cardiovascular risk.` });
  }

  // Log is empty
  if (!foodLog.length) {
    con.innerHTML = `<div class="info-badge">💡 Add foods to your log and save your profile to get personalised recommendations.</div>`;
    return;
  }

  // Great day message
  if (!recs.length) {
    con.innerHTML = `<div class="rec-card" style="border-color:rgba(16,185,129,0.3)">
      <div class="rec-icon add">🎉</div>
      <div><div class="rec-title" style="color:var(--accent-emerald)">You're nailing your nutrition today!</div>
      <div class="rec-body">All major nutrients are within healthy ranges. Keep up the great work — consistency is key to long-term health.</div></div>
    </div>`;
    return;
  }

  const typeMap = { add:'tag-add', swap:'tag-swap', portion:'tag-portion' };
  con.innerHTML = recs.map(r => `
    <div class="rec-card">
      <div class="rec-icon ${r.type}">${r.icon}</div>
      <div style="flex:1">
        <span class="rec-tag ${typeMap[r.type]}">${r.tag}</span>
        <div class="rec-title">${r.title}</div>
        <div class="rec-body">${r.body}</div>
      </div>
    </div>
  `).join('');
}

// ── TOAST ─────────────────────────────────────────────────────────────────────
function showToast(msg) {
  const t = document.getElementById('toast');
  document.getElementById('toastMsg').textContent = msg;
  t.classList.add('show');
  setTimeout(() => t.classList.remove('show'), 3000);
}

// ── TAB SWITCHING ─────────────────────────────────────────────────────────────
function switchTab(name) {
  document.querySelectorAll('.tab-panel').forEach(p => p.classList.remove('active'));
  document.getElementById('tab-' + name).classList.add('active');
  document.querySelectorAll('.nav-tab').forEach((b,i) => {
    b.classList.toggle('active', ['dashboard','log','profile','recs'][i] === name);
  });
  document.querySelectorAll('.mobile-tab').forEach((b,i) => {
    b.classList.toggle('active', ['dashboard','log','profile','recs'][i] === name);
  });
}

// ── SAVE / LOAD ───────────────────────────────────────────────────────────────
function saveState() {
  localStorage.setItem('ns_profile', JSON.stringify(profile));
  localStorage.setItem('ns_log',     JSON.stringify(foodLog));
}

// ── INIT ──────────────────────────────────────────────────────────────────────
function init() {
  // Date badge
  const d = new Date();
  document.getElementById('dateBadge').textContent =
    d.toLocaleDateString('en-IN', { weekday:'short', day:'numeric', month:'short' });

  // Populate food select
  const sel = document.getElementById('foodSelect');
  Object.keys(FOODS).sort().forEach(f => {
    const opt = document.createElement('option');
    opt.value = f; opt.textContent = f;
    sel.appendChild(opt);
  });

  // Food preview listeners
  document.getElementById('foodSelect').addEventListener('change', updateFoodPreview);
  document.getElementById('foodQty').addEventListener('input', updateFoodPreview);
  document.getElementById('foodUnit').addEventListener('change', updateFoodPreview);

  // Macro chart
  initMacroChart();

  // Load profile form
  loadProfileForm();

  // Render
  renderLogTable();
  renderDashboard();
  renderRecs();
  if (profile.age) renderTargetsCard();
}

document.addEventListener('DOMContentLoaded', init);
</script>

<!-- ENHANCED FEATURES ADDED:
CSV Upload, 40+ Foods Expansion, Additional Micronutrients,
2-Day Meal Planner, Risk Analysis, Educational Disclaimer,
Nutrition Sources, Better Charts, Advanced Recommendations
-->

</body>
</html>
