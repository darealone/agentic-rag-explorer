# Contributing to Agentic RAG Explorer

First off — thank you for considering contributing to this project. 🙏

This tool exists to make AI decision-making transparent and accessible. Your contributions help that mission.

## Ways to Contribute

### 🐛 Report Bugs
Found something broken? Open an issue with:
- Clear description of the problem
- Steps to reproduce
- Expected vs actual behavior
- Browser/device information

### 💡 Suggest Features
Have an idea? We'd love to hear it:
- Describe the feature and why it matters
- How it improves understanding of Agentic RAG
- Any implementation thoughts

### 📝 Improve Documentation
- Fix typos or unclear explanations
- Add examples or use cases
- Translate to other languages
- Improve code comments

### 🎨 Enhance the UI
- Better visualizations
- Improved animations
- Mobile responsiveness
- Accessibility improvements

### 🔧 Add Functionality
- New example scenarios
- Additional routing patterns
- Export/share features
- Performance improvements

## Development Guidelines

### Keep It Simple
This tool has **zero dependencies** for a reason. Before adding any library, ask:
- Does this meaningfully improve understanding?
- Can we achieve it with vanilla JavaScript?
- Will it still work offline?

### Make It Educational
Every feature should answer: "What does this teach about Agentic RAG?"

If it's just cool but not educational, it might not belong here.

### Prioritize Clarity
Code should be readable by someone learning web development.
- Use clear variable names
- Comment complex logic
- Avoid clever tricks that obscure meaning

## Code Style

- **Indentation:** 4 spaces
- **Naming:** camelCase for functions, PascalCase for classes
- **Comments:** Explain *why*, not *what*
- **Functions:** Keep them small and focused

## Pull Request Process

1. **Fork the repo** and create your branch from `main`
2. **Test thoroughly** across browsers (Chrome, Firefox, Safari)
3. **Update documentation** if you change functionality
4. **Write a clear PR description** explaining what and why
5. **Keep commits atomic** — one logical change per commit

## Commit Message Format

```
<type>: <subject>

<body>
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Visual/CSS changes
- `refactor`: Code restructure (no behavior change)
- `perf`: Performance improvement
- `test`: Adding tests

**Example:**
```
feat: Add model comparison mode

Shows how different LLMs (GPT-4, Claude, Gemini) would route 
the same query differently. Helps users understand routing 
variation across models.
```

## Questions?

Open an issue with the label `question` — no question is too small.

## Code of Conduct

Be kind. Be constructive. Be curious.

We're here to learn together, not to judge or gatekeep.

---

**Remember:** The goal isn't perfect code.  
The goal is making AI decision-making **visible** and **understandable**.

If your contribution does that, we want it.
