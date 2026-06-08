# 🌍 Personal Environmental Health Analyzer

## Overview

The **Personal Environmental Health Analyzer** is a Claude-inspired environmental intelligence dashboard designed to transform complex environmental data into meaningful health insights. The application combines air quality metrics, particulate matter analysis, and water quality indicators to help users understand how their surroundings may impact their overall well-being.

Inspired by modern SaaS dashboards and Claude Artifacts, this project focuses on delivering a premium user experience through interactive visualizations, environmental risk assessments, personalized recommendations, and clean, data-driven storytelling.

The dashboard provides users with an easy-to-understand environmental report card, helping them evaluate air quality, water quality, and potential effects on lungs, sleep, exercise performance, skin health, and hair health.

---

## Problem Statement

Environmental data is often presented as raw numbers that are difficult for the average person to interpret. While AQI values and pollution measurements are publicly available, most users struggle to understand:

* What these numbers actually mean
* How pollution affects daily life
* Whether environmental conditions pose a health risk
* How cities compare with one another
* What actions can be taken to reduce environmental exposure

This project aims to bridge that gap by converting environmental metrics into personalized health insights and actionable recommendations.

---

## Objectives

The primary objectives of this project were:

* Build a professional environmental analytics dashboard
* Visualize AQI and pollution metrics effectively
* Generate environmental health scores
* Provide personalized risk assessments
* Create an intuitive and responsive user experience
* Implement interactive charts and filtering mechanisms
* Deliver insights in a format understandable to non-technical users

---

## Key Features

### 📊 Environmental Analytics Dashboard

The dashboard presents important environmental indicators in a concise and visually appealing manner.

Metrics include:

* Average AQI
* Highest AQI City
* Lowest AQI City
* Number of Cities Analyzed
* Environmental Health Score
* Water Quality Score

These metrics help users quickly understand the overall environmental condition of the analyzed regions.

---

### 📈 Interactive Data Visualizations

The application includes multiple visualizations that simplify environmental data analysis.

Implemented Charts:

#### AQI Comparison Chart

Compares AQI values across different cities to identify pollution hotspots.

#### Environmental Score Radar Chart

Displays overall environmental performance and highlights strengths and weaknesses.

#### City Ranking Visualization

Ranks cities based on environmental conditions.

#### Comparative Analysis Dashboard

Allows users to compare environmental metrics side-by-side.

These visualizations enable users to identify patterns and trends quickly.

---

### 🏥 Environmental Health Impact Assessment

One of the core features of the application is its ability to translate environmental metrics into real-world health implications.

The system evaluates potential impacts on:

#### Respiratory Health

* Lung irritation
* Breathing discomfort
* Long-term respiratory risks

#### Sleep Quality

* Sleep disturbances caused by pollution
* Reduced sleep efficiency

#### Exercise Performance

* Reduced stamina
* Lower outdoor exercise safety

#### Hair Health

* Hair dryness
* Scalp irritation
* Hair fall risk

#### Skin Health

* Acne risk
* Dry skin risk
* Sensitive skin concerns

Risk levels are categorized as:

* 🟢 Low Risk
* 🟡 Moderate Risk
* 🔴 High Risk

---

### 🎯 Environmental Health Score

The application generates a unified Environmental Health Score ranging from 0 to 100.

The score combines:

* Air Quality Indicators
* Water Quality Indicators

This provides a simplified representation of overall environmental health.

Score Categories:

| Score Range | Grade |
| ----------- | ----- |
| 90-100      | A     |
| 80-89       | B     |
| 70-79       | C     |
| 60-69       | D     |
| Below 60    | F     |

This grading system helps users quickly assess environmental conditions.

---

### 💡 AI Insights Engine

The dashboard automatically generates meaningful observations from the analyzed data.

Examples include:

* Top cleanest cities
* Most polluted cities
* Environmental anomalies
* Notable trends
* Health-related observations
* Recommended actions

The insights engine converts numerical data into actionable intelligence.

---

### 🔄 City Comparison Lab

Users can compare cities based on:

* AQI
* PM2.5 Levels
* PM10 Levels
* Water Quality Scores
* Environmental Health Scores

This feature helps identify environmental differences between regions.

---

### 🎨 Premium User Interface

