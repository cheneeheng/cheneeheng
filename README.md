<div align="center">

# Chen Ee Heng

**Munich, Germany** · building agentic systems you can audit — and the tools to build them with

</div>

```python
from dataclasses import dataclass, field


@dataclass
class ChenEeHeng:
    """The short version. The long version is on the blog."""

    builds: list[str] = field(default_factory=lambda: [
        "LLM systems that turn regulation into structured, reviewable output",
        "agentic pipelines with a deterministic decision layer underneath",
        "the MLOps plumbing that makes both reproducible",
    ])
    also_builds: list[str] = field(default_factory=lambda: [
        "Claude Code & Codex plugins that guide agents through a product's whole life",
        "backends", "frontends", "the infrastructure in between",
    ])
    cares_about: list[str] = field(default_factory=lambda: [
        "auditability", "evaluation", "knowing why the system said yes",
    ])
    philosophy: str = "follow a problem end to end — from the model to the metal"

    def __repr__(self) -> str:
        return "still building, still writing it all down ↓"
```

## Featured Projects

### Agent tooling

#### [ceh-claude-code-library](https://github.com/cheneeheng/ceh-claude-code-library)
Claude Code plugins that guide autonomous agents through a product's life: shaping the idea, building and proving the software, and getting it in front of the people who should find it. Written for agents first and people second.
`Claude Code` · `plugins & skills` · `agentic workflows`

#### [claude-code-command-center](https://github.com/cheneeheng/claude-code-command-center)
A monorepo of apps, tools and libraries for working with Claude Code day to day: a multi-repo workspace, usage insights and forecasts, plugin toggling, statusline and scheduled session digests.
`Python` · `TypeScript` · `Claude Code`

#### [mcp-cassette](https://github.com/cheneeheng/mcp-cassette)
vcrpy for MCP. Records real agent–server sessions into diffable cassettes and replays them as deterministic mock servers, so agentic systems can be tested deterministically. Published on PyPI.
`Python` · `MCP` · `PyPI`

### Regulated-domain AI

#### [pr-compliance-gate](https://github.com/cheneeheng/pr-compliance-gate)
Reviews pull requests against security, licensing and data-handling policy before merge. An LLM classifies and scores the change; a deterministic policy table makes the decision. The split matters — the judgement is probabilistic, the ruling is not, and the evidence trail survives review. Cost-gated, human-in-the-loop.
`Python` · `LangGraph` · `Claude Agent SDK`

#### [presidio-compliance-stack](https://github.com/cheneeheng/presidio-compliance-stack)
A pip-installable PDPA compliance layer for Malaysian SMEs using AI/LLM tooling with customer data: detection, classification and redaction of personal data. One shared codebase, two packages — `presidio-audit` and `presidio-malaysia`.
`Python` · `Microsoft Presidio` · `PDPA`

#### [mlops-incident-commander](https://github.com/cheneeheng/mlops-incident-commander)
Multi-agent supervision of a live ML model: monitoring, investigation, remediation, and post-mortem generation. Model risk management, applied to production ML.
`Python` · `multi-agent` · `MLOps`

### Coming soon

#### 🌙 Nightshift
Agents that keep working while you're away — long-running, restartable, and learning from past sessions how you would make the call. Private for now; opening up in 2027.

<details>
<summary><b>Earlier work</b></summary>
<br>

- [gradio-chat-agent](https://github.com/cheneeheng/gradio-chat-agent) — a Gradio app with a chat agent that controls the app's own components
- [gradio-svelteflow](https://github.com/cheneeheng/gradio-svelteflow) · [gradio-reactflow](https://github.com/cheneeheng/gradio-reactflow) · [gradio-floating-chatbot](https://github.com/cheneeheng/gradio-floating-chatbot) — custom Gradio components
- [figureflow](https://github.com/cheneeheng/figureflow) — interactive flow diagrams in Python, styled shape-by-shape
- [pose-estimation](https://github.com/cheneeheng/pose-estimation) — a collection of pose estimation models
- [Kaggle2023Contrails](https://github.com/cheneeheng/Kaggle2023Contrails) — Kaggle 2023: identifying aviation contrails from satellite imagery

</details>

## Now — late 2026 → 2027

- 🔭 **Building:** agent tooling for the whole product lifecycle, and agentic workflows for regulated domains — classification with an auditable decision layer underneath
- 🌱 **Exploring:** OpenTelemetry for agent systems, and evaluation harnesses that catch drift before users do
- 🚀 **Next (2027):** opening up Nightshift, and agents that run unattended without losing the evidence trail

<div align="center">

### → I write about all of it

*Engineering notes, machine-learning deep dives, and the things I build along the way.*

[![Read the blog](https://img.shields.io/badge/Read_the_blog-cheneeheng.github.io-0A0A0A?style=for-the-badge&logo=githubpages&logoColor=white)](https://cheneeheng.github.io)

<br>
<img src="./metrics-languages.svg" alt="Most used languages" width="400" align="top" />
<img src="./metrics-calendar.svg" alt="Contribution calendar" width="400" align="top" />
<br>
<img src="./metrics-blog.svg" alt="Latest blog posts" width="808" />
<br>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/ee-heng-chen-dr-ing)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:eeheng.chen@gmail.com)

<sub>Open to interesting problems and the right opportunity — a note on any of the above reaches me.</sub>

</div>
