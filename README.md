# Shih-Feng Huang 黃士峯

<p align="center">
  <strong>Surgical Data Scientist · Colorectal Surgeon</strong><br/>
  <em>clinical problems → structured data → deployable systems</em>
</p>

<p align="center">
  <a href="https://orcid.org/0000-0002-8037-4074"><img src="https://img.shields.io/badge/ORCID-0000--0002--8037--4074-a6ce39?style=flat-square&logo=orcid&logoColor=white" /></a>
  <a href="https://shihfenghuang.com"><img src="https://img.shields.io/badge/Website-shihfenghuang.com-2E86AB?style=flat-square&logo=googlechrome&logoColor=white" /></a>
  <a href="https://blog.shihfenghuang.com"><img src="https://img.shields.io/badge/Blog-blog.shihfenghuang.com-21759B?style=flat-square&logo=wordpress&logoColor=white" /></a>
  <a href="https://pypi.org/project/ctpelvimetry/"><img src="https://img.shields.io/pypi/v/ctpelvimetry?style=flat-square&logo=pypi&logoColor=white&label=ctpelvimetry&color=3776AB" /></a>
  <a href="https://pypi.org/project/ctpelvimetry/"><img src="https://img.shields.io/pypi/dm/ctpelvimetry?style=flat-square&logo=pypi&logoColor=white&label=downloads&color=3776AB" /></a>
</p>

---

I build end-to-end surgical data systems — turning raw CT, intraoperative video, and postoperative records into reproducible analysis and deployable clinical tools.

> 高雄榮總大腸直腸外科主治醫師  
> 專注於將臨床問題轉化為可計算、可重現、可部署的資料科學系統

---

## ⚙️ Surgical Data Pipeline (Core System)

```text
            CT Imaging
                │
         Feature Extraction
                │
        Difficulty Modeling
                │
   Intraoperative Video / Workflow Analysis
                │
   Postoperative Outcomes / PRO / Prediction
```

### 🧠 Preoperative
- Automated CT-based pelvimetry
- Surgical difficulty modeling (FREDRIC framework)

### 🎥 Intraoperative
- Learning curve modeling (RA-CUSUM)
- Video-based workflow analysis

### 📊 Postoperative
- Outcome prediction (ML / survival analysis)
- Digital follow-up & PRO systems

---

## 🚀 Featured Systems

### 🔬 CT Pelvimetry Pipeline
[`ctpelvimetry`](https://github.com/odafeng/ctpelvimetry) — 🟢 `pip install ctpelvimetry`
→ Fully automated CT-based pelvimetry
→ Published & validated (IJCARS) · distributed via PyPI

---

### 📈 Learning Curve Intelligence
[`RiSSA_ML_Learning_Curve`](https://github.com/odafeng/RiSSA_ML_Learning_Curve) — 📄 paper + code
→ ML-based surgical safety profiling
→ Published in *Journal of Robotic Surgery*

---

### 📊 Clinical Outcome Modeling
[`Stage_III_Colon_EDR`](https://github.com/odafeng/Stage_III_Colon_EDR) — 📄 research code
→ Early recurrence prediction
→ Multi-center validation

---

### 📱 Surgical Follow-up Platform
[`Hemorrhoids_PostOp`](https://github.com/odafeng/Hemorrhoids_PostOp) — 🔒 IRB study · deployed
→ Digital postoperative monitoring system
→ Deployed in IRB-approved clinical study

---

### 🎥 Surgical Video Analytics
[`cholec80-phase-recognition`](https://github.com/odafeng/cholec80-phase-recognition) — 🟢 open-source · active
→ Automated surgical phase recognition
→ Two-stage pipeline: MS-TCN (non-causal) vs TeCNO (causal MS-TCN)

---

## 📚 Selected Publications

Focus: surgical AI, learning curves, and outcome modeling

- Machine learning–based learning curve analysis — *J Robotic Surg.* 2026 [`doi`](https://doi.org/10.1007/s11701-025-03088-5)
- Video-based RA-CUSUM proficiency assessment — *Int J Colorectal Dis.* 2026 [`doi`](https://doi.org/10.1007/s00384-025-05078-3)
- Robotic single-stapling vs double-stapling anastomosis — *J Robotic Surg.* 2025 [`doi`](https://doi.org/10.1007/s11701-025-02609-6)

Full list → [ORCID](https://orcid.org/0000-0002-8037-4074)

---

## 🧰 Methods & Stack

- **Data Science**: pandas, scikit-learn, lifelines, PyTorch
- **Imaging**: CT processing, TotalSegmentator, 3D Slicer
- **Causal Inference**: overlap weighting, RMST, survival modeling
- **Systems**: Next.js, TypeScript, PostgreSQL

---

## 🧭 Direction

Building the infrastructure of **Surgical Data Science**:

- From clinical intuition → quantitative modeling
- From retrospective data → real-time systems
- From isolated studies → reproducible pipelines
- **Now building:** surgical video analytics — automated phase recognition & workflow decomposition ([`cholec80-phase-recognition`](https://github.com/odafeng/cholec80-phase-recognition): MS-TCN vs causal TeCNO)
