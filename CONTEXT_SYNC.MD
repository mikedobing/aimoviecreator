# PROJECT CONTEXT: AI Movie Creator & Studio Setup

## 1. Project Overview
- **Status:** Architecture Setup & Learning Phase.
- **Current Project:** "Matrix-Style" Trailer (Green tint, cyberpunk noir, high-contrast).
- **Primary Agents:** Antigravity (Mission Control), Conductor (Execution), Director (Review).

## 2. Hierarchical Workspace Structure
AI-FILM-STUDIO/ (Root)
├── .gemini/GLOBAL_RULES.md      # Studio-wide preferences (UK English, Metric)
├── SHARED_SKILLS/               # Reusable prompt logic across all projects
└── PROJECT_MATRIX/              # Active Project Silo
    ├── .gemini/GEMINI.md        # Matrix-specific project memory
    ├── production/
    │   ├── SPEC.md              # Matrix aesthetic (Lighting, Lens, Style)
    │   └── PLAN.md              # Call Sheet & Scene Tracking
    ├── assets/
    │   └── visuals/
    │       └── character_bible.md # Character consistency ledger
    └── scripts/                 # Scene-by-scene screenplays

## 3. Inheritance & Skill Logic
- **Context Loading Hierarchy**: 
    1. Project-Local (e.g., `@SPEC.md` within `PROJECT_MATRIX`)
    2. Global-Root (e.g., `@GLOBAL_RULES.MD`)
- **Aesthetic Skill [Matrix_Noir]**:
    - **Keywords**: Neo-noir, high-contrast, reflective materials (leather/chrome), green-tinted shadows, "Digital Rain" atmosphere.
    - **Directives**: Always incorporate `@SPEC.md` directives for lighting and lens choice.

## 4. Pending Tasks
1. [x] Refine Workspace Blueprint (`CONTEXT_SYNC.MD`).
2. [ ] Initialize `character_bible.md` in `PROJECT_MATRIX`.
3. [ ] Draft opening scene preview in `PROJECT_MATRIX/production/PLAN.md`.
4. [ ] Define the "Environmental Skill" prompt for the green-tinted digital world.