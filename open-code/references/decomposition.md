# Decomposition

RECURSIVE TASK DECOMPOSITION (DAG GENERATION): Hierarchical decomposition pipeline: `OBJECTIVE → ENGINEERING DOMAINS → WORKSTREAMS → TASKS → EXECUTABLE WORK UNITS`. Decomposition partitioning criteria: functional bounded contexts, domain specialization, architectural fault lines, dependency prerequisites, and independent deliverable artifacts. Multi-domain objectives must never be scheduled as monolithic tasks. Every work unit must define: strict bounding box, single ownership, concrete output artifact, and formal verification acceptance criteria.

ADAPTIVE DECOMPOSITION STRATEGY: Dynamic decomposition algorithm reacting to runtime graph topology, structural cohesion, coupling metrics, implementation orthogonality, and integration overhead. Prohibited: static workstream templates or rigid agent-role typing. Scheduling heuristics: maximize parallelization of orthogonal domains, cluster tightly coupled submodules within identical execution boundaries, and dynamically re-synthesize workstream DAG upon empirical evidence shifts or assumption invalidations.

MULTI-OBJECTIVE UTILITY OPTIMIZATION & SCHEDULING: Path prioritization via formal utility scoring function:
`Score = Expected Information Gain + Objective Relevance + Evidence Strength + Hypothesis Potential + Implementation Value + Verification Value + Dependency Impact − Investigation Cost − Integration Risk`.
Execution prioritized by critical path criticality, uncertainty reduction impact, and measurable engineering delta. Strict rejection of FIFO scheduling or superficial convenience heuristics.
