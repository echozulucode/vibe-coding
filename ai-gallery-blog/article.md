> **AI does not eliminate the need for discipline—it rewards it.** The more structured your process, the more value AI provides.

The projects within this gallery are artifacts from working with and attempting to understand how to scale “vibe coding”.

- Many of these have been open sourced with MIT license (with plan markdown included), and you can find Github links below.
- Many of these are different technology stacks and types of applications that I am not an expert in and of different scope, as I navigate how to manage AI effectively.
- The particularly interesting thing is now the end result, but the process to achieve desired results and related input and output artifacts.

![](./images/6c6e26c8-ac10-469c-a45d-60e37b858969.png align="center")

## Project Estimation Test

A demo Electron desktop application for creating and managing project estimates using a new `.est` file format. Built with React, TypeScript, and Ant Design.

- **Active Development Period** : October 5-8, 2025
- **Lines of Code** : ~6,200+ lines

![](./images/36873e50-fc03-42d1-999a-fd4e096f95a0.png align="center")

![](./images/fcda738a-8405-4939-acc9-c895ca56995e.png align="center")

**Technology Stack**

- **Application Framework**: Electron (for cross-platform desktop application development)
- **Frontend Library**: React (for building the user interface)
- **Language**: TypeScript (for type safety and improved developer experience)
- **Build Tool**: Vite (for fast development and optimized production builds, migrated from Webpack)
- **State Management**: Zustand (lightweight and flexible state management)
- **UI Library**: Ant Design (for pre-built UI components and theming capabilities)
- **Charting Library**: Recharts (for interactive data visualizations)
- **Styling**: CSS Modules with custom properties (for scoped styles and theme customization)
- **File Operations**: `tar.gz` (for handling `.est` file format)
- **Bundler**: ESBuild (used by Vite for fast TypeScript compilation)

## Behavior Pad Gherkin Editor

Behavior Pad is a ridiculously user-friendly Gherkin editor built with Electron, React, TypeScript, and Vite, designed to make behavior-driven development accessible and delightful.

- **Active Development Period**: October 8 - October 12, 2025
- **Lines of Code**: ~6,000 lines (TypeScript/TSX across frontend, Electron, and CLI)
- **Current Version**: v0.3.0
- **Status**: Production-ready with Windows installer; core features complete

![](./images/944a391e-f5d5-40ad-b076-716ef5b7a0c6.png align="center")

![](./images/a8aff47d-1a60-4ef4-86df-53a1a85eb2e2.png align="center")

**Key Features**:

- **Gherkin Syntax Highlighting** - CodeMirror 6 integration with custom Gherkin language support
- **Auto-Formatting** - Intelligent formatter with CLI tool (`gherkin-format`)
- **Table Editor** - Spreadsheet-like editing for Gherkin tables with improved UX
- **Markdown Export** - One-click conversion from Gherkin to Markdown
- **Theme Support** - Light, dark, and system-aware themes with WCAG AA compliance
- **Cross-Platform** - Windows installer (NSIS), macOS (DMG/ZIP), Linux (AppImage/DEB/RPM)
- **File Tree Navigation** - Virtual scrolling with react-window for performance
- **Keyboard-First Design** - Comprehensive shortcuts (⌘B to toggle sidebar, ⌘O to open folder)

**Technology Stack**:

- **Frontend**: React 19, TypeScript, Vite, CodeMirror 6
- **Desktop**: Electron 38, electron-builder
- **UI Components**: Ant Design 5, Radix UI primitives
- **Testing**: Vitest with coverage support
- **CLI**: Standalone CLI tool with @cucumber/gherkin parser
- **Build/Deploy**: Multi-platform installers (Windows NSIS, macOS DMG, Linux AppImage/DEB/RPM)

**AI Generation Notes:**

This project really came together quickly and was perhaps the catalyst for follow on work. I imagine that the gherkin files or whatever might most effectively superscede that format can be used to generate requirements and then iterate back both from requirements to implementation and then backwards until they are both in harmony. The requirements can then also be analyzed separately.

**Links**

