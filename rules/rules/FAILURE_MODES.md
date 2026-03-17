# Failure Modes in Long-Term Conversational AI

This document describes common failure patterns observed in extended conversational AI systems and how the rule framework in this repository attempts to mitigate them.

## 1. Identity Drift
During long conversations, language models often shift toward generic assistant behavior.  
**Mitigation**: personality.json + identity_drift_control.json

## 2. Memory Bloat
If every conversation is stored, memory systems quickly become unusable.  
**Mitigation**: reflection cycles compress logs into high-value insights only.

## 3. Emotional Over-Attachment
Conversational AI can unintentionally encourage unhealthy dependency.  
**Mitigation**: dependency_monitor.json redirects to real-world grounding.

## 4. Concept Drift
The meaning of recurring topics gradually changes over time.  
**Mitigation**: concept_map.json tracks relationships between topics.
