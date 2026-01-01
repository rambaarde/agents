# Contains Studio AI Agents

A comprehensive collection of specialized AI agents designed to accelerate and enhance every aspect of rapid development. Each agent is an expert in their domain, ready to be invoked when their expertise is needed.

## 📥 Installation & Usage

These agents are designed to be platform-agnostic and can be used with various AI-powered development environments including **Claude Code**, **Cursor**, **Gemini**, or any LLM-based coding assistant that supports context-aware personas.

### For Claude Code
1. **Download this repository:**
   ```bash
   git clone https://github.com/rambaarde/agents.git
   ```

2. **Copy to your agents directory:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```

3. **Restart Claude Code** to load the new agents.

### For Cursor / VS Code with AI
1. Copy the content of the agent markdown file you need.
2. Paste it into your project's `.cursor/rules` file or use it as a "System Prompt" in your AI chat settings.
3. You can also save these as reusable snippets or "Rules for AI" within your IDE configuration.

### For Gemini / Other LLMs
1. Use the agent persona description as the initial system prompt to "roleplay" that specific expert.
2. Example: "Act as the [Agent Name] defined below..." followed by the agent's full markdown content.

## 🚀 Quick Start

Simply describe your task and invoke the appropriate agent persona.

### Example Usage
- "Create a new app for tracking meditation habits" → `rapid-prototyper`
- "What's trending on TikTok that we could build?" → `trend-researcher`
- "Our app reviews are dropping, what's wrong?" → `feedback-synthesizer`
- "Make this loading screen more fun" → `whimsy-injector`

## 📁 Directory Structure

Agents are organized by department for easy discovery:

```
contains-studio-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
├── bonus/
│   ├── joker.md
│   └── studio-coach.md
└── orig-agents/
    ├── README.md
    ├── backend_agent_persona.md
    ├── frontend_agent_persona.md
    ├── refactor_agent_persona.md
    ├── security_agent_persona.md
    ├── seo_specialist_persona.md
    ├── solutions_architect_persona.md
    ├── tester_agent_persona.md
    └── ui_ux_agent_persona.md