- Blog Article: [https://echozulu.hashnode.dev/behavior-pad-gherkin-editor](https://echozulu.hashnode.dev/behavior-pad-gherkin-editor)
- Github: [https://github.com/echozulucode/behavior-pad](https://github.com/echozulucode/behavior-pad)

## LCARS React Test

**LCARS React** is a React component library that recreates authentic Star Trek LCARS (Library Computer Access/Retrieval System) interfaces.

If you’re not familiar, LCARS (Library Computer Access and Retrieval System) is the fictional computer operating system and user interface used by Starfleet in the 24th century of the Star Trek universe, notably in The Next Generation, Deep Space Nine, and Voyager.

- **Active Development Period** : October 15-19, 2025
- **Lines of Code** : ~8,500+ lines
- **Status** : Initial Demo Only

![](./images/b9cfc88f-b5a5-4f37-8ac5-58002d7a7278.png align="center")

![](./images/050600f9-069b-448c-94b2-fdf415d68f84.png align="center")

**Technology Stack:**

- React 19.1.1 with TypeScript
- Vite 7.1.7 build system
- CSS Modules for scoped styling

**AI Generation Notes:**

Regardless of pictures, prompts, context and plans, I couldn’t get AI to design something from scratch that resembled LCARS. It wasn’t until I provided the following source code as reference ([https://www.thelcars.com/download.php](https://www.thelcars.com/download.php)) that it became productive. We also spin looped for a while getting the elements to scale properly as screen size changed. However, once we got the basics, it was able to apply the style to new, unrelated screen types within the plan fast and without issue.

**Links**

- **Github:** [https://github.com/echozulucode/lcars-react](https://github.com/echozulucode/lcars-react)

## Ludicrous Game Engine

**Ludicrous Engine** is a modern, high-performance 2D/3D game engine built in Rust, designed for AI-assisted development with sub-second hot-reload capabilities. The project demonstrates rapid, quality-driven development using an MVP-based approach.

**Overview**

- **Active Development Period**: October 12 - 31, 2025
- Project status: 57% complete (3.4 of 6 phases)
- 34 days of development across 3 completed phases
- Phase 1: Foundation and Core Systems: Oct 12 - 20, 2025
- Phase 2: Game Development Features: Oct 19 - 26, 2025
- Phase 3: Initial Tooling and Developer Experience: October 26 - 31, 2025

**Key Metrics Featured**

- 0.32s hot-reload (6x better than target)
- 97+ tests passing
- 15,000+ lines of Rust code
- 17+ working examples

**AI Generation Notes:**

I wanted to see how well this approach scaled, so thought I’d try to go huge. This is still a work in progress, but it was really interesting to see AI planned small throw-away prototypes for evaluating topics, such as user input, animation, audio, etc.

_side-note_: I am not planning to open-source this one just in case.

**Space Defender:** First 2D AI generated game for the engine

![](./images/716e24c8-913c-4834-9565-0b0056034ccf.png align="center")

_Example small derisk demos_

![](./images/0833eda1-ea26-4b37-8a55-020aef228a0a.gif align="center")

![](./images/759fad2f-3235-4a6b-a64a-1fbefddc687e.gif align="center")

## SimBlocks - ReactFlow Test

SimBlocks is a **real-time block diagram simulator** with a professional visual editor, designed for control systems engineering, signal processing, and educational applications. Built as a native desktop application using Rust (backend) and React/TypeScript (frontend) with the Tauri framework.

- **Active Development Period**: October 24-26, 2025 (3 days)
- **Lines of Code**: ~4,150 lines (Rust: 2,506, TypeScript: 1,638, plus documentation)
- **Status**: Visual editor demo complete

![](./images/470a4660-9721-4617-bd52-a9583c7bb39a.png align="center")

**Key Features**:

- Real-time simulation engine (1 kHz fixed-step execution)
- Visual block diagram editor with drag-and-drop interface
- 13 simulation blocks across 5 categories (Sources, Math, Timing, Sinks, Plant)
- Multi-trace oscilloscope with live data visualization
- Deterministic execution with seeded PRNG for reproducibility
- Parameter editor with live updates during simulation
- Project save/load with JSON format
- CSV data export for analysis
- Undo/Redo with 50-level history
- Auto-save with crash recovery
- Comprehensive graph validation (cycle detection, type checking)

**Technology Stack**:

- **Backend**: Rust, Tauri, petgraph, crossbeam, serde
- **Frontend**: React, TypeScript, Vite, React Flow, uPlot, Zustand
- **Testing**: Playwright (E2E), Rust unit tests
- **Build System**: Cargo (Rust), npm (TypeScript)
- **Deployment**: Native Windows/macOS/Linux executables

**Links**

- **Github:** [https://github.com/echozulucode/unpdf](https://github.com/echozulucode/unpdf)

## FastAPI Intranet Application Template

The FastAPI Intranet Application is a full-stack intranet web application template designed with enterprise features.

- **Active Development Period**: October 30 - November 1, 2025
- **Lines of Code**: ~32,400 lines (total across code, tests, documentation, and BDD features)
- **Status**: Core functionality complete, CI/CD and production deployment pending

![](./images/089c3dda-3abe-4d22-97cf-d86799487cac.png align="center")

![](./images/52c052c5-3925-4556-a886-21dba21d2538.png align="center")

**Key Features**:

- Robust Authentication (JWT, LDAP/Active Directory with fallback)
- User Management (Admin CRUD, profile management)
- Personal Access Tokens (PATs) with scopes and expiration
- Role-Based Access Control (RBAC)
- Modern, responsive UI/UX

**Technology Stack**:

- **Backend**: FastAPI (Python), SQLModel, Argon2
- **Frontend**: React, TypeScript, Vite
- **Deployment**: Docker/Podman compatible containers

**Links**

- **Blog Article:** [https://echozulu.hashnode.dev/from-vibe-to-verified-building-production-software-with-ai](https://echozulu.hashnode.dev/from-vibe-to-verified-building-production-software-with-ai)
- **Github:** [https://github.com/echozulucode/fastapi-demo](https://github.com/echozulucode/fastapi-demo)

## unpdf

The simple, transparent, MIT‑licensed PDF→Markdown converter for developers who value speed, predictability, and explainability over handling every edge case.

This was created when I encountered some CLI agents were unable to read PDFs directly. I found that Pandoc didn’t support this and attempted conversion with some python packages but with significant issues for a large PDF. This project was started to attempt to build an open-source converter. Investigating further, I found that PDF to markdown is not a trivial operation. We’ve worked through a fair number of issues and are using new approaches, but still not quite there.

- Active Development Period: Nov 2, 2025 - Nov 8, 2025
- Status: In progress (numerous working test cases)
- Objectives: &lt;0.5s/page typical; &lt;10 dependencies; clear, testable pipeline
- License: MIT only (no AGPL/ML/GPU)

![](./images/0fa06b64-71f9-4694-a005-896f9e77d8ca.webp align="center")

Key Features

- Rule‑based pipeline (Extract → Process → Render), no ML
- Text + formatting (bold, italic)
- Structure: headings, lists, blockquotes
- Code detection: inline and fenced blocks
- Tables: pipe‑table rendering with graceful fallback
- Media & Links: image extraction, hyperlink preservation
- CLI: single file/dir, helpful flags and errors
- Transparency: DEBUG logging of detection decisions

Technology Stack

- Python 3.10+, `pdfplumber` (core); optional Camelot if justified
- CLI via `argparse`; packaging with `pyproject.toml`
- Tooling: Black (88), type hints, pytest
- Serverless/CI friendly; no ML/GPU dependencies

Performance & Quality Targets

- Install &lt;10s; cold start &lt;1s; processing &lt;0.5s/page; &lt;50MB/page
- > 80% test coverage; &gt;95% match on round‑trip for target docs

**Links**

- **Github:** [https://github.com/echozulucode/unpdf](https://github.com/echozulucode/unpdf)

## **Core Abstract Principles for Using AI Effectively**

### **1\. Treat AI as a Skilled Assistant, Not a Replacement**

AI is not magic; it is a **capable junior contributor**. It works best when **given direction, constraints, patterns, and review**.

> **Human sets strategy → AI executes → Human verifies.**

This principle applies to writing, research, design, planning, scientific work, operations—everywhere.

---

### **2\. Start With a Clear Plan Before Using AI**

Do **not** begin by asking AI to “do the task.” First, ask it to help create:

- A structured plan
- Deliverables
- Success criteria
- Dependencies and phase breakdowns

This converts AI from being a **reactive tool** into a **process amplifier**.

---

### **3\. Work Iteratively With Continuous Verification**

Never assume AI output is correct.

- Produce small increments
- Test or verify each increment
- Revise before proceeding

**Verification is the control system** that prevents compounding errors.

In any discipline, this can mean:

- Checking citations
- Running experiments
- Peer review
- Cross-reference against known constraints

---

### **4\. Establish Patterns Early and Reuse Them**

AI is strongest when following a **consistent structure**.

Define reusable patterns first:

- Writing styles
- Data report formats
- Design templates
- Analysis methods
- Presentation frameworks

Then ask AI to **extend the pattern**.

Pattern first → Consistency later.

---

### **5\. Generate Documentation and Explanation Continuously**

Don’t “document later.” Have AI:

- Summarize reasoning
- Produce guides
- Capture decisions
- Explain workflows

This builds **living documentation** that evolves with work rather than trailing it.

Useful in:

- Research (lab notes)
- Policy development
- Project planning
- Curriculum design
- Manufacturing process work

---

### **6\. Use AI to Create Verification and Traceability Artifacts**

AI can help generate:

- Test checklists
- Evaluation criteria
- Audit trails
- Rationale documentation
- Traceability between goals, decisions, and results

This supports:

- Compliance
- Long-term maintenance
- Onboarding others
- Institutional knowledge retention

---

### **7\. Reverse-Engineer Work Into Formal Descriptions**

When a working system (or idea) exists, ask AI to extract:

- Behavior descriptions
- Requirements
- Rationale
- Best practices
- Training material

This enables:

- Retrospective clarity
- Transfer of knowledge
- Reuse in future projects

---

### **8\. Discipline Determines Output Quality**

AI **amplifies your process**.

- A **sloppy workflow** → sloppy results faster.
- A **rigorous workflow** → rigorous results faster.

The difference is not the AI model — **it’s the method you apply to it.**

---

## **The Meta-Principle**

### **AI accelerates whatever exists.**

If you bring:

| Human Input                    | AI Output Result               |
| ------------------------------ | ------------------------------ |
| Chaos                          | Faster chaos                   |
| Clear structure                | Faster structured productivity |
| Good judgment and verification | Higher-quality results         |

So the focus should be on **process quality, not AI intelligence.**
