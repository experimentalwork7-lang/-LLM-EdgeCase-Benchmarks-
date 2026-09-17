### Model Comparison Matrix

| Evaluation Metric | Gemini 1.5 Flash | GPT-5.6 Luna |
| :--- | :--- | :--- |
| **Constraint Override Adherence** | Passed (17-minute solution) | Passed (17-minute solution) |
| **Negative Constraint Check** | Verified A and D never crossed together | Explicit `rule_1_verification` audit sub-schema |
| **State Tracking** | Basic step breakdown | Full state-machine tracking (`start_side`, `far_side`, `lantern_side`) |
| **Raw JSON Adherence** | 100% clean output | 100% clean output with granular cumulative timing |
