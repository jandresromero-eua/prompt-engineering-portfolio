RAG Implementations: Protocol-Based Advisory Systems

Objective

Implementation of Retrieval-Augmented Generation (RAG) to ensure zero-hallucination responses based on official diplomatic and consular manuals.

1. Consular Protection Advisory System

Context: Vienna Convention on Consular Relations (1963).

Operational Workflow

Source Grounding: The system retrieves the exact article (e.g., Article 36) before generating a procedural response.

Verification Loop: The model compares the generated advice against the retrieved text to ensure 100% factual alignment.

Technical Implementation (Prompt Template)

Role: Consular Affairs Expert.
Context Provided: [Official Manual Text]
Task: Analyze the vulnerability of the national citizen based on the provided text.
Constraint: If the specific procedure is not detailed in the Context, respond: "INFORMATION NOT AVAILABLE IN OFFICIAL MANUAL".


2. Outcomes

Accuracy: 100% adherence to provided documentation.

Auditability: Every response includes a direct citation from the normative source.
