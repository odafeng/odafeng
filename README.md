# Shih-Feng (Fredric) Huang, MD · 黃士峯

<p align="center">
  <strong>Surgical Data Scientist · Colorectal Surgeon</strong><br/>
  <em>clinical problems → structured data → deployable systems</em>
</p>

<p align="center">
  <a href="https://orcid.org/0000-0002-8037-4074"><img alt="ORCID" src="https://img.shields.io/badge/ORCID-0000--0002--8037--4074-a6ce39?style=flat-square&logo=orcid&logoColor=white" /></a>
  <a href="https://research.shihfenghuang.com"><img alt="Research website" src="https://img.shields.io/badge/Research-research.shihfenghuang.com-2E86AB?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://shihfenghuang.com"><img alt="Clinical website" src="https://img.shields.io/badge/Clinical-shihfenghuang.com-0F766E?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://blog.shihfenghuang.com"><img alt="Blog" src="https://img.shields.io/badge/Blog-blog.shihfenghuang.com-21759B?style=flat-square&logo=wordpress&logoColor=white" /></a>
  <a href="https://pypi.org/project/ctpelvimetry/"><img alt="ctpelvimetry on PyPI" src="https://img.shields.io/pypi/v/ctpelvimetry?style=flat-square&logo=pypi&logoColor=white&label=ctpelvimetry&color=3776AB" /></a>
</p>

---

I build evidence-backed surgical data systems — turning raw CT, intraoperative video, and postoperative records into reproducible analysis, open-source software, and deployable clinical tools.

> 高雄榮總大腸直腸外科主治醫師  
> 專注於將臨床問題轉化為可計算、可重現、可部署的資料科學系統

---

## ⚙️ Evidence → Deployment

| Clinical problem | Peer-reviewed evidence | Reproducible code | Deployed artifact |
| --- | --- | --- | --- |
| Mid-pelvic workspace from CT | [Auto-ISD · *IJCARS* 2026](https://doi.org/10.1007/s11548-026-03606-2) | [`auto-isd-pelvimetry`](https://github.com/odafeng/auto-isd-pelvimetry) | [Interactive demo](https://auto-isd-demo.vercel.app) · [`ctpelvimetry`](https://pypi.org/project/ctpelvimetry/) |
| Robotic surgery learning curves | [*J Robotic Surg.* 2026](https://doi.org/10.1007/s11701-025-03088-5) | [`rissa-ML-learning-curve`](https://github.com/odafeng/rissa-ML-learning-curve) | Reusable analysis workflow |
| Postoperative symptom monitoring | IRB-approved study | [`hemorrhoids-postop`](https://github.com/odafeng/hemorrhoids-postop) | [Live clinical-research PWA](https://prototype-zeta-black.vercel.app) |

---

## 🚀 Featured Work

### 🔬 Medical Imaging: Publication → Reusable Software

- [`auto-isd-pelvimetry`](https://github.com/odafeng/auto-isd-pelvimetry) — peer-reviewed [IJCARS paper](https://doi.org/10.1007/s11548-026-03606-2), open-source pipeline, and [interactive demo](https://auto-isd-demo.vercel.app)
- [`ctpelvimetry`](https://github.com/odafeng/ctpelvimetry) — installable [PyPI package](https://pypi.org/project/ctpelvimetry/) with a Python API, CLI, automated QC, and tests

### 🎥 Surgical Intelligence

- [`rissa-ML-learning-curve`](https://github.com/odafeng/rissa-ML-learning-curve) — reproducible ML analysis of robotic surgery learning curves; published in the [*Journal of Robotic Surgery*](https://doi.org/10.1007/s11701-025-03088-5)
- [`cholec80-phase-recognition`](https://github.com/odafeng/cholec80-phase-recognition) — surgical phase recognition pipeline comparing non-causal MS-TCN with causal TeCNO models

### 📊 Clinical Prediction & NLP

- [`Stage_III_Colon_EDR`](https://github.com/odafeng/Stage_III_Colon_EDR) — externally validated early-recurrence modeling workflow with manuscript-aligned notebooks; patient-level data excluded
- [`llm-extractor`](https://github.com/odafeng/llm-extractor) — local-first LLM pipeline for extracting structured fields from rectal cancer pathology reports

### 📱 Deployed Clinical Systems

- [`hemorrhoids-postop`](https://github.com/odafeng/hemorrhoids-postop) — postoperative symptom monitoring and AI-assisted patient education [PWA](https://prototype-zeta-black.vercel.app), deployed in an IRB-approved study
- [`MedFeedJournalTracker`](https://github.com/odafeng/MedFeedJournalTracker) — automated literature monitoring with LLM filtering and daily LINE notifications

---

## 📚 Selected Publications

Focus: surgical AI, learning curves, and outcome modeling

- Automated CT-based pelvimetry — *Int J Comput Assist Radiol Surg.* 2026 [`doi`](https://doi.org/10.1007/s11548-026-03606-2)
- Machine learning–based learning curve analysis — *J Robotic Surg.* 2026 [`doi`](https://doi.org/10.1007/s11701-025-03088-5)
- Video-based RA-CUSUM proficiency assessment — *Int J Colorectal Dis.* 2026 [`doi`](https://doi.org/10.1007/s00384-025-05078-3)

Full list → [ORCID](https://orcid.org/0000-0002-8037-4074)

---

## 🧰 Methods & Stack

- **Data Science**: pandas, scikit-learn, lifelines, PyTorch
- **Imaging**: CT processing, TotalSegmentator, 3D Slicer
- **Causal Inference**: overlap weighting, RMST, survival modeling
- **Engineering**: Python packaging, pytest, GitHub Actions, Next.js, TypeScript, PostgreSQL

---

## 🧭 Direction

Building the infrastructure of **Surgical Data Science**:

- From clinical intuition → quantitative modeling
- From retrospective data → real-time systems
- From isolated studies → reproducible pipelines
- **Now building:** surgical video analytics — automated phase recognition & workflow decomposition ([`cholec80-phase-recognition`](https://github.com/odafeng/cholec80-phase-recognition): MS-TCN vs causal TeCNO)
