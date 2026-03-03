# Perplexity Super-Skills Collection

> **10 comprehensive super-skills** merging [Perplexity Computer](https://perplexity.ai) built-in skills with [Claude Code](https://docs.anthropic.com/en/docs/agents-and-tools/claude-code/overview) expertise into unified, production-ready skill files for AI-powered workflows.

## What Are Super-Skills?

Each super-skill is a single, comprehensive `.md` file that combines multiple Perplexity Computer skills with complementary Claude Code capabilities into one unified reference. They're designed to be used as context/instructions for AI agents, giving them deep domain expertise across an entire functional area.

**Each skill includes:** gap analysis matrices, structured workflows, templates, decision frameworks, quality checklists, and real-world examples.

---

## The Collection

| # | Super-Skill | Domain | Key Capabilities | Repo |
|---|------------|--------|-----------------|------|
| 1 | **AI Agent Builder** | AI/ML Engineering | Agent architecture (ReAct, Plan-Execute), MCP servers, RAG pipelines, subagent coordination, prompt engineering | [ai-agent-super-skill](https://github.com/get-zeked/ai-agent-super-skill) |
| 2 | **Dev & Engineering** | Full-Stack Development | Architecture, frontend, backend, fullstack, QA/testing, DevOps, CI/CD, code review | [dev-engineering-super-skill](https://github.com/get-zeked/dev-engineering-super-skill) |
| 3 | **Marketing** | Marketing & Growth | Content creation, SEO, campaign planning, demand gen, analytics, competitive intelligence, PMM, ASO | [marketing-super-skill](https://github.com/get-zeked/marketing-super-skill) |
| 4 | **Sales** | Sales & Revenue | Prospecting, outreach sequences, objection handling, pipeline management, customer interviews, RICE prioritization | [sales-super-skill](https://github.com/get-zeked/sales-super-skill) |
| 5 | **Finance** | Finance & Accounting | Financial statements, month-end close, audit prep, investment research, ML forecasting, data engineering | [finance-super-skill](https://github.com/get-zeked/finance-super-skill) |
| 6 | **Legal** | Legal Operations | Contract review & redlining, NDA triage, compliance (GDPR/CCPA), risk assessment, legal writing | [legal-super-skill](https://github.com/get-zeked/legal-super-skill) |
| 7 | **Product Management** | Product & UX | Feature specs/PRDs, roadmap prioritization (RICE/MoSCoW), sprint/agile ops, metrics/OKRs, UX research, design systems | [pm-super-skill](https://github.com/get-zeked/pm-super-skill) |
| 8 | **Operations & CX** | Ops & Customer Experience | Ticket triage, customer responses, escalation workflows, KB management, sprint ops, quality verification | [operations-cx-super-skill](https://github.com/get-zeked/operations-cx-super-skill) |
| 9 | **Research & Knowledge** | Research & Data | Deep research workflows, knowledge graphs, content extraction, data exploration, statistical analysis, visualization | [research-knowledge-super-skill](https://github.com/get-zeked/research-knowledge-super-skill) |
| 10 | **Content & Creative** | Creative Studio | Video, speech, image generation, web building, canvas design, algorithmic art, brand guidelines, frontend design | [content-creative-super-skill](https://github.com/get-zeked/content-creative-super-skill) |

---

## How to Import Skills

### Method 1: Upload the SKILL.md File Directly (Recommended)

This is the fastest way to add any super-skill to your Perplexity Computer.

1. **Pick a skill** from the table above and click through to its repo
2. **Click on `SKILL.md`** in the file list to open the skill file
3. **Download the file:**
   - Click the **Download raw file** button (downward arrow icon) near the top-right of the file view
   - This saves `SKILL.md` to your computer
4. **Open Perplexity Computer** at [computer.perplexity.ai](https://computer.perplexity.ai)
5. **Go to the Skills page** from the left sidebar
6. **Click "Create skill"**
7. **Select "Upload a skill"**
8. **Drag and drop** your downloaded `SKILL.md` file (or click to browse and select it)
9. **Done!** The skill is now in your **My Skills** library and will activate automatically when relevant

> **File requirements:** Each `SKILL.md` includes the required YAML frontmatter with `name` and `description` fields, so it's ready to upload as-is.

### Method 2: Copy-Paste the Skill Content

If you prefer not to download files:

1. **Navigate to the skill repo** and open `SKILL.md`
2. **Click the "Raw" button** to see the plain text version
3. **Select all** (`Ctrl+A` / `Cmd+A`) and **copy** (`Ctrl+C` / `Cmd+C`)
4. **In Perplexity Computer**, go to Skills > Create skill > **Create with Perplexity**
5. **Paste the content** as your skill definition
6. Perplexity will process and add it to your skill library

### Method 3: Clone the Entire Collection

For developers who want all 10 skills locally:

```bash
# Clone this hub repo
git clone https://github.com/get-zeked/perplexity-super-skills.git

# Or clone individual skill repos
git clone https://github.com/get-zeked/ai-agent-super-skill.git
git clone https://github.com/get-zeked/dev-engineering-super-skill.git
git clone https://github.com/get-zeked/marketing-super-skill.git
git clone https://github.com/get-zeked/sales-super-skill.git
git clone https://github.com/get-zeked/finance-super-skill.git
git clone https://github.com/get-zeked/legal-super-skill.git
git clone https://github.com/get-zeked/pm-super-skill.git
git clone https://github.com/get-zeked/operations-cx-super-skill.git
git clone https://github.com/get-zeked/research-knowledge-super-skill.git
git clone https://github.com/get-zeked/content-creative-super-skill.git
```

Then upload each `SKILL.md` file using Method 1 above.

### Method 4: Use with Claude Code or Other AI Agents

These skills aren't limited to Perplexity Computer:

1. **Open the `SKILL.md` file** from any skill repo
2. **Copy the contents** (skip the YAML frontmatter if your platform doesn't support it)
3. **Add as system context** in your AI agent's configuration:
   - **Claude Code:** Add as a custom instruction or project knowledge file
   - **Cursor/Windsurf:** Add as a `.cursorrules` or project rules file
   - **Custom agents:** Include as system prompt context
4. The agent now has deep domain expertise for that functional area
5. **Pro tip:** Combine multiple skills for cross-functional workflows (e.g., Marketing + Sales for a GTM strategy)

---

### Tips for Getting the Most Out of Super-Skills

- **Skills activate automatically** — Once imported, Perplexity Computer will use them when your task matches the skill's domain
- **Skills work together** — Perplexity can combine multiple super-skills in a single task (e.g., Research + Content for a blog post)
- **Manage your skills** — View, search, and delete imported skills from the **My Skills** tab in Perplexity Computer
- **Keep skills updated** — Star the repos to get notified of updates, then re-upload the latest `SKILL.md`

### Finding Skills by Topic

All repos are tagged with the [`perplexity-super-skill`](https://github.com/topics/perplexity-super-skill) topic for easy discovery on GitHub.

---

## Skill Architecture

Every super-skill follows a consistent structure:

```
SKILL.md
+-- Gap Analysis         - What Perplexity has vs. what Claude Code adds
+-- Domain Sections      - Deep-dive into each capability area
|   +-- Workflows        - Step-by-step processes
|   +-- Templates        - Ready-to-use output formats
|   +-- Decision Trees   - When to use what approach
|   +-- Quality Checks   - Validation criteria
+-- Integration Points   - How sections work together
```

---

## Contributing

These skills are actively maintained and improved. If you find gaps or have suggestions:
- Open an issue on the specific skill repo
- PRs welcome for improvements and corrections

---

**Built by [@get-zeked](https://github.com/get-zeked)** | Merging the best of Perplexity Computer + Claude Code into unified super-skills
