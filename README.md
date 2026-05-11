MOM Compliance Assistant

The Goal: Developed a specialized AI agent to help workers navigate MOM employment practices with 100% accuracy and zero hallucinations.

The Challenge:Standard AI often misrepresents legal nuances. This project "jails" the agent within official documentation to protect 12-hour shift workers from incorrect overtime (OT) info.

The Strategy:
  - Source Control: Restricted knowledge strictly to official MOM URLs.
  - Guardrails: Forced a hard-stop on irrelevant queries (e.g., food) to prevent guessing.
  - Logic: Engineered retrieval for complex 3-week averaging rules for shift work.

Results:
  - Strict Boundaries: Successfully refused all out-of-scope prompts.
  - Nuanced Accuracy: Corrected identifies OT triggers for 12-hour shifts.
  - Clarity: Capped responses at 120 words for professional readability.

