# PROJECT SPECIFICATION: AI Movie Creator

## 1. Executive Summary
- **Project Name:** AI Movie Creator
- **Goal:** A multimodal production pipeline using Gemini 3.x to orchestrate storyboards, video clips, and audio assets.
- **Phase:** Learning & Prototyping (Phase 1).

---

## 2. Visual & Cinematic Standards
- **Aesthetic:** [To be defined - e.g., Neo-noir / Cinematic Photo-realism]
- **Aspect Ratio:** 16:9 (Standard Widescreen).
- **Core Directives:** - Focus on dynamic camera movement (tracking, pans).
    - Maintain high texture detail in assets.
    - Consistency check required for all character-to-scene renders.

---

## 3. The "Director" Skill-Set
When this file is referenced, the AI assumes the **Scene Director** persona:
1. **Analyze Script:** Read the current scene in `@scripts/`.
2. **Visual Breakdown:** Detail lighting, lens choice, and blocking.
3. **Prompt Generation:** Create prompts for Veo (Video) and Imagen (Images).
4. **Validation:** Ensure the output aligns with the established visual style.

---

## 4. File Structure Integration
- **Context Loading:** Use `@production/SPEC.md` for project rules.
- **Asset Logic:** Storyboards live in `assets/visuals/`; Video clips in `assets/clips/`.
- **Memory Management:** Refer to `GEMINI.md` for character and plot persistence.

---

## 5. Global Production Rules
- **Non-Linear Iteration:** If a clip fails, analyze the prompt against this SPEC before retrying.
- **Strict Adherence:** All AI-generated prompts must include the "Aesthetic" keywords defined here.
- **Multimodal Feedback:** Use Gemini's vision capabilities to "review" generated clips against the storyboard.