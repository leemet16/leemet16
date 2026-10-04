### Hi, I'm Lee 👋

I build learning systems for technical, client-facing teams, and I build with AI to stay honest about what I teach. I work on enterprise AI enablement and adoption, and I'm completing an MA in AI & Societies on human-AI co-creation.

Most of my current work lives in private repositories (studio code and thesis data), so here's what's behind the contribution graph.

#### 🎨 Zhudiyo: an AI-native comic studio ([cilstudio.tech](https://cilstudio.tech))

A multi-agent production studio and the practice arm of my MA thesis. A human director works with a studio of 80+ agents across six production stages, from story to finished pages.

- **Agents:** Google ADK, with LiteLLM routing across frontier models. Stronger models lead high-judgment stages; lighter models handle mechanical work.
- **State, not prose:** canonical story state lives in Postgres as relational spines (subjects, beats, panels) with stable IDs. Agents use typed domain operations instead of generic file editing; summary views like the World Sheet and Story Map are derived on read.
- **Review with a human in charge:** reviewing agents return structured findings rather than editing directly. The human accepts, rejects, or applies them, and rejected points are suppressed in application code, outside the model's turn.
- **Provenance:** intent records whether each choices were made by an agent or a person.
- **Lessons I write about:** tool routing (models reach for generic tools unless docstrings say clearly when *not* to use them), cost and latency trade-offs in model routing, and why structured artifacts beat long prose for multi-agent work.

#### 📄 Research

- [The Workflow as Medium: A Framework for Navigating Human-AI Co-Creation](https://arxiv.org/abs/2511.18182) (arXiv, 2025)
- [Perceptions of Agentic AI in Organizations: Implications for Responsible AI and ROI](https://arxiv.org/abs/2504.11564) (arXiv, 2025)
- *Patterns-Based Engineering: Successfully Delivering Solutions via Patterns* (Addison-Wesley, 2010), plus three US patents on software pattern automation
- [Google Scholar](https://scholar.google.ca/citations?user=r89xgQUAAAAJ&hl=en)

#### 🔗 Elsewhere

[LinkedIn](https://www.linkedin.com/in/ackermanlee/) · [cilstudio.tech](https://cilstudio.tech) · Calgary, Canada
