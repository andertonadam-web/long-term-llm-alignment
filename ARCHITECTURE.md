# System Architecture

Four-layer design for stable long-term conversation:

1. Conversation Layer  
   User messages → local LLM + rule modules (personality, boundaries, emotion tags).

2. Reflection Cycle  
   Nightly: summarize chat → tag emotion → extract insights.

3. Core Memory  
   Store only high-value stuff—no bloat.

4. Identity Drift Control  
   Weekly checks + dependency rules to keep behavior consistent and safe.
