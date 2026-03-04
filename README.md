# ETC - Engineering the Conversation

A professional prompt engineering platform that transforms unstructured AI interactions into repeatable, high-quality prompts through guided frameworks and real-time feedback.

🔗 **Live App:** [etc-prompt-builder.vercel.app](https://etc-prompt-builder.vercel.app)

---

## 🌟 What is ETC?

ETC teaches structured prompting through progressive frameworks, providing real-time quality feedback and demonstrating value through before/after AI output comparisons. Whether you're a change management professional, business analyst, or knowledge worker, ETC helps you create professional-grade prompts in minutes instead of hours.

---

## 🚀 Quick Start

1. **Visit** [etc-prompt-builder.vercel.app](https://etc-prompt-builder.vercel.app)
2. **Select a framework** from the sidebar (start with "Structured Prompt")
3. **Fill in the fields** as you type, watch the live preview update
4. **Check quality signals** for real-time feedback
5. **Click Copy** when ready to use your prompt
6. **Save to Library** for future reuse

---

## 📚 Features

### **5 Prompt Frameworks**

**Level 1 - Structure the Prompt:**
- **Structured Prompt** - Foundation: Persona + Task + Context
- **Few-Shot Prompt** - Teach by example with input/output pairs
- **Chain-of-Thought** - Force step-by-step reasoning for complex problems

**Level 2 - Structure the Thinking:**
- **Task Decomposition** - Break complex work into sequential stages
- **Decision Framework** - Structured comparative evaluation

### **Supporting Features**
- ✅ **Live Preview** - See your prompt assemble in real-time
- ✅ **Quality Signals** - Color-coded feedback (green/yellow/red)
- ✅ **Prompt Library** - Save, search, and reuse your best prompts
- ✅ **Export/Import** - Backup your library as JSON file
- ✅ **Examples Tab** - See weak vs. strong prompts with actual AI outputs
- ✅ **Guide Tab** - Learn when to use each framework
- ✅ **Light/Dark Themes** - Accessible design with theme toggle
- ✅ **Mobile Responsive** - Works on phones, tablets, and desktop
- ✅ **Bullet Toggle** - Format Context field with bullets

---

## 💡 Tips & Best Practices

### **Getting Started**

**Start Simple:**
- Begin with **Structured Prompt** (Persona + Task + Context)
- Master the basics before moving to Level 2 frameworks
- Use the **Examples tab** to see what "good" looks like

**Use Quality Signals:**
- Green dots = You're on the right track
- Yellow dots = Could be more specific
- Red dots = Missing critical information
- Read the feedback messages - they're actionable!

**Leverage the Library:**
- Save prompts you've tested and refined
- Add tags for easy searching (e.g., "executive-comms", "analysis")
- **Export your library** regularly as backup (⬇ Export Library button)

### **Building Effective Prompts**

**Persona Tips:**
- Be specific: "Senior change strategist" > "Expert"
- Include expertise level: "10 years in Fortune 500 transformation"
- Define perspective: "You understand executive communication"

**Task Tips:**
- Use action verbs: Write, Analyze, Compare, Generate, Evaluate
- Specify deliverable: "Write a 250-word email" not "help with communication"
- Be precise about what you want

**Context Tips:**
- Who's the audience? (executives, engineers, customers)
- What's the situation? (new policy, crisis, opportunity)
- What constraints exist? (timeline, tone, complexity)
- Use **• Bullets toggle** for clarity

**Constraints Tips:**
- Length: Word count or time to read
- Tone: Professional, casual, urgent, reassuring
- Style: Bullet points, narrative, Q&A format
- Audience level: Technical depth, jargon usage

**Output Format:**
- Choose from 9 presets (Prose, Bullets, Table, JSON, etc.)
- This guides the AI's response structure

### **Framework Selection Guide**

**Use Structured Prompt when:**
- Creating any type of content
- You need a solid foundation
- Task is straightforward
- Example: Executive emails, summaries, explanations

**Use Few-Shot Prompt when:**
- You want specific style or format
- Showing examples is easier than explaining
- Pattern recognition is key
- Example: Product descriptions, consistent formatting

**Use Chain-of-Thought when:**
- Problem requires analysis
- Multiple steps are involved
- You want reasoning shown
- Example: Strategic analysis, troubleshooting, planning

**Use Task Decomposition when:**
- Output is long or complex
- Work naturally breaks into phases
- Each stage builds on previous
- Example: Strategy documents, comprehensive reports

**Use Decision Framework when:**
- Comparing 2+ options
- Need structured evaluation
- Want defendable recommendation
- Example: Vendor selection, go/no-go decisions

### **Advanced Tips**

**Iterate in Layers:**
1. Start with basic structure
2. Add examples or reasoning steps
3. Refine constraints and format
4. Save when satisfied
5. Test and adjust

**Use Examples Tab:**
- See real before/after AI outputs
- Understand why strong prompts work
- Learn from concrete comparisons

**Combine Techniques:**
- Use Few-Shot within other frameworks
- Add reasoning steps to complex decisions
- Layer constraints for precision

**Version Control:**
- Save multiple versions as you refine
- Export library before major changes
- Name prompts descriptively: "Q4-Exec-Update-v2"

---

## 🔧 Technical Details

- **Technology:** Pure HTML/CSS/JavaScript (no dependencies)
- **Storage:** Browser localStorage + manual export/import
- **Deployment:** Vercel with automatic GitHub deployment
- **File Size:** ~75KB (single HTML file)
- **Browser Support:** Chrome 90+, Firefox 88+, Safari 14+
- **Accessibility:** WCAG 2.1 Level AA compliant

---

## 💾 Data & Privacy

**Your Data is Local:**
- Prompts saved in **browser localStorage** (automatically)
- No cloud storage, no servers, no tracking
- Data stays on your device

**Backup Your Work:**
- Click **⬇ Export Library** to download backup file
- Store backup file anywhere (Desktop, cloud storage, etc.)
- Click **⬆ Import Library** to restore from backup
- Export regularly as safety measure

**Limitations:**
- Data is per-browser (Chrome vs. Firefox = separate libraries)
- Clearing browser data deletes library (use Export first!)
- Incognito/Private browsing doesn't persist data
- ~5MB storage limit per browser

---

## 🐛 Troubleshooting

**Library not saving between sessions?**
- Check if you're in Incognito/Private browsing
- Verify browser allows localStorage
- Export library as backup precaution

**Prompts not loading correctly?**
- Ensure you selected the right framework
- Check that all required fields are filled
- Try resetting and starting fresh

**Mobile layout issues?**
- Try portrait orientation
- Ensure browser is updated
- Tabs can scroll horizontally if needed

**Quality signals not updating?**
- Make sure you're typing in the active framework's fields
- Framework-specific fields only appear when that framework is selected

---

## 📖 Learn More

**Tabs:**
- **Build** - Active workspace for creating prompts
- **Examples** - Weak vs. strong comparisons with AI outputs
- **Guide** - Framework explanations and best practices

**Resources:**
- [Anthropic Prompt Engineering Guide](https://docs.anthropic.com/claude/docs/prompt-engineering)
- [OpenAI Prompt Engineering Guide](https://platform.openai.com/docs/guides/prompt-engineering)

---

## 🗺️ Roadmap

**Version 2.0 (Planned):**
- Multi-dimensional prompt scorecard
- Teaching mode with interactive overlays
- Use case starter library (pre-built templates)
- Version history with diff comparison
- Output structure presets

**Version 3.0+ (Future):**
- Prompt testing sandbox with inline execution
- Cognitive architecture mode (multi-agent workflows)
- Team collaboration features
- Advanced analytics dashboard

---

## 🙋 Support & Feedback

- **GitHub Issues:** [Report bugs or request features](https://github.com/68Craiger/etc-prompt-builder/issues)
- **Creator:** Trevor Langton - [trevorlangton.com](https://trevorlangton.com)
- **Questions?** Open a discussion on GitHub

---

## 📜 License

MIT License - Free to use, modify, and distribute

---

## 🎯 Philosophy

ETC is built on the principle that **structured thinking compounds**. By teaching frameworks instead of just providing templates, we help users build transferable skills that improve over time. Every prompt is an opportunity to practice clarity, precision, and intentional design.

---

**Built with ❤️ for better AI conversations**
