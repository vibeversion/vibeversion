# VibeVersion: Version your vision.

The Vibe Coding Revolution Demands a New Kind of Version Control.

Vibe Coding marks a **paradigm shift** to **intent-driven development**. You collaborate directly with AI, guiding it through natural language prompts to generate and refine code. The AI often works autonomously, making broad, cross-component modifications based on your abstract input, ushering in an era of **exploratory programming**.

While Git remains a powerful tool for traditional source code management and collaboration, Vibe Coding's unique dynamics expose fundamental mismatches with Git's core assumptions. **VibeVersion is not intended to replace Git**, but rather to provide the essential, specialized layer needed to manage the nuances of human-AI collaborative development, working seamlessly alongside existing Git workflows.

This revolutionary approach fundamentally clashes with the core assumptions of traditional version control systems like Git:

* **Philosophical Mismatch**: Git's strength lies in tracking human-driven, granular changes, built around the concept of "meaningful commit units." Vibe Coding, however, involves AI making sweeping, often experimental, and sometimes ambiguous changes across the codebase from a single instruction. This creates a profound disconnect in understanding the "what" and "why" within Git's history.
* **Chaotic & Noisy History**: AI's frequent, small modifications, instant rollbacks, and rapid experimentation lead to a commit history filled with "AI auto-updates" and fragmented changes. This results in **"noisy history"** where tracing original intent or debugging becomes a significant challenge, akin to navigating a "spaghetti branch" of countless minor revisions.
* **Invisible Progress**: How do you truly visualize your project's evolution when the core isn't just lines of code, but the continuous, iterative dialogue with your AI partner? Git struggles to convey this narrative of evolving intent and AI response.
* **Bridging Human & AI**: Integrating your own precise manual refinements into an AI-driven workflow becomes cumbersome, lacking clear distinction and easy traceability between human interventions and AI's outputs.

**VibeVersion** is engineered from the ground up to resolve these conflicts, designed specifically for the fluid, **intent-driven**, and **exploratory** nature of Vibe Coding.

## How VibeVersion Transforms Your Workflow

VibeVersion shifts the focus from managing mere code changes to **versioning your entire creative process** with AI.

* **Prompt-Centric & Intent-Driven History**: Every instruction you give your AI, every prompt, becomes a first-class citizen in your project's history. VibeVersion links your prompts directly to the code they generate, ensuring you always know the "why" (the intent) behind the "what" (the code). This makes your history meaningful and highly traceable.
* **Session-Based Workflow for Exploratory Development**: Organize your development journey into distinct "sessions," each with a clear intent and timeframe. This structure inherently supports **exploratory programming**, allowing you to easily revisit, branch from, or discard experimental paths with minimal overhead, preventing history pollution and reducing "commit anxiety."
* **Unified Project Traceability with Semantic Understanding**: Beyond just code, VibeVersion tracks and links all your project assets: prompts, AI-generated code, configurations, and related documentation. It aims to incorporate **semantic understanding** of changes, allowing you to trace the conceptual evolution of features, not just textual diffs.
* **Seamless Human-AI Collaboration**: Integrate your manual code refinements effortlessly. VibeVersion clearly distinguishes human-made changes from AI-generated ones within the history, preserving clarity and allowing for easy **post-hoc commentary and organization** of your interventions.
* **Intuitive Visual Timeline**: Forget cryptic commit messages. Experience your project's history as a living, visual timeline, showcasing key decisions, AI interactions, and the precise moment your vision came to life. This makes the abstract concepts of intent and session tangible and easy to navigate.

---

## VibeVersion vs. Git: A Philosophical Divide

Traditional Git excels at tracking human-driven, granular code changes. However, its core assumptions create fundamental friction points in an AI-accelerated Vibe Coding workflow. VibeVersion directly addresses these:

| Feature/Philosophy      | Git (Traditional VCS)                                      | VibeVersion (For Vibe Coding)                                 | Why it Matters for Vibe Coding                                   |
| :----------------------- | :--------------------------------------------------------- | :------------------------------------------------------------ | :--------------------------------------------------------------- |
| **Core Unit of Change** | **Commit**: A snapshot of code changes, often manual.      | **Prompt/Session**: An expression of intent, an AI interaction, or a focused human work unit. | Captures the *why* (intent) and the *process*, not just the *what*.      |
| **History Focus** | **Code Diffs**: Tracks line-by-line changes over time.     | **Intent & Evolution**: Traces the unfolding vision, AI responses, and human refinements. | Provides semantic meaning and context, transforming noisy history into a clear narrative. |
| **Change Granularity** | Often small, human-crafted increments.                      | Can be vast, broad, AI-generated sweeps or focused human tweaks. | Accommodates AI's broad refactors and micro-changes transparently without manual overhead or complex rebasing. |
| **Collaboration Model** | Human-to-human code sharing and merging.                    | Human-AI partnership, with AI as a first-class collaborator.   | Built for the conversational, iterative nature of AI development. |
| **Traceability** | Code changes traced to commit messages and authors.         | Code traced to its originating prompt, session, and developer's explicit intent. | Essential for understanding AI output, debugging hallucinations, and refining prompts. |
| **Exploratory Workflow** | Branching/reverting can be cumbersome; history accumulates. | Sessions enable fearless experimentation and easy discarding/reversion of trials. | Encourages rapid iteration and reduces "commit anxiety" inherent in exploratory AI work. |
| **Visibility of Progress**| Primarily through `git log` and diff tools.                 | Intuitive visual timelines showing the "story" of development, making abstract concepts tangible. | Makes complex AI-driven evolution immediately comprehensible and navigable.    |

---

## Get Started with VibeVersion

While VibeVersion offers a powerful visual interface for managing your projects, you can quickly integrate it into your command-line workflow.

### Basic CLI Usage

```bash
# Start a new development session with a clear goal
vv start "Implementing the new personalized recommendation engine"

# Record a prompt given to your AI and its generated code
vv prompt "Generate an AI-powered recommendation algorithm based on user browse history."

# View the changes made by your AI in the current session
vv diff

# Commit your manual refinements, explicitly marking your intent
# (e.g., after reviewing and tweaking AI-generated code)
vv commit "Human refinement: Optimized database queries and added comprehensive error handling."

# Revert to a previous session or prompt state
vv revert <session_id_or_prompt_version>

# See your project's history as a linear timeline of sessions and prompts
vv history --timeline

# Export the current VibeVersion state as a clean Git commit
vv export-to-git "Integrate recommendation engine feature"
```

---

## Contributing to VibeVersion

Have an idea to make `VibeVersion` even better? We'd love to hear it! This project is open source, and your contributions are key to shaping the future of AI-driven development.

* **Share Your Ideas**: Open a [discussion](https://github.com/vibeversion/vibeversion/discussions) or submit a [feature request](https://github.com/vibeversion/vibeversion/issues/new?assignees=&labels=feature&projects=&template=feature_request.md&title=).
* **Report Bugs**: Found a glitch? Please open a [bug report](https://github.com/vibeversion/vibeversion/issues/new?assignees=&labels=bug&projects=&template=bug_report.md&title=) so we can fix it.
* **Contribute Code**: Check out our [Contributing Guidelines](CONTRIBUTING.md) to get started with coding.

---

## Learn More

* **Detailed Requirements and Specification** (coming soon!)
* **API Documentation** (coming soom!)
---

## License

`VibeVersion` is released under the [MIT License](LICENSE.md).

---

VibeVersion: Version your vision.
