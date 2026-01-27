# SaMD Regulatory Pathway Navigator

[![License: CC BY-NC 4.0](https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc/4.0/)

An interactive decision tree and comprehensive regulatory analysis tool to help researchers and developers navigate FDA regulations for Software as a Medical Device (SaMD). Created by Tamiko Eto, MA, CIP.

## 🎯 What This Tool Does

This free resource helps you:
- Determine if your software qualifies as a medical device
- Understand the distinction between medical devices and general wellness products
- Navigate Clinical Decision Support (CDS) exclusion criteria
- Assess study-specific risk (Significant Risk vs. Nonsignificant Risk)
- Understand the critical difference between "clinical investigation" and "clinical evaluation"
- Identify appropriate regulatory pathways and IRB requirements

## 🚀 Quick Start

### Option 1: Use the Interactive Web Tool
1. Download `samd_decision_tree.html`
2. Open it in any web browser (Chrome, Firefox, Safari, Edge)
3. No installation or server required!

### Option 2: Read the Comprehensive Analysis
Open `regulatory_analysis_verified.md` for an in-depth regulatory analysis with full citations to 21 CFR 56, 812, FDA guidance documents, and IMDRF standards.

## 📋 Features

### Interactive Decision Tree
- **Step-by-step guidance** through regulatory determinations
- **Educational content** explaining key regulatory concepts
- **General wellness checkpoint** to address common misclassifications
- **Risk mitigation assessment** for nuanced NSR/SR determinations
- **Back button** to revise answers
- **Mobile-responsive** design

### Comprehensive Regulatory Analysis Document
- **Two-step regulatory framework** (device determination + study risk classification)
- **General wellness analysis** explaining why disease-specific chatbots don't qualify
- **Clinical evaluation vs. clinical investigation** distinction for SaMD
- **Full regulatory citations** (21 CFR 56, 812, FDA/IMDRF guidance)
- **Practical recommendations** for IRB submissions

## 🎓 Who Should Use This

- **Researchers** developing AI/ML healthcare software
- **IRB administrators** reviewing device studies
- **Regulatory affairs professionals** in digital health
- **Academic investigators** working on SaMD projects
- **Startup founders** in the medical device space
- **Compliance officers** at healthcare institutions

## 📚 Regulatory Framework Covered

This tool is based on current FDA regulations and guidance as of January 2026:

- **21 CFR Part 56** - Institutional Review Board Requirements
- **21 CFR Part 812** - Investigational Device Exemptions
- **FDA CDS Guidance** (2022, updated 2026) - Clinical Decision Support Software
- **FDA General Wellness Guidance** (2026) - Policy for Low Risk Devices
- **IMDRF SaMD Clinical Evaluation** (N41FINAL:2017) - Adopted by FDA
- **21 CFR Part 50** - Protection of Human Subjects
- **21 CFR Part 820** - Quality System Regulation

## 🔍 Key Concepts Explained

### Why This Matters: Common Misconceptions

1. **"We're just developing an algorithm, so we don't need IRB review"**
   - ❌ **Wrong for medical devices.** Clinical evaluation (broader than clinical investigation) includes development activities and requires IRB oversight.

2. **"Our diabetes education chatbot is general wellness"**
   - ❌ **Wrong.** Disease-specific risk assessment using clinical data is a medical device, not general wellness.

3. **"If patients see the outputs, it's automatically Significant Risk"**
   - ❌ **Not always.** With adequate risk mitigation protocols, studies may qualify as NSR even when outputs are visible.

## 📖 Example Use Cases

### Use Case 1: AI Diabetes Management Chatbot
**Scenario:** Patient-facing conversational agent using clinical data to provide personalized diabetes education and risk assessment.

**Determination:**
- ✅ Medical Device (patient-facing, disease-specific)
- ❌ NOT General Wellness (uses clinical data for disease-specific recommendations)
- Study Risk: Depends on whether outputs influence care and adequacy of safeguards

### Use Case 2: Clinical Decision Support for Radiologists
**Scenario:** AI that analyzes medical images and provides diagnostic suggestions to radiologists.

**Determination:**
- ✅ Medical Device (processes medical images)
- ❌ NOT excluded CDS (acquires/processes medical images)
- Study Risk: Depends on study procedures and risk mitigation

### Use Case 3: General Fitness Tracker
**Scenario:** App that tracks steps and encourages 30 minutes of daily exercise for general heart health.

**Determination:**
- ✅ May qualify as General Wellness (population-level advice, no disease-specific risk assessment)
- No device regulations apply (if truly general wellness)

## 🛠️ Technical Details

### Interactive Tool
- **Technology:** Pure HTML/CSS/JavaScript with React
- **Dependencies:** React 18 (loaded via CDN), Tailwind CSS (loaded via CDN)
- **Browser Support:** All modern browsers (Chrome, Firefox, Safari, Edge)
- **No server required:** Runs entirely client-side

### Files Included
```
├── samd_decision_tree.html          # Interactive decision tree (standalone)
├── regulatory_analysis_verified.md   # Comprehensive regulatory analysis
├── README.md                         # This file
└── LICENSE                           # License terms
```

## 📝 Citation

If you use this tool in your work, please cite:

```
Eto, T. (2026). SaMD Regulatory Pathway Navigator. 
TechInHSR LLC. https://github.com/[your-username]/samd-regulatory-navigator
```

## ⚖️ Legal Disclaimer

This tool provides educational information about FDA regulations and is not a substitute for:
- Legal advice from a licensed attorney
- Regulatory consultation from a qualified regulatory affairs professional
- Official determinations from your Institutional Review Board
- Guidance from the FDA

**The IRB makes the final determination** of device status and study risk classification. This tool provides preliminary assessments to help you prepare for IRB review.

Regulatory requirements may change. Always consult current FDA guidance and regulations.

## 🤝 Contributing

Found an error or have a suggestion? Please:
1. Open an issue on GitHub
2. Describe the regulatory concern or improvement
3. Include relevant FDA guidance citations if applicable

## 📧 Contact

**Tamiko Eto, MA, CIP**  
TechInHSR LLC  
Website: [techinshsr.com](https://techinshsr.com)

- OECD.AI Expert Working Group Advisor
- CAIDP Senior Teaching Fellow
- 20+ years experience in research ethics and regulatory compliance

## 🎓 About TechInHSR

TechInHSR is an AI research ethics consulting practice specializing in:
- IRB training and consultation
- AI governance frameworks for research
- Regulatory strategy for digital health
- Research ethics program development

Learn more at [techinshsr.com](https://techinshsr.com)

## 🌟 Support This Work

If you find this tool valuable:
- ⭐ Star this repository
- 🔗 Share with colleagues
- 📧 Provide feedback
- 🤝 Contribute improvements

## 📅 Version History

### Version 1.0 (January 2026)
- Initial release
- Interactive decision tree
- Comprehensive regulatory analysis
- General wellness checkpoint
- Risk mitigation pathway
- Based on FDA guidance through January 2026

## 🔗 Related Resources

- [FDA Digital Health Center of Excellence](https://www.fda.gov/medical-devices/digital-health-center-excellence)
- [21 CFR Part 812 - Investigational Device Exemptions](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-H/part-812)
- [21 CFR Part 56 - Institutional Review Boards](https://www.ecfr.gov/current/title-21/chapter-I/subchapter-A/part-56)
- [FDA CDS Software Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/clinical-decision-support-software)
- [FDA General Wellness Guidance](https://www.fda.gov/regulatory-information/search-fda-guidance-documents/general-wellness-policy-low-risk-devices)

---

**Made with ❤️ for the research ethics and digital health communities**

*Empowering researchers to navigate complex regulations with confidence*
