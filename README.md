# dvpo

**Table 2. Performance under the Instruction Setting**

*Mistral 7B refers to* **Mistral-7B-instruction-v0.2**, *and Llama 8B refers to* **Llama3-8B-instruction**.  
*DVPO performs best among the preference alignment methods.*

| Model      | MtBench | Arena Hard | AlpacaEval2 |
|------------|---------|------------|-------------|
| Mistral 7B | 6.60    | 12.69      | 21.90       |
| ReMaX      | 6.67    | 21.90      | 20.55       |
| DRO        | 6.30    | 16.30      | 26.29       |
| GRPO       | 6.31    | 21.80      | 27.19       |
| PPO        | 6.55    | 19.40      | 19.40       |
| DVPO       | 6.79    | 24.70      | 27.43       |
| Llama 8B   | 6.90    | 20.60      | 22.92       |
| GPT4       | 7.93    | 35.50      | 30.20       |
