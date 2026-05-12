# AI Pocket Historian

**Open Source Historical Research Software**

> Turn scattered historical documents into structured, evidence-based research and portable, self-contained history documents.

---

## What It Does

AI Pocket Historian is a single HTML file that turns old newspaper clippings, letters, photographs, census records, and family documents into structured genealogical research — using AI to do in seconds what would take a researcher hours.

Drop in a 1912 Iowa marriage notice. The AI identifies every person named, their relationships, the date and place, and cross-references it against your other sources. If a name is spelled differently in a 1914 obituary than it was in the marriage record, the conflict is flagged automatically.

The result is a portable, self-contained research document — complete with citations, person profiles, a narrative reconstruction, and a timeline — that you can print, download, or share.

---

## The Payoff

A real example from Clayton County, Iowa:

> **George W. White** (b. ~1860) appears across four sources. His son **Earl White** married **Mabel Conner** on June 14, 1912 at the Methodist church — witnessed by siblings Bessie and Howard White.
>
> ⚠ **Conflict detected:** The 1914 Elkader Gazette names Earl's father "George *H.* White" while the 1912 marriage notice uses "George *W.* White." Middle initial inconsistency flagged for resolution.
>
> Three generations documented. 8 persons · 6 events · 2 places · 1 conflict flagged.

That analysis took 30 seconds.

---

## Features

**Input — bring anything:**
- Upload letters, photographs, newspapers, records, and scanned documents
- Paste text directly from any source
- Record audio that is automatically transcribed into text
- Add photographs from your phone camera
- Custom metadata: date, publisher, source, caption, page number

**AI Analysis:**
- Extract people, places, events, organizations, and relationships
- Detect conflicts in names, dates, places, and relationships (GPS-4 standard)
- Surface emerging trends and patterns across your entire document collection
- Chat directly with your sources — ask the AI questions, get cited answers
- Generate semantic data cluster maps of your research

**Research Outputs — every record produces:**

| Output | Description |
|--------|-------------|
| Structured Analysis | Full AI analysis with citation links to source documents |
| Genealogical Proof Record | Documented to the GPS (Genealogical Proof Standard) |
| Historical Account | Narrative summary with full source citations |
| Narrative Reconstruction | Evidence woven into a coherent family story |
| Research Notes | Recorded chat sessions saved with the record |
| Conflict Resolution | Side-by-side comparison of conflicting evidence |
| Research Recommendations | AI-suggested next steps and records to seek |
| Person Profiles | Detailed profiles with every mention and source |
| Timeline | Interactive timeline built from extracted events |
| Photographic Evidence | Organized and annotated historical photographs |
| Tags & Themes | Automatic topic and keyword organization |
| Semantic Data Clusters | Visual AI-powered relationship maps |

---

## Getting Started

**1. Download**

Download `zogHist.html` and open it in any modern browser. That's the entire application — one file, no installation, no server.

**2. Get an API key**

AI Pocket Historian uses AI models to analyze your sources. You provide your own key from one of these providers — setup takes about 3 minutes and costs a few cents per analysis:

- [Anthropic (Claude)](https://console.anthropic.com) — recommended
- [OpenAI (GPT-4)](https://platform.openai.com)
- [Google (Gemini)](https://aistudio.google.com)

Enter your key via **⋯ → Provider API Keys** inside the app.

**3. Add a source**

Click **+ Add**, drop in an image or paste some text, fill in what you know about it, and click **Save**.

**4. Generate**

Click **✦ Generate** and watch the AI go to work.

---

## Why Open Source Matters

- **The software is free.** You only pay the AI provider for actual usage — typically a few cents per analysis. The software itself costs nothing.
- **Everything stays on your computer.** Your family documents, your research, your API key — none of it is uploaded to any server. Ever.
- **It runs from a single HTML file.** Save it to your hard drive and it runs locally, offline, forever. No dependency on this repository staying online. No worry about a service being discontinued.
- **You can modify it.** It's your software. Change anything you want.

---

## Who It's For

Families who want to preserve their history. Genealogists who want to work faster. Historians, librarians, and archivists who need a lightweight research tool. Anyone who has a box of old documents and wonders who those people were.

---

## Technical Notes

- Single-file HTML/CSS/JavaScript — no framework, no build step, no dependencies
- Works in Chrome, Firefox, Safari, and Edge on desktop and mobile
- Records saved as JSON files on your local device
- Supports Anthropic, OpenAI, and Google Gemini API providers
- Supports PNG, JPG, GIF, WEBP, and PDF input
- OCR powered by your chosen AI provider
- Exports a JSON file of all records in context which can then be uploaded directly into any AI chat (ChatGPT, Claude, Gemini) and queried conversationally — ask questions about your research, generate summaries, or explore patterns beyond what this app provides.
---

## License

MIT License — free to use, modify, and distribute.

---


