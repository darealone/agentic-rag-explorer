# Agentic RAG Explorer 🧠

**See how intelligent RAG systems think – and what they cost.**

An interactive visualization tool that reveals the decision-making process behind Agentic RAG systems. Built to make complex AI concepts tangible, transparent, and actionable.

![Version](https://img.shields.io/badge/version-2.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![No Dependencies](https://img.shields.io/badge/dependencies-none-brightgreen)

[🚀 Live Demo](https://github.com/darealone/agentic-rag-explorer) • [📖 Article](#) • [🐛 Report Bug](https://github.com/darealone/agentic-rag-explorer/issues)

---

## Why This Exists

Most explanations of Agentic RAG tell you *what* it is. This tool shows you **how it thinks**.

You don't just read about router decisions, confidence scores, or fallback mechanisms — you **see them happen** in real time. You watch the system weigh its options, choose a source, validate relevance, and adapt when it's wrong.

**The difference?**  
Understanding vs. knowing.  
Feeling vs. reading.  
Insight vs. information.

---

## What You'll Learn

### 1. **Router Confidence: Where Uncertainty Lives**
See all three data sources compared side-by-side:
- 🏥 Medical Q&A Database
- 📋 Device Manual Database  
- 🌐 Web Search (SerperAPI)

**Why it matters:** The magic happens at 48% vs 52% — close decisions reveal where good prompt engineering makes the difference.

### 2. **Cost vs Quality: The Bill Nobody Shows You**

| Metric | Traditional RAG | Agentic RAG |
|--------|----------------|-------------|
| 💰 Cost per Query | ~$0.02 | ~$0.08 |
| ⚡ Latency | ~800ms | ~3.2s |
| 🎯 Accuracy | ~75% | ~94% |
| 🔄 API Calls | 2-3 | 5-8 |

**The truth:** Agentic RAG is **4x more expensive** and **4x slower** — but also **25% more accurate**.

**The question:** What's more expensive — $0.06 or a wrong answer in healthcare?

### 3. **Decision Process: Step-by-Step Transparency**
Watch the system move through:
1. **Router Decision** – Which source to query
2. **Retrieval** – Fetch relevant documents
3. **Relevance Check** – Validate context quality
4. **Generate** – Create answer or fallback to web search

---

## Features

✅ **Zero Dependencies** – Pure HTML, CSS, and Vanilla JavaScript  
✅ **Fully Offline** – Works without internet after download  
✅ **Interactive Scenarios** – 4 pre-built examples showing different routing patterns  
✅ **Real-time Animation** – Watch decisions unfold step-by-step  
✅ **Educational Insights** – Learn *why* each decision was made  
✅ **Mobile Responsive** – Works on any device  

---

## Quick Start

### Option 1: Download and Open
1. Download `index.html`
2. Double-click to open in your browser
3. Done. No setup required.

### Option 2: Serve Locally
```bash
# If you want to run it with a local server
python -m http.server 8000
# Then open http://localhost:8000
```

### Option 3: GitHub Pages
Fork this repo and enable GitHub Pages in Settings → Pages → Deploy from main branch.

---

## How to Use

1. **Try the Example Scenarios**  
   Click any of the 4 pre-built scenarios to see different routing behaviors.

2. **Enter Your Own Questions**  
   Type any query and watch the system decide which source to use.

3. **Observe the Confidence Bars**  
   See how the router weighs all three options before choosing.

4. **Understand the Trade-offs**  
   Compare cost, speed, and accuracy between Traditional and Agentic RAG.

---

## Example Scenarios

### Scenario 1: Perfect Match
**Query:** "What are the treatments for Kawasaki disease?"  
**Result:** Medical Q&A (92% confidence) → Retrieval → Relevant → Generate

### Scenario 2: Web Search Required
**Query:** "What export tariffs apply to medical devices from China?"  
**Result:** Web Search (95% confidence) → Current economic data needed

### Scenario 3: Technical Device Info
**Query:** "What dialysis machines exist for neonatal patients?"  
**Result:** Device Manual (88% confidence) → Technical specifications

### Scenario 4: False Positive + Fallback
**Query:** "What medications help with COVID-19?"  
**Result:** Medical Q&A (68% confidence) → Irrelevant → Fallback to Web Search

---

## Technical Architecture

### Router Logic
The router analyzes query intent using pattern matching and keyword detection to determine:
- Medical knowledge (symptoms, treatments, diseases)
- Technical specifications (devices, manuals, equipment)
- Current data (economic, political, recent events)

### Confidence Scoring
Each query is scored against all three sources:
- **90-100%** High confidence, clear match
- **70-89%** Medium confidence, likely correct
- **50-69%** Low confidence, uncertain decision
- **< 50%** Rejected, alternative source chosen

### Relevance Validation
After retrieval, the system checks if retrieved context matches the query intent:
- ✅ **Relevant** → Generate answer
- ❌ **Irrelevant** → Fallback to web search

---

## Use Cases

### For Developers
- Understand RAG architecture patterns
- Learn prompt engineering for routing
- Explore confidence-based decision making

### For Educators
- Teaching AI/ML concepts visually
- Demonstrating LLM decision processes
- Explaining cost/quality trade-offs

### For Product Managers
- Evaluate RAG implementation strategies
- Understand operational costs
- Assess accuracy requirements

### For Researchers
- Analyze routing patterns
- Study confidence thresholds
- Explore multi-source retrieval

---

## Educational Value

This tool bridges the gap between **knowing** and **understanding**.

You can read about Agentic RAG in papers and blog posts. But until you *see* the router hesitate between two 48% confidence scores, you don't really understand where the complexity lives.

**What makes this different:**
- It's not just a diagram — it's an experience
- It doesn't just explain decisions — it shows uncertainty
- It doesn't hide costs — it makes them tangible

---

## Roadmap

🔮 **Coming Soon:**
- [ ] Model comparison mode (GPT-4 vs Claude vs Gemini routing patterns)
- [ ] Custom scenario builder (define your own data sources)
- [ ] Export/share functionality (PNG screenshots, shareable links)
- [ ] Real API integration option (live queries)
- [ ] Extended metrics (token usage, embedding costs)

---

## Contributing

Contributions welcome! Whether it's:
- New example scenarios
- UI improvements  
- Additional routing logic
- Better documentation
- Bug fixes

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

MIT License - See [LICENSE](LICENSE) for details.

---

## Credits

**Created by Al Hashemi** – Creative AI Specialist  
Built for people who want to understand how AI thinks, not just what it does.

Inspired by the need to make complex AI systems transparent, accessible, and emotionally resonant.

---

## Connect

- 💼 LinkedIn: (https://www.linkedin.com/in/al-hashemi/)

---

**Remember:** The goal isn't just to build RAG systems.  
The goal is to build RAG systems that **think** — and that we can **trust**.

This tool helps you see the difference.
