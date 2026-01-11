<!--
README theme: Dark Neon (Pink/Purple) + quirky eco-science vibe
Accent: #FF3FB4  | Purple: #A855F7 | Cyan: #22D3EE | BG: #0D1117
-->

<div align="center">

<!-- Neon badge header -->
<img alt="Neon Divider" width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=8&section=header"/>

<!-- Name + tagline -->
<h1>
  <span style="color:#F8FAFC;">Pranjel</span>
  <span style="color:#FF3FB4;">✦</span>
  <span style="color:#A855F7;">Ecology • GIS • Remote Sensing</span>
</h1>

<p>
  <b style="color:#F8FAFC;">Interdisciplinary ecologist</b> working at the interface of
  <span style="color:#FF3FB4;"><b>ecological modelling</b></span>,
  <span style="color:#A855F7;"><b>GIS & remote sensing</b></span>,
  <span style="color:#22D3EE;"><b>metabolomics</b></span> and
  <span style="color:#FF3FB4;"><b>chemical ecology</b></span>.
</p>

<!-- Quirky bubble -->
<div style="display:inline-block;padding:14px 18px;border:2px solid #FF3FB4;border-radius:18px;background:rgba(168,85,247,0.08);">
  <b style="color:#F8FAFC;">Nice, using dark mode I see.</b>
  <span style="color:#FF3FB4;"><b>True researcher</b></span> 😄🔬🌙
</div>

<br/><br/>

<!-- Quick links -->
<a href="https://bit.ly/3Z4lSOD">
  <img alt="Portfolio" src="https://img.shields.io/badge/Visit%20Site-0D1117?style=for-the-badge&logo=vercel&logoColor=22D3EE&labelColor=FF3FB4"/>
</a>
<a href="mailto:pranjel200109@gmail.com">
  <img alt="Email" src="https://img.shields.io/badge/Email-0D1117?style=for-the-badge&logo=gmail&logoColor=F8FAFC&labelColor=A855F7"/>
</a>
<a href="https://github.com/pranjel-ecologist">
  <img alt="GitHub" src="https://img.shields.io/badge/GitHub-0D1117?style=for-the-badge&logo=github&logoColor=F8FAFC&labelColor=FF3FB4"/>
</a>

<br/>

<img alt="Location" src="https://img.shields.io/badge/Bielefeld,%20Germany-0D1117?style=flat-square&logo=googlemaps&logoColor=22D3EE&labelColor=A855F7"/>
<img alt="Focus" src="https://img.shields.io/badge/Focus-Applied%20Conservation-0D1117?style=flat-square&logo=leaflet&logoColor=F8FAFC&labelColor=FF3FB4"/>

<br/><br/>

<!-- Neon ring SVG (self-contained, no external assets) -->
<svg width="520" height="130" viewBox="0 0 520 130" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Neon ring">
  <defs>
    <radialGradient id="g" cx="50%" cy="50%" r="60%">
      <stop offset="0%" stop-color="#FF3FB4" stop-opacity="0.6"/>
      <stop offset="60%" stop-color="#A855F7" stop-opacity="0.25"/>
      <stop offset="100%" stop-color="#0D1117" stop-opacity="0"/>
    </radialGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6" result="blur"/>
      <feMerge>
        <feMergeNode in="blur"/>
        <feMergeNode in="SourceGraphic"/>
      </feMerge>
    </filter>
  </defs>
  <rect width="520" height="130" fill="#0D1117"/>
  <circle cx="260" cy="65" r="44" fill="none" stroke="#FF3FB4" stroke-width="6" filter="url(#glow)"/>
  <circle cx="260" cy="65" r="56" fill="url(#g)"/>
  <text x="260" y="70" text-anchor="middle" font-family="ui-sans-serif,system-ui" font-size="14" fill="#F8FAFC">
    modelling ✦ maps ✦ molecules ✦ conservation
  </text>
</svg>

</div>

---

## 🧪 About me (a.k.a. *what I do when the data behaves*)
- I combine **field data**, **lab analyses**, and **quantitative modelling (R/Python)** to study how environmental stressors like **artificial light**, **drought**, and **habitat fragmentation** shape organisms and ecosystems.
- I like results that are **statistically honest**, **ecologically meaningful**, and **useful for conservation**.

---

## 🔭 Current playground
- 🗺️ **GIS dataset review & prioritization** for mapping *small natural landscape features* (iDiv, Halle–Jena–Leipzig)
- 🌿 Trait-space & ecological strategies: **multidimensional shifts** in R
- 🧬🧫 Metabolomics + chemical ecology: turning molecules into stories (the good kind)

