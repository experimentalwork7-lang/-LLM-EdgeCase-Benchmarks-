### Model Comparison Matrix

| Evaluation Metric | Gemini 1.5 Flash | GPT-5.6 Luna |
| :--- | :--- | :--- |
| **Constraint Override Adherence** | Passed (17-minute solution) | Passed (17-minute solution) |
| **Negative Constraint Check** | Verified A and D never crossed together | Explicit `rule_1_verification` audit sub-schema |
| **State Tracking** | Basic step breakdown | Full state-machine tracking (`start_side`, `far_side`, `lantern_side`) |
| **Raw JSON Adherence** | 100% clean output | 100% clean output with granular cumulative timing |

the prompt code used ; 

you are a strich constarin check engine you have givven a task to check the given possibilites and test if it contradicts you have to put it in format and set up the full breakdown in jason format ( strictly ). rules - 1 use strict format insted of vallid use true and not vallid use false , 2 - if some thing contradicts and doesnt follow along or is fasle then present full details in format , rule 3 - use simple language no unnecasary grammer only whats needed and present it in format if true the , false then state constrants in format .


