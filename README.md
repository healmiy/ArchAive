# 🏛️ ArchAive

<div align="center">

### Clean Markdown over PDFs (great for Obsidian and now AIs)

**I turn painful, uncopyable, bloated PDFs into clean, aesthetic, AI-ready `.md` files.**

[![Format](https://img.shields.io/badge/Format-Clean_Markdown-black?style=for-the-badge&logo=markdown)](https://commonmark.org/)
[![Obsidian Ready](https://img.shields.io/badge/Vault-Obsidian_Ready-7C3AED?style=for-the-badge&logo=obsidian)](https://obsidian.md/)
[![AI Ready](https://img.shields.io/badge/AI-RAG_%26_LLM_Ready-FF6F00?style=for-the-badge&logo=google)](https://notebooklm.google.com/)
[![OCR Engine](https://img.shields.io/badge/Pipeline-Mistral_OCR_%2B_Docling-3B82F6?style=for-the-badge)](https://github.com/healmiy/ArchAive)
[![Status](https://img.shields.io/badge/Status-Work_in_Progress_🚧-yellow?style=for-the-badge)](https://github.com/healmiy/ArchAive)
[![Focus](https://img.shields.io/badge/Domain-Malaysia_Tax_%26_MFRS-EF4444?style=for-the-badge)](https://github.com/healmiy/ArchAive)

</div>

---

## ⚡ TL;DR

Ever tried copying a table from an official government PDF?  
Congrats, your clipboard is now abstract art. 🎨💀

**ArchAive** is my personal hobby project where I convert PDFs (focusing on 🇲🇾 Taxation) and rebuild them into clean structured Markdown.

No bloat. No broken tables. Ready for Obsidian note-taking and AI RAG-ing.

> [!NOTE]
> ### 🚧 Work in Progress (Still Ongoing!)
> This archive is actively evolving and not yet a finished product:
> - **More Acts to come**: Not all Acts and statutory orders related to Malaysian taxation and accounting have been converted/published yet.
> - **Skill distillation in progress**: Not all converted `.md` files have been QC'ed

---

## 🥊 The Matchup: Cursed PDF vs. ArchAive

| 💀 The Cursed PDF | 🗿 ArchAive Markdown (`.md`) |
| :--- | :--- |
| **Copy-paste disaster** (broken line breaks everywhere) | **Pure plain text** (copies cleanly anywhere) |
| **Scrambled tables** (calculation ladders get ruined) | **Crisp GitHub pipe tables** (properly formatted) |
| **LLMs choke on it** (split context, OCR hallucinations) | **AI & RAG ready** (NotebookLM, Claude & GPT feast on it) |
| **"What changed in the new gazette?"** 🤷‍♂️ (Can't diff) | **`git diff`** shows the exact amended sentence in 0.1s |
| **Needs heavy PDF bloatware** to open | **Instant** in Obsidian, VS Code, or terminal |
| **50 MB** scanned file | **40 KB** featherweight file |

---

## 🗃️ What's in the Vault?

A curated arsenal of Malaysia's heaviest statutory & accounting texts:

```
ArchAive/
├── 🏛️ Tax Acts/        👉 Act 53 (ITA 1967), RPGT 1976, Sales & Service Tax (SST)
├── 📜 Public Rulings/   👉 LHDNM Public Rulings (2021–2026) translated BM ⟷ EN
├── 📊 MFRS/            👉 Full Malaysian Financial Reporting Standards (MFRS 1–141)
├── ⚖️ Tax Cases/       👉 High Court & SCIT judicial precedents
└── 🔮 .obsidian/       👉 Pre-tuned for Obsidian graph & local AI connections
```

- 🏛️ **[Tax Acts](./Tax%20Acts/)**: Yes, the entire **Income Tax Act 1967 (Act 53)** — over 1MB of pure, searchable markdown.
- 📜 **[Public Rulings](./Public%20Rulings/)**: Rulings from 2021 through 2026, with examples, schedules, and step-by-step tax computations intact.
- 📊 **[MFRS](./MFRS/)**: Every MASB standard (MFRS 9, 15, 16, 17, 101–141) structured for instant reference.
- ⚖️ **[Tax Cases](./Tax%20Cases/)**: Key tax jurisprudence ready to cite in seconds.

---

## 🛠️ The Pipeline (How the Magic Happens)

```mermaid
flowchart LR
    A["📄 Cursed PDF"] --> B["👁️ Mistral OCR / Docling"]
    B --> C["🌐 BM ⟷ EN Legal Polish"]
    C --> D["📐 Rebuild Tables & Math"]
    D --> E["✨ Markdown"]
```

1. **AI Vision & Layout OCR**: Using **Mistral OCR** and **Docling** to parse multi-column insanity.
2. **Translation & Context**: Converting official Bahasa Melayu gazettes to English without losing statutory legal terms.
3. **Table & Math Restoration**: Rebuilding multi-step calculation ladders and tax schedules by hand and script.
4. **Zero-Hallucination Audit**: Cross-checked against official gazettes line-by-line.

---

## 🚀 How to Use This Vault

### 1. In Obsidian (Instant 2nd Brain 🧠)
```bash
git clone https://github.com/healmiy/ArchAive.git
```
Open Obsidian $\to$ **Open folder as vault** $\to$ Select `ArchAive`. Done. Graph view, backlinks, and offline search are ready.

### 2. In AI & RAG (NotebookLM, Claude, ChatGPT 🤖)
Just drop any `.md` file into **NotebookLM** or your custom RAG pipeline. No chunking errors. No PDF ingestion headaches.

### 3. In the Terminal (Faster Than Light ⚡)
```bash
# Find Section 33(1) deductions in ITA 1967 instantly
rg "33\(1\)" "Tax Acts/"

# Search all withholding tax rulings
rg -i "withholding tax" "Public Rulings/"
```

---

## Any help is appreciated 🤝

Have an unreadable, scanned, or locked PDF you need liberated into clean Markdown?
- 🐛 **Found a typo / OCR glitch?** Open a [PR or Issue](https://github.com/healmiy/ArchAive/issues).
- 💡 **Got a doc request?** Drop an issue with the link!

---

<div align="center">

Crafted with ❤️ by **[@healmiy](https://github.com/healmiy)**

*Free the text. Ditch the PDF.*

</div>
