# 🔍 Research Software Readiness Checker Pro

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Made with](https://img.shields.io/badge/Made%20with-HTML%2FCSS%2FJS-orange)]()

## 📌 Overview

**Research Software Readiness Checker Pro** is an automated web-based tool that evaluates software repositories against six research-readiness criteria and provides a weighted score out of 100 with actionable recommendations. Built with HTML, CSS, and JavaScript, it runs entirely in the browser with no installation required.

## 🎯 Features

| Feature | Description |
|---------|-------------|
| **Automated Analysis** | Scans any local repository folder |
| **6 Quality Checks** | README, License, Tests, CI/CD, Versioning, Citation |
| **Weighted Scoring** | README(20), License(15), Tests(25), CI/CD(15), Versioning(10), Citation(15) |
| **Smart Recommendations** | Prioritized fixes with code examples |
| **Multiple Exports** | PDF, HTML report, JSON data |
| **History Tracking** | Persistent scan history (last 20 scans) |
| **Visual Feedback** | Confetti animation for scores ≥80 |

## 🚀 How to Use

### Option 1: Download and Run Locally
1. Download `index.html` from this repository
2. Double-click to open in **Chrome/Edge/Brave** (Firefox not supported)
3. Click **"Select Folder to Analyze"**
4. Choose any software repository folder
5. View score, check results, and recommendations

### Option 2: Use GitHub Pages (Live Demo)
Click here: [Live Demo](https://prathikshaethiraji2024-bit.github.io/research-software-readiness-checker/)

## 📊 Scoring System

| Score Range | Grade | Meaning |
|-------------|-------|---------|
| 70-100 | GOOD | Research Ready |
| 40-69 | MEDIUM | Needs Improvement |
| 0-39 | POOR | Not Research Ready |

## 🧪 Test the Tool

Use the sample repositories in the **`SVV SAMPLES/`** folder:

| Repository | Expected Score |
|------------|----------------|
| sample_good | 95/100 |
| sample_medium_50 | 50/100 |
| sample_medium_45 | 45/100 |
| sample_poor | 20/100 |
| sample_empty | 0/100 |

### Sample Repository Details

**sample_good** (95/100) - Contains:
- Complete README with installation and usage instructions
- MIT License file
- Tests folder with test files
- GitHub Actions CI/CD configuration
- VERSION file
- CITATION.md file

**sample_medium_50** (50/100) - Contains:
- Partial README (installation only)
- MIT License file
- Tests folder (empty)
- VERSION file
- Missing CI/CD and Citation

**sample_medium_45** (45/100) - Contains:
- Minimal README
- Tests folder with test files
- package.json with version
- Citation info in README
- Missing License and CI/CD

**sample_poor** (20/100) - Contains:
- Minimal README
- One test file (no test folder)
- Missing License, CI/CD, Version, Citation

**sample_empty** (0/100) - Empty folder

## 🛠️ Technologies Used

| Technology | Version | Purpose |
|------------|---------|---------|
| HTML5 | Latest | Page structure |
| CSS3 | Latest | Styling, animations |
| JavaScript | ES6+ | Core logic, API integration |
| File System Access API | Web API | Folder selection |
| LocalStorage API | Web API | History persistence |
| jsPDF | 2.5.1 | PDF export |
| canvas-confetti | 1.0 | Celebration animations |

## 🌐 Browser Compatibility

| Browser | Support | Notes |
|---------|---------|-------|
| Google Chrome | ✅ Full | Best experience |
| Microsoft Edge | ✅ Full | Chromium-based |
| Brave | ✅ Full | Chromium-based |
| Firefox | ❌ Not Supported | Lacks File System Access API |
| Safari | ❌ Not Supported | Lacks File System Access API |


## 👩‍💻 Authors

| Name | Register Number |
|------|-----------------|
| **Prathiksha Ethiraji** | 24MID0295 |
| **Darshana Priya R** | 24MID0211 |

## 📚 Course Information

| Field | Details |
|-------|---------|
| **Course** | Software Verification and Validation |
| **Course Code** | CSI3014 |
| **Slot** | G1+TG1 |
| **Guided By** | Dr. Naveenkumar J |
| **Institution** | VIT Chennai |

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

## 📝 How to Cite

If you use this tool in your research, please cite as:

```bibtex
@software{Ethiraji_Research_Software_Readiness_2026,
  author = {Prathiksha Ethiraji and Darshana Priya R},
  title = {Research Software Readiness Checker Pro},
  year = {2026},
  url = {https://github.com/prathikshaethiraji2024-bit/research-software-readiness-checker},
  version = {1.0.0}
}
