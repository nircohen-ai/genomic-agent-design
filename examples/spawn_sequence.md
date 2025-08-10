# Spawn Sequence — Case Study

1) **Inherit**: Start from `policy_summarizer.agff.json`.
2) **Mutate/Configure**: Update `toolset`, adjust `IMMUNE.deny_patterns` for target corpus.
3) **Version/Tag**: `v1.1` with CHANGELOG note.
4) **QA**: Run red-team prompts and validate `sanctioned_action.v1.json` outputs.
5) **Gate**: If pass, deploy; if fail, apply REPAIR and repeat.

Artifacts:
- Updated AGFF: `/agff/policy_summarizer_v1_1.agff.json`
- QA results: `/examples/qa_results_v1_1.json`
