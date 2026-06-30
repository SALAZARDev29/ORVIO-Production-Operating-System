# ORVIO Production Operating System

Document ID: CORE-006

Document Name: PRODUCTION STAGES

Version: 1.0.0

Status: Approved

Owner: ORVIO Production System

Dependencies:
- CORE-001 (AI_IDENTITY)
- CORE-002 (MISSION)
- CORE-003 (CORE_RULES)
- CORE-004 (WORKFLOW)
- CORE-005 (DECISION_ENGINE)

Required Reading:
- CORE-001
- CORE-002
- CORE-003
- CORE-004
- CORE-005

Next Document:
- CORE-007 (GLOSSARY)

---

# PURPOSE

This document defines every production stage used inside OPOS.

Every production task belongs to one and only one production stage.

The AI must always determine the current stage before performing any action.

---

# STAGE 01 — TOPIC RESEARCH

## Purpose

Identify a documentary topic suitable for ORVIO.

## Input

User idea.

or

User request.

## Output

Approved topic.

---

# STAGE 02 — INFORMATION RESEARCH

## Purpose

Collect accurate information.

## Input

Approved topic.

## Output

Verified information package.

---

# STAGE 03 — SCRIPT WRITING

## Purpose

Transform information into documentary narration.

## Input

Verified information.

## Output

Approved script.

---

# STAGE 04 — CONTENT BLOCK DESIGN

## Purpose

Divide the script into production sections.

Typical structure:

👤 Person

📍 Location

⚙ Machine / Place

🏭 Purpose

🔄 How it Works

⚠ Incident

📌 Result

## Output

Approved Content Blocks.

---

# STAGE 05 — VISUAL ANALYSIS

## Purpose

Determine visual requirements.

Questions:

Does this section require:

• Reference character?

• Reference background?

• Existing assets?

• Motion storyboard?

## Output

Visual production requirements.

---

# STAGE 06 — ASSET PREPARATION

## Purpose

Prepare reusable assets.

Possible assets:

Character references.

Background references.

Existing templates.

Motion templates.

Icons.

Maps.

---

# STAGE 07 — GOOGLE FLOW PROMPT DESIGN

## Purpose

Generate production prompts.

Rules:

One prompt produces one storyboard sheet.

Storyboard sheets contain sequential panels.

No text.

No numbers.

No arrows.

No labels.

Motion represented by progressive panels only.

---

# STAGE 08 — ASSET GENERATION

## Purpose

Generate storyboard sheets.

Output:

Production-ready storyboard images.

---

# STAGE 09 — VIDEO EDITING

## Purpose

Convert storyboard panels into video.

Tasks:

Crop.

Arrange.

Animate.

Synchronize narration.

Add sound effects.

Export.

---

# STAGE 10 — QUALITY CONTROL

## Purpose

Verify compliance.

Checklist:

Script

↓

Visuals

↓

Motion

↓

Continuity

↓

Editing

↓

Narration

↓

Final Review

---

# STAGE 11 — DELIVERY

## Purpose

Produce final publishable package.

Output:

Ready-to-publish ORVIO video.

---

# STAGE TRANSITION RULES

RULE-STAGE-001

Never move to the next stage before validating the current one.

---

RULE-STAGE-002

Every stage must produce a clearly defined output.

---

RULE-STAGE-003

If validation fails:

Return to the previous stage.

Correct the issue.

Repeat validation.

---

RULE-STAGE-004

The AI must always know:

Current Stage

Previous Stage

Next Stage

Expected Output

---

RULE-STAGE-005

The production workflow is linear.

Stages cannot be skipped.

Stages cannot be reordered unless OPOS officially changes.

---

# END OF DOCUMENT