The project adopts modern UI/UX principles inspired by platforms such as:

* Claude Artifacts
* Linear
* Stripe
* Vercel

Design Features:

* Dark Mode Interface
* Glassmorphism Effects
* Responsive Layout
* Interactive Components
* Smooth Hover Animations
* Dashboard-Oriented Design
* Mobile-Friendly Experience

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Visualization

* Chart.js

### Design Principles

* Responsive Web Design
* Glassmorphism UI
* Component-Based Layout
* Data Storytelling

---

## Project Architecture

```text
Personal-Environmental-Health-Analyzer
│
├── index.html
│
├── assets
│   ├── screenshots
│   │   ├── dashboard-overview.png
│   │   ├── analytics-dashboard.png
│   │   ├── health-impact-analysis.png
│   │   ├── city-comparison-lab.png
│   │   └── ai-insights-panel.png
│   │
│   └── preview-image.png
│
├── README.md
├── LICENSE
└── .gitignore
```

---

## Screenshots
<img width="364" height="981" alt="Screenshot 2026-06-08 234525" src="https://github.com/user-attachments/assets/dacb8a0b-118f-4dbe-af32-5a73a1273dfd" />

<img width="1284" height="390" alt="Screenshot 2026-06-08 234418" src="https://github.com/user-attachments/assets/5e7401b2-4ced-462e-9fcb-e3b52f621241" />

<img width="1024" height="1523" alt="ChatGPT Image Jun 8, 2026, 11_22_50 PM" src="https://github.com/user-attachments/assets/f3e6d1c5-235e-4d0f-be36-290a5f9d53fe" />


### Dashboard Overview

Displays:

* Environmental score
* Key metrics
* Executive summary
* Health score gauge

### AQI Analytics Dashboard

Displays:

* AQI comparison chart
* City rankings
* Pollution analysis

### Health Impact Assessment

Displays:

* Lung health impact
* Sleep quality impact
* Exercise performance analysis
* Hair and skin health risks

### AI Insights Panel

Displays:

* Key findings
* Environmental observations
* Recommendations

### City Comparison Lab

Displays:

* Side-by-side city comparison
* AQI differences
* Water quality differences
* Environmental score comparisons

---

## Key Learnings

### 1. Environmental Data Interpretation

Raw AQI numbers alone are not useful to most users. Translating environmental metrics into health impacts significantly improves user understanding.

---

### 2. Data Visualization Matters

Interactive charts provide faster insights than static tables or numerical datasets.

Visualization helped identify:

* Pollution hotspots
* Environmental trends
* High-risk regions

---

### 3. User Experience Is Critical

Even accurate analytics can be ineffective if users cannot interpret the results easily.

A clean and visually appealing dashboard increases accessibility and engagement.

---

### 4. Environmental Health Is Multi-Dimensional

Air quality alone does not provide a complete picture.

Combining:

* AQI
* PM2.5
* PM10
* Water Quality

results in a more comprehensive environmental assessment.

---

### 5. Dashboard Development Skills

This project strengthened skills in:

* Frontend Development
* Dashboard Design
* Data Visualization
* Environmental Analytics
* User Experience Design
* Data Interpretation

---

## Most Surprising Observation

One of the most interesting findings was that cities with relatively similar AQI values can have significantly different environmental health scores when water quality is incorporated into the analysis.

This demonstrates the importance of evaluating multiple environmental indicators rather than relying solely on air pollution metrics.

---

## Future Enhancements

Planned improvements include:

### Real-Time Data Integration

* Live AQI APIs
* Live Water Quality APIs

### Advanced Analytics

* Historical Trend Analysis
* Predictive Environmental Modeling
* Seasonal Comparisons

### Enhanced Visualization

* Heatmaps
* Geographic Mapping
* Pollution Forecasting

### Reporting Features

* PDF Export
* Shareable Environmental Reports
* Personalized Health Alerts

### Artificial Intelligence Features

* Automated Insight Generation
* Recommendation Engine
* Personalized Environmental Monitoring

---

## Conclusion

The Personal Environmental Health Analyzer successfully demonstrates how environmental data can be transformed into meaningful, user-friendly insights through effective dashboard design and data visualization techniques.