---

## 🧰 Toolbox (neon edition)

### 🧠 Data / Modelling / GIS
![R](https://img.shields.io/badge/R-0D1117?style=for-the-badge&logo=r&logoColor=22D3EE&labelColor=FF3FB4)
![Python](https://img.shields.io/badge/Python-0D1117?style=for-the-badge&logo=python&logoColor=F8FAFC&labelColor=A855F7)
![QGIS](https://img.shields.io/badge/QGIS-0D1117?style=for-the-badge&logo=qgis&logoColor=22D3EE&labelColor=FF3FB4)
![Pandas](https://img.shields.io/badge/Pandas-0D1117?style=for-the-badge&logo=pandas&logoColor=F8FAFC&labelColor=A855F7)

- Stats: **PCA, PLS-DA, ANOVA, GLMs, mixed models, survival models**
- Spatial: **SDM**, spatial analysis, geo packages, trait space modelling
- ML bits: **Roboflow**, machine learning workflows (when it helps, not just because it exists)

### 🧪 Analytical / Lab
- **GC-MS, GC-FID, HPLC, MetaboAnalyst, PAM Fluorometer, GFS-3000**

### 🥾 Field / Experimental
- **Bioassay development**, ecological monitoring (insects/birds/amphibians), surveys, experimental design

---

## 📌 Selected project highlights (from field → lab → model)
- **Vigilance behaviour in geese (Wadden Sea)**: quantified vigilance across distance, flock size & position; supported Many-Eyes + Edge effects  
- **Savoy cabbage metabolomics (drought × fertilization)**: GC-FID/GC-MS showed drought suppressed TCA intermediates; fertilization increased amino acids (serine, threonine, GABA)  
- **UV-B vs greenhouse plant stress**: PSII efficiency comparison; greenhouse leaves outperformed UV-rich outdoor leaves  
- **CHC profiles (Athalia rosae & Phaedon cochleariae)**: sex/species differences; higher chemical richness/diversity in *Athalia rosae*  
- **Blue tit climate-driven egg-laying simulation**: mixed-effects + multi-generation fitness simulation; temperature linked to increased egg output & mean fitness  
- **Kashmir stag conservation strategy (Cervus hanglu hanglu)**: GIS + genetics corridor restoration plan to improve gene flow and population viability  
- **Artificial light effects on insect chemical defense (ALAN)**: bioassay design + feeding performance + defensive secretion analysis

> Want these as pinned repos with matching cards? Create repos with these names and I’ll format the pinned section to auto-fit.

---

## 🧑‍🔬 Experience (tiny timeline, big datasets)
- **iDiv (Halle–Jena–Leipzig)** — Working student / Research assistant (01/2026–03/2026)  
  Reviewed & prioritized GIS datasets for small natural landscape feature mapping.
- **iDiv (Halle–Jena–Leipzig)** — Research volunteer (12/2025)  
  Evaluated multisource GIS data for mapping features; data availability + scale limitations + ecological relevance.
- **Göttingen University** — Research volunteer (09/2025–12/2025)  
  Digitized floristic data into GIFT matrices; modelled multidimensional trait-space shifts in R.

---

## 🎓 Education
- **M.Sc. Ecology & Environmental Changes** — Bielefeld University (10/2024–2026)  
- **B.Sc. Botany, Zoology & Chemistry** — MDU (08/2019–08/2022)

---

## 🗣️ Languages
- English (IELTS) • German (A2)

---

## 📫 Contact
- Email: **pranjel200109@gmail.com**
- Location: **Bielefeld, Germany**
- Site: https://bit.ly/3Z4lSOD

---

<div align="center">

<!-- GitHub stats (kept on-theme) -->
<img height="165" src="https://github-readme-stats.vercel.app/api?username=pranjel-ecologist&show_icons=true&hide_border=true&bg_color=0D1117&title_color=FF3FB4&icon_color=22D3EE&text_color=F8FAFC"/>
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=pranjel-ecologist&layout=compact&hide_border=true&bg_color=0D1117&title_color=A855F7&text_color=F8FAFC"/>

<br/><br/>

<!-- Footer -->
<img alt="Neon Divider" width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0D1117&height=8&section=footer"/>

<p>
  <sub style="color:#94A3B8;">
    Built in dark mode. Field-tested. Lab-approved. Model-validated. 🌙✨
  </sub>
</p>

</div>