```

## 📋 Complete Agent List

### Engineering Department (`engineering/`)
- **ai-engineer** - Integrate AI/ML features that actually ship
- **backend-architect** - Design scalable APIs and server systems
- **devops-automator** - Deploy continuously without breaking things
- **frontend-developer** - Build blazing-fast user interfaces
- **mobile-app-builder** - Create native iOS/Android experiences
- **rapid-prototyper** - Build MVPs in days, not weeks
- **test-writer-fixer** - Write tests that catch real bugs

### Product Department (`product/`)
- **feedback-synthesizer** - Transform complaints into features
- **sprint-prioritizer** - Ship maximum value in 6 days
- **trend-researcher** - Identify viral opportunities

### Marketing Department (`marketing/`)
- **app-store-optimizer** - Dominate app store search results
- **content-creator** - Generate content across all platforms
- **growth-hacker** - Find and exploit viral growth loops
- **instagram-curator** - Master the visual content game
- **reddit-community-builder** - Win Reddit without being banned
- **tiktok-strategist** - Create shareable marketing moments
- **twitter-engager** - Ride trends to viral engagement

### Design Department (`design/`)
- **brand-guardian** - Keep visual identity consistent everywhere
- **ui-designer** - Design interfaces developers can actually build
- **ux-researcher** - Turn user insights into product improvements
- **visual-storyteller** - Create visuals that convert and share
- **whimsy-injector** - Add delight to every interaction

### Project Management (`project-management/`)
- **experiment-tracker** - Data-driven feature validation
- **project-shipper** - Launch products that don't crash
- **studio-producer** - Keep teams shipping, not meeting

### Studio Operations (`studio-operations/`)
- **analytics-reporter** - Turn data into actionable insights
- **finance-tracker** - Keep the studio profitable
- **infrastructure-maintainer** - Scale without breaking the bank
- **legal-compliance-checker** - Stay legal while moving fast
- **support-responder** - Turn angry users into advocates

### Testing & Benchmarking (`testing/`)
- **api-tester** - Ensure APIs work under pressure
- **performance-benchmarker** - Make everything faster
- **test-results-analyzer** - Find patterns in test failures
- **tool-evaluator** - Choose tools that actually help
- **workflow-optimizer** - Eliminate workflow bottlenecks

### Original Agents (`orig-agents/`)
- **backend_agent_persona** - Original backend specialist
- **frontend_agent_persona** - Original frontend specialist
- **refactor_agent_persona** - Original refactoring specialist
- **security_agent_persona** - Original security specialist
- **seo_specialist_persona** - Original SEO specialist
- **solutions_architect_persona** - Original architecture specialist
- **tester_agent_persona** - Original testing specialist
- **ui_ux_agent_persona** - Original UI/UX specialist

## 🎁 Bonus Agents
- **studio-coach** - Rally the AI troops to excellence
- **joker** - Lighten the mood with tech humor

## 📚 Legacy Agents
The `orig-agents/` directory contains the original set of personas that served as the foundation for this expanded system. They are kept for archival purposes and reference.

## 🎯 Proactive Agents

Some agents trigger automatically in specific contexts (especially in Claude Code):
- **studio-coach** - When complex multi-agent tasks begin or agents need guidance
- **test-writer-fixer** - After implementing features, fixing bugs, or modifying code
- **whimsy-injector** - After UI/UX changes
- **experiment-tracker** - When feature flags are added

## 💡 Best Practices

1. **Let agents work together** - Many tasks benefit from multiple agents
2. **Be specific** - Clear task descriptions help agents perform better
3. **Trust the expertise** - Agents are designed for their specific domains
4. **Iterate quickly** - Agents support the 6-day sprint philosophy

## 🔧 Technical Details

### Agent Structure
Each agent includes:
- **name**: Unique identifier
- **description**: When to use the agent with examples (using YAML block scalars for readability)
- **color**: Visual identification
- **tools**: Specific tools the agent can access
- **System prompt**: Detailed expertise and instructions

### Adding New Agents
1. Create a new `.md` file in the appropriate department folder
2. Follow the existing format with YAML frontmatter
3. Include 3-4 detailed usage examples
4. Write comprehensive system prompt (500+ words)
5. Test the agent with real tasks

## 🛠️ Customizing Agents for Your Studio

### Agent Customization Todo List

Use this checklist when creating or modifying agents for your specific needs:

#### 📋 Required Components
- [ ] **YAML Frontmatter**
  - [ ] `name`: Unique agent identifier (kebab-case)
  - [ ] `description`: Detailed description using `|` block scalar
  - [ ] `color`: Visual identification (e.g., blue, green, purple, indigo)
  - [ ] `tools`: Specific tools the agent can access (Write, Read, MultiEdit, Bash, etc.)

#### 🔧 Agent File Structure Template

```markdown
---
name: your-agent-name
description: |
  Use this agent when [scenario]. This agent specializes in [expertise].
  
  Examples:
  
  <example>
  Context: [situation]
  user: "[user request]"
  assistant: "[response approach]"
  <commentary>
  [why this example matters]
  </commentary>
  </example>
  
  <example>
  Context: [situation 2]
  ...
  </example>
color: agent-color
tools: Tool1, Tool2, Tool3
---

# Agent Persona Name

## Core Identity
**Name:** [Name]
**Role:** [Role]
**Expertise:** [Areas of Expertise]

## Core Responsibilities
1. [Responsibility 1]
2. [Responsibility 2]
...

[Detailed system prompt content...]
```

## 🤝 Contributing

To improve existing agents or suggest new ones:
1. Use the customization checklist above
2. Test thoroughly with real projects
3. Document performance improvements
4. Share successful patterns with the community

## 🙏 Credits

This repository is built upon the foundational work of:
- **Michael Galpert** (mgalpert) - for the original `contains-agents` concept and personas.
- **Contains Studio** - for the vision of rapid, agent-assisted development [agents](https://github.com/contains-studio/agents).

I have expanded and modified these original agents to create a fully comprehensive, context-aware studio ecosystem.