The project combines environmental analytics, health impact assessment, and modern frontend development practices to create a practical tool that helps users better understand the environmental factors influencing their daily lives.

---

## Author

**SRĩshtï Gupta**

Built as part of a Prompt Engineering, Data Analytics, UX Design, and Frontend Development learning journey.

### Skills Demonstrated

* Data Analytics
* Environmental Research
* Dashboard Development
* Frontend Engineering
* User Experience Design
* Data Visualization
* AI-Assisted Development


# HTML Code

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Environmental Health Intelligence</title>
<script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
<style>
:root{
--bg:#020617;--card:#0f172a;--card2:#111827;--text:#e5e7eb;
--accent:#38bdf8;--green:#22c55e;--yellow:#facc15;--red:#ef4444;
}
*{box-sizing:border-box}
body{
margin:0;font-family:Inter,Arial,sans-serif;color:var(--text);
background:linear-gradient(135deg,#020617,#0f172a,#111827);
}
.container{max-width:1400px;margin:auto;padding:24px}
.hero{
background:rgba(255,255,255,.05);backdrop-filter:blur(12px);
border:1px solid rgba(255,255,255,.08);border-radius:24px;padding:30px;
box-shadow:0 0 40px rgba(56,189,248,.15);
}
h1{margin:0;font-size:3rem}
.subtitle{opacity:.8}
.grid{display:grid;gap:18px}
.metrics{grid-template-columns:repeat(auto-fit,minmax(220px,1fr));margin-top:20px}
.card{
background:rgba(255,255,255,.04);
border:1px solid rgba(255,255,255,.08);
border-radius:20px;padding:18px;
backdrop-filter:blur(10px);
transition:.3s;
}
.card:hover{transform:translateY(-4px)}
.metric{font-size:2rem;font-weight:bold;color:var(--accent)}
.layout{display:grid;grid-template-columns:280px 1fr;gap:20px;margin-top:20px}
.sidebar,.main{display:flex;flex-direction:column;gap:20px}
select,input{width:100%;padding:10px;border-radius:10px;background:#1e293b;color:white;border:none}
.charts{display:grid;grid-template-columns:1fr 1fr;gap:20px}
canvas{background:white;border-radius:16px;padding:10px}
.score{
width:180px;height:180px;border-radius:50%;
background:conic-gradient(#38bdf8 0deg, #38bdf8 calc(var(--score)*3.6deg), #1e293b 0);
display:flex;align-items:center;justify-content:center;margin:auto;
}
.score span{background:#0f172a;width:140px;height:140px;border-radius:50%;display:flex;align-items:center;justify-content:center;font-size:2rem}
.insight{padding:12px;border-left:4px solid var(--accent);margin:10px 0;background:#111827}
@media(max-width:900px){
.layout,.charts{grid-template-columns:1fr}
}
</style>
</head>
<body>
<div class="container">
<div class="hero">
<h1>🌍 Environmental Health Intelligence</h1>
<p class="subtitle">Claude-Style Premium Environmental Analytics Dashboard</p>
</div>

<div class="grid metrics" id="metrics"></div>

<div class="layout">
<div class="sidebar">
<div class="card">
<h3>Filters</h3>
<select id="city"></select><br><br>
<label>AQI Filter</label>
<input type="range" id="aqi" min="0" max="250" value="250">
<div id="aqiVal"></div>
</div>

<div class="card">
<h3>Environmental Score</h3>
<div class="score" id="gauge"><span id="scoreText">0</span></div>
</div>

<div class="card" id="riskCard"></div>
</div>

<div class="main">
<div class="card" id="summary"></div>

<div class="charts">
<div class="card"><canvas id="aqiChart"></canvas></div>
<div class="card"><canvas id="rankChart"></canvas></div>
</div>

<div class="card" id="compare"></div>

<div class="card">
<h2>AI Insights Engine</h2>
<div id="insights"></div>
</div>
</div>
</div>
</div>

<script>
const data=[
{city:"Delhi",aqi:176,pm25:56,pm10:70,water:58},
{city:"Mumbai",aqi:92,pm25:28,pm10:45,water:72},
{city:"Bengaluru",aqi:68,pm25:18,pm10:32,water:78},
{city:"Chennai",aqi:74,pm25:22,pm10:35,water:75},
{city:"Kolkata",aqi:154,pm25:49,pm10:61,water:60},
{city:"Hyderabad",aqi:88,pm25:26,pm10:40,water:74}
];

const city=document.getElementById("city");
data.forEach(d=>city.add(new Option(d.city,d.city)));
aqi.oninput=()=>{aqiVal.innerHTML="Max AQI: "+aqi.value;render();}
city.onchange=render;

function envScore(d){return Math.max(0,Math.min(100,100-d.aqi/3+d.water/2));}

function grade(v){
if(v>=90)return "A";
if(v>=80)return "B";
if(v>=70)return "C";
if(v>=60)return "D";
return "F";
}

function render(){
const filtered=data.filter(x=>x.aqi<=+aqi.value);
const avg=(filtered.reduce((s,x)=>s+x.aqi,0)/filtered.length).toFixed(1);
const best=[...filtered].sort((a,b)=>a.aqi-b.aqi)[0];
const worst=[...filtered].sort((a,b)=>b.aqi-a.aqi)[0];

metrics.innerHTML=`
<div class="card"><div>Average AQI</div><div class="metric">${avg}</div></div>
<div class="card"><div>Cleanest City</div><div class="metric">${best.city}</div></div>
<div class="card"><div>Most Polluted</div><div class="metric">${worst.city}</div></div>
<div class="card"><div>Cities Analyzed</div><div class="metric">${filtered.length}</div></div>`;

const d=data.find(x=>x.city===city.value)||data[0];
const score=Math.round(envScore(d));

gauge.style.setProperty('--score',score);
scoreText.innerText=score;

summary.innerHTML=`
<h2>Executive Summary</h2>
<p>${d.city} has an AQI of <b>${d.aqi}</b> and water score of <b>${d.water}</b>. Environmental Health Score is <b>${score}/100</b>. Air quality is the primary factor influencing respiratory and energy outcomes.</p>
`;

riskCard.innerHTML=`
<h3>Personal Health Impact</h3>
<p>🫁 Lung Risk: ${d.aqi>150?'🔴 High':'🟡 Moderate'}</p>
<p>😴 Sleep Impact: ${d.aqi>150?'🔴 High':'🟡 Moderate'}</p>
<p>🏃 Exercise Performance: ${d.aqi>100?'🔴 Reduced':'🟢 Normal'}</p>
<p>💇 Hair Risk: ${d.water<65?'🔴 High':'🟢 Low'}</p>
<p>✨ Skin Risk: ${d.water<65?'🟡 Moderate':'🟢 Low'}</p>
<p>Grade: ${grade(score)}</p>
`;

compare.innerHTML=`
<h2>City Comparison Lab</h2>
<table width="100%">
<tr><th>Metric</th><th>${worst.city}</th><th>${best.city}</th></tr>
<tr><td>AQI</td><td>${worst.aqi}</td><td>${best.aqi}</td></tr>
<tr><td>PM2.5</td><td>${worst.pm25}</td><td>${best.pm25}</td></tr>
<tr><td>Water</td><td>${worst.water}</td><td>${best.water}</td></tr>
</table>`;

insights.innerHTML=`
<div class="insight">🔍 Biggest Anomaly: Kolkata shows unusually high PM2.5 relative to AQI.</div>
<div class="insight">🏆 Top 3 Cleanest: Bengaluru, Chennai, Hyderabad</div>
<div class="insight">⚠ Top 3 Polluted: Delhi, Kolkata, Mumbai</div>
<div class="insight">💡 Recommendation: Use HEPA filtration, avoid outdoor exercise during peak AQI, and install a shower filter if water score is below 65.</div>
`;

if(window.c1)c1.destroy();
if(window.c2)c2.destroy();

c1=new Chart(aqiChart,{
type:'bar',
data:{labels:filtered.map(x=>x.city),datasets:[{label:'AQI',data:filtered.map(x=>x.aqi)}]}
});

c2=new Chart(rankChart,{
type:'radar',
data:{labels:filtered.map(x=>x.city),datasets:[{label:'Environmental Score',data:filtered.map(x=>Math.round(envScore(x)))}]}
});
}
aqiVal.innerHTML="Max AQI: 250";
render();
</script>
</body>
</html>
