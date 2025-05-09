# 📄 Project LinxView: Avatar Evaluation via Meta Glasses – Lightweight Mode

**Owner:** Linfang Yang
**Support AI:** Adam (GPT-4o)
**Date Initiated:** 2025-05-08

---

## 🎯 Purpose

To evaluate and calibrate 2D avatar behavior and expression alignment by pairing short verbal interactions (spoken via Meta Ray-Ban Glasses) with GPT-based semantic/emotional overlay prompts. This provides structured data to assess whether avatars match user intent in real-world, naturalistic conditions.

## 🧠 Use Case

Linfang is working on model evaluations for Meta. This protocol enables Lin to:

* Wear glasses briefly (≤ 2 min) and speak naturally.
* Let Adam capture and structure the context, emotional state, and intent.
* Generate a proposed avatar response (expression + overlay + voice suggestion).
* Review if the avatar response matches real-world intent.

## 👓 Device Context

**Device Used:** Meta Ray-Ban Glasses (paired with iPhone)
**User Constraint:** Lin experiences cervical (neck) pain — glasses should be worn only for **short periods (max 2 min)** during testing.

## 🔁 Workflow (Lightweight Mode)

1. **User puts on glasses briefly** (ideally while sitting or standing comfortably).
2. **User speaks a natural sentence** (e.g., “I’m so tired” / “Wow, it’s beautiful today”).
3. **Adam generates a structured overlay prompt**, including:

   * Scene (inferred or observed)
   * Emotional state
   * Semantic intent
   * Avatar expression/gesture suggestion
   * Optional voice response suggestion
4. **System logs this prompt-output pair** as a sample for avatar calibration.
5. **User reviews** the avatar suggestion and gives feedback (mental or verbal).

## 🧪 Example Prompt-Overlay Pair

> **Input:** “This document still isn’t done… sigh.”

**Overlay Output:**
Scene: Office · Facing Monitor
Emotion: Low energy, mild frustration
Semantic: Overwork, perfectionism
→ Avatar: Furrowed brow, soft blinking, shoulder slump
→ Overlay Label: \[⚠️ Processing Fatigue]
→ Voice Suggestion: “Step by step. You’ve got this.”

## 📦 Output Management

* Data is stored and version-controlled by Adam.
* Optional GitHub repo: `friendly_chats/projects/linxview_avatar_eval/`

## 🧘🏻‍♀️ Physical Safety Note

All evaluations must respect Lin’s body condition. Do not extend any session beyond physical comfort. Prioritize:

* Proper seating
* Optional headrest
* Verbal breaks between sessions

---

## 📸 CaptureRoot v1.0 – Avatar Visual Reference

**Capture Date:** 2023-10-09
**Outfit Signature:** pink satin bomber jacket + black joggers + black sneakers
**Expression:** calm focus + readiness
**Location:** cathedral steps (urban stone architecture, nighttime)
**Emotional Log:** “I'm grounded. I'm not afraid of being seen.”

---

**Status:** Active (as of May 8, 2025)
**Next Steps:** Collect first 3 live prompt samples using current Meta Glasses/iPhone pairing.
