# UBalt AI Policy Generator

[![Live Demo](https://img.shields.io/badge/Live-Demo-brightgreen?style=for-the-badge)](https://tinyurl.com/ubaipolicygen)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-success?style=for-the-badge)](https://github.com/your-org/ubalt-ai-policy-generator)
[![Single File](https://img.shields.io/badge/Architecture-Single--File-blueviolet?style=for-the-badge)](https://github.com/your-org/ubalt-ai-policy-generator)

> **A zero-dependency, single-file web application that empowers University of Baltimore faculty to generate comprehensive, customizable Generative AI syllabus policies in minutes.**

---

## 🔗 Live Demo

**[🚀 Launch the AI Policy Generator →](https://tinyurl.com/ubaipolicygen)**

---

## 📋 Table of Contents

- [Overview](#-overview)
- [Features](#-features)
- [AI Usage Levels](#-ai-usage-levels-tiered-framework)
- [Built-in Reference Materials](#-built-in-reference-materials)
- [Getting Started](#-getting-started)
- [Usage Guide](#-usage-guide)
- [Technical Architecture](#️-technical-architecture)
- [Deployment](#-deployment)
- [Development Guidelines](#-development-guidelines)
- [Contributing](#-contributing)
- [License](#-license)
- [Acknowledgments](#-acknowledgments)

---

## 🎯 Overview

The **UBalt AI Policy Generator** is a standalone, client-side web application designed to help faculty and instructors at the **University of Baltimore** quickly generate clear, professional syllabus statements regarding the use of Generative AI in their courses.

With a guided 5-step wizard, faculty can choose between a **predefined tiered framework** or a **fully custom policy path**, configure permitted tools and usage expectations, and instantly export a ready-to-use syllabus statement — all without any login, server, or software installation.

---

## ✨ Features

### 🧭 Interactive 5-Step Wizard
A clean, intuitive interface guides users from policy approach selection all the way through to final export, with clear progress tracking at every step.

### 🔀 Dual Policy Approaches

| Approach | Best For | Description |
|----------|----------|-------------|
| **Tiered Framework** | Faculty who want a standardized policy | Choose from 6 predefined UBalt AI usage levels, from "No AI Use" to "AI Collaborative Tasks" |
| **Custom Policy** | Faculty with specific course needs | Explicitly define permitted tools, acceptable use cases, and disclosure requirements |

### 🛡️ Comprehensive Academic Integrity Coverage
Every generated policy automatically incorporates:
- ✅ Rules for academic integrity and ethical AI use
- ✅ Specific consequences for policy violations
- ✅ Campus student support resources (BoodleBox, Writing Center, etc.)

### 📤 One-Click Export Options
| Export Format | Use Case |
|--------------|----------|
| 📋 **Copy to Clipboard** | Instantly paste directly into your syllabus document |
| 📄 **Download `.txt`** | Plain text for any text editor or LMS |
| 📝 **Download `.doc`** | Microsoft Word-compatible format |
| 🖨️ **Print** | Clean, print-optimized layout for hard copies |

### 📚 Built-in Reference Guide
Comprehensive reference materials are embedded directly on the page — no external links needed:
- Full UBalt AI Policy Framework documentation
- AI Use Disclosure Statement template for students
- Citation guidelines (APA 7th Edition, MLA, Chicago)
- Faculty implementation checklist

---

## 📊 AI Usage Levels (Tiered Framework)

The tiered framework provides 6 standardized usage levels to cover every instructional context:

| Level | Name | Summary |
|:-----:|------|---------|
| **1** | 🚫 No AI Use | AI tools are not permitted for any coursework |
| **2** | 🔍 AI for Research Only | AI may support brainstorming/research; not for final submissions |
| **3** | ✏️ AI-Assisted Drafting | AI may assist with drafts; final work must be substantially human-authored |
| **4** | 🔧 AI as a Tool | AI tools permitted with proper citation and disclosure |
| **5** | 🤝 AI Integration | AI is actively encouraged as part of the learning process |
| **6** | 🤖 AI Collaborative Tasks | Assignments explicitly designed for human-AI collaboration |

---

## 📖 Built-in Reference Materials

### 📋 Student AI Use Disclosure Statement Template
The app provides a ready-to-distribute student disclosure form covering:
- AI tools used (with version)
- Purpose of AI use (brainstorming, editing, research, content generation)
- Specific tasks completed with AI assistance
- Human contribution description
- Reflection on AI strengths/limitations
- Student certification signature

### 📚 Citation Guidelines for AI-Generated Content

**APA Style (7th Edition):**
```
OpenAI. (2024). ChatGPT (Mar 14 version) [Large language model]. https://chat.openai.com/chat
```

**In-text citation:**
```
(OpenAI, 2024)
```

> 📝 *Follow discipline-appropriate citation formats. Consult your library or instructor for MLA, Chicago, and other style requirements.*

---

## 🚀 Getting Started

### Prerequisites

- ✅ A modern web browser (Chrome, Firefox, Safari, or Edge)
- ✅ That's it — no server, no Node.js, no build tools, no dependencies

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-org/ubalt-ai-policy-generator.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd ubalt-ai-policy-generator
   ```

3. **Open the application:**
   ```bash
   open index.html
   # or on Windows:
   start index.html
   ```
   Or simply **double-click** `index.html` in your file explorer.

> 💡 **No build steps. No `npm install`. No configuration.** The entire application runs instantly in any modern browser.

---

## 📖 Usage Guide

### Step-by-Step Workflow

#### Step 1 — Choose Your Approach
Select either the **Tiered Framework** (standardized UBalt levels) or the **Custom Policy** path (fully tailored).

#### Step 2 — Configure Your Policy
- **Tiered path:** Select one of the 6 predefined AI usage levels; each includes built-in disclosure requirements.
- **Custom path:** Specify permitted tools by name (e.g., BoodleBox, ChatGPT, Grammarly), define allowed/prohibited categories, and set usage expectations.

#### Step 3 — Review Usage Expectations & Consequences
Confirm or adjust the automatically generated language covering academic integrity rules and consequences for violations.

#### Step 4 — Add Support Resources
Review and confirm campus student support resources (e.g., BoodleBox, UBalt Writing Center) to be referenced in the policy.

#### Step 5 — Export Your Statement
Review the complete generated syllabus statement, then:
- Copy to clipboard for immediate use
- Download as `.txt` or `.doc`
- Print a clean hard copy

---

## 🛠️ Technical Architecture

### Zero External Dependencies
The entire application is built with pure **HTML5, CSS3, and Vanilla JavaScript** — no frameworks, no libraries, no CDN calls. This ensures maximum portability, longevity, and security.

### Single-File Architecture

```
ubalt-ai-policy-generator/
├── index.html          # Complete application (HTML + CSS + JS in one file)
├── README.md           # This file
└── LICENSE             # License information
```

All markup, styles, and logic are self-contained in `index.html`, making deployment as simple as copying a single file.

### CMS-Safe Scoped CSS
All styles are scoped under the `#ai-policy-app` container ID, ensuring zero conflicts when embedded into UBalt's existing CMS:

```css
/* All styles are namespaced — safe for CMS embedding */
#ai-policy-app .wizard-step { ... }
#ai-policy-app .btn-primary { ... }
#ai-policy-app .policy-output { ... }
```

### Responsive Design
Fully mobile-friendly and accessible across all screen sizes — desktops, tablets, and smartphones — using native responsive CSS techniques.

### Accessibility
Built following **WCAG 2.1 AA** accessibility guidelines to ensure the tool is usable by all faculty, including those using assistive technologies.

---

## 🌐 Deployment

### Option 1: Static Hosting *(Recommended)*
Upload `index.html` to any static file host:

| Platform | Notes |
|----------|-------|
| **GitHub Pages** | Free, version-controlled |
| **Netlify** | Free tier, instant deploys |
| **Vercel** | Free tier, fast CDN |
| **AWS S3** | Scalable, institutional hosting |

### Option 2: CMS Embedding
Embed seamlessly into UBalt's existing CMS:
1. Copy the full contents of `index.html`
2. Paste into a CMS HTML block or custom page template
3. The scoped CSS guarantees no style conflicts with existing site headers, footers, or navigation

### Option 3: Local / Offline Use
Open `index.html` directly in any browser — works fully offline, no internet connection required after download.

---

## 👨‍💻 Development Guidelines

To maintain quality and compatibility when contributing:

- **Single-file architecture** — All code stays within `index.html`
- **CSS scoping** — All styles must remain under `#ai-policy-app`
- **Zero dependencies** — No external libraries, CDN links, or npm packages
- **Cross-browser testing** — Verify on Chrome, Firefox, Safari, and Edge
- **Mobile-first** — All UI changes must be responsive
- **Accessibility** — Follow WCAG 2.1 AA standards throughout
- **Clean exports** — Ensure all 4 export formats (clipboard, `.txt`, `.doc`, print) work correctly after changes

---

## 🤝 Contributing

Contributions are welcome! Here's how to get involved:

1. **Fork** the repository
2. **Create** a feature branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. **Commit** your changes with a clear message:
   ```bash
   git commit -m "feat: add [description of change]"
   ```
4. **Push** to your branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. **Open a Pull Request** with a description of your changes

---

## 📄 License

This project is developed for the **University of Baltimore**. Please refer to the [LICENSE](LICENSE) file for full usage terms and conditions.

---

## 🙏 Acknowledgments

| Contributor | Role |
|-------------|------|
| **University of Baltimore** | Institutional sponsor and AI literacy advocate |
| **UBalt Faculty** | Policy framework feedback and real-world testing |
| **BoodleBox** | Campus collaborative AI platform integrated as a resource |
| **UBalt Writing Center** | Student support resource embedded in generated policies |

---

## 📬 Contact

For questions, feedback, or support regarding the UBalt AI Policy Generator, please contact the **University of Baltimore's Instructional Technology Team**.

---

<p align="center">
  <strong>Built with ❤️ for UBalt Faculty</strong><br>
  <em>Empowering responsible, transparent AI integration in higher education</em><br><br>
  <a href="https://tinyurl.com/ubaipolicygen">🚀 Try it now →</a>
</p>
