# Strategic Documentation Template

## Overview

A hierarchical pyramid documentation structure for strategic planning and execution, based on best practices in organizational documentation and the Minto Pyramid Principle.

**Purpose:** Provide a clear, scalable framework for documenting strategy from ideation through execution.

## Documentation Structure

This template follows a hierarchical pyramid documentation structure:

### Layer 0: Ideas & Research (`00-ideas/`)
- Exploration and hypothesis tracking
- Status-based progression system
- Gateway to formal documentation

### Layer 1: Vision & Foundation (`01-foundation/`)
- Core vision and mission statements
- Lean Canvas business model
- Fundamental strategic assets

### Layer 2: Strategy & KPIs (`02-strategy/`)
- 12-month strategic plans
- Market positioning
- Key performance indicators

### Layer 3: OKRs & Roadmaps (`03-execution/`)
- Quarterly objectives and key results
- Implementation roadmaps
- Experiment logs

### Layer 3.5: Specs (`03-specs/`)
- Product requirement documents (PRDs)
- Design specifications
- Bridge between strategy and execution

### Layer 4: Playbooks & Templates (`04-playbooks/`)
- Operational procedures
- Reusable templates
- Standard operating procedures

### Layer 5: Research Library (`05-research/`)
- Supporting research and evidence
- Interview transcripts and analysis
- External references and studies
- (Empty folder - add research as needed)

## Getting Started

### Initial Setup

1. **Start with Foundation** (`01-foundation/`)
   - Define your vision and mission
   - Complete the Lean Canvas
   
2. **Develop Strategy** (`02-strategy/`)
   - Set 12-month objectives
   - Define market positioning
   
3. **Plan Execution** (`03-execution/`)
   - Create quarterly OKRs
   - Build implementation roadmap
   
4. **Track Ideas** (`00-ideas/`)
   - Log strategic initiatives
   - Track progression through validation

### File Naming Conventions

- Use lowercase with hyphens: `my-document.md`
- No spaces, underscores, or capital letters
- Keep filenames descriptive but concise

## Documentation Principles

1. **Hierarchical Flow:** Ideas → Foundation → Strategy → Execution
2. **Evidence-Based:** Support claims with data and research
3. **Status Tracking:** Clear progression from exploration to implementation
4. **Cross-Referencing:** Use `@docs/` paths for internal links
5. **Changelog Discipline:** Document every update

## Document Standards

Each document should include:
- **H1 Title** at the top
- **Date line** (format: Month DD, YYYY)
- **Owner** designation
- **Changelog** at the bottom

Example:
```markdown
# Document Title
September 07, 2025
Owner: [Your Name]

[Content...]

---

> **Changelog:** _September 07, 2025 — Initial document created._
```

## Status System (for Ideas)

- 🔴 **Exploring:** Hypothesis stage; shaping problem and outcome
- 🟠 **Drafting:** Brief exists; scope and metrics defined
- 🟢 **Validated:** Evidence accepted; ready to promote
- 🔵 **Promoted:** Moved to strategy/execution layers
- ⚪ **Merged:** Combined with another idea
- ⚫ **Archived:** Closed with documented reason

## Workflow

### For New Ideas
1. Add to `00-ideas/index.md` with 🔴 status
2. Develop and validate (🟠 → 🟢)
3. Promote to appropriate layer (🔵)
4. Create formal documentation in target layer

### For Strategy Updates
1. Review current state in relevant layer
2. Propose changes with clear rationale
3. Update documentation with changelog
4. Cascade changes to dependent documents

### For Execution Planning
1. Link to strategy documents
2. Define measurable objectives
3. Create detailed roadmaps
4. Track experiments and learnings

## Best Practices

### Writing Style
- **Tone:** Concise, active voice
- **Language:** American English
- **Citations:** Inline Markdown links

### Version Control
- Commit after significant changes
- Use descriptive commit messages
- Maintain changelog in each document

### Collaboration
- Assign clear ownership
- Review cycles for major changes
- Regular synchronization meetings

## Templates Included

- **Ideas Index:** Central tracking for all strategic ideas
- **Vision & Mission:** Organizational purpose and direction
- **Lean Canvas:** Business model overview
- **Strategy Document:** Annual strategic planning
- **Market Positioning:** Competitive differentiation
- **Execution Roadmap:** Quarterly OKRs and milestones
- **PRD Template:** Product requirement specifications
- **Playbook Template:** Operational procedures

## Maintenance

### Regular Reviews
- **Weekly:** Update idea statuses
- **Monthly:** Review OKR progress
- **Quarterly:** Refresh strategy and roadmaps
- **Annually:** Revisit vision and foundation

### Archive Policy
- Keep historical versions in changelogs
- Archive completed initiatives with outcomes
- Maintain lessons learned documentation

## Support

This template is designed to be self-documenting. Each layer includes:
- Clear purpose statements
- Format guidelines
- Update protocols
- Cross-references to related documents

## Contributing

When adding new document types:
1. Follow existing naming conventions
2. Include standard headers (title, date, owner)
3. Add to appropriate layer (00-04)
4. Update this README if adding new patterns

## License

This template is provided as-is for organizational use. Adapt as needed for your specific context.

---

_Last Updated: September 07, 2025_
