# dvpo

**Table 2. Performance under the Instruction Setting**

*Mistral 7B refers to* **Mistral-7B-instruction-v0.2**,   
*DVPO performs best among the preference alignment methods.*

| Model      | MtBench | Arena Hard | AlpacaEval2 |
|------------|---------|------------|-------------|
| Mistral 7B | 6.60    | 12.69      | 21.90       |
| ReMaX      | 6.67    | 21.90      | 20.55       |
| DRO        | 6.30    | 16.30      | 26.29       |
| GRPO       | 6.31    | 21.80      | 27.19       |
| PPO        | 6.55    | 19.40      | 19.62       |
| DVPO       | 6.79    | 24.70      | 27.43       |
| GPT4       | 7.93    | 35.50      | 30.20       |


**Table 5. Value Model Performance**  
Value model’s performance shows a positive correlation with model size.

| Metric     | Llama3 8B | Llama2 13B | Llama3 3B | Mistral 7B |
|------------|-----------|------------|-----------|------------|
| Mean Value | 68.05     | 70.55      | 63.61     | 64.51      |
| P1 Value   | 57.15     | 63.80      | 55.00     | 52.00      |
| P5 Value   | 60.24     | 65.90      | 57.15     | 59.36      |
| P10 Value  | 62.54     | 67.90      | 58.59     | 58.83      |
| P90 Value  | 66.23     | 69.10      | 63.21     | 61.95      |
| P95 Value  | 66.99     | 69.67      | 59.91     | 59.92      |
| P99 Value  | 66.30     | 74.65      | 56.99     | 59.94      |


**Table 6. Comparison of learning value models from reward data and preference data**

| Accuracy    | From Reward | From Preference |
|-------------|------------|-----------------|
| Mean Value  | 64.51       | 67.85           |
| P1 Value    | 56.02       | 58.60           |
| P5 Value    | 58.46       | 62.80           |
| P10 Value   | 59.83       | 63.95           |
| P90 Value   | 61.47       | 65.85           |
| P95 Value   | 60.30       | 65.80           |
| P99 Value   | 59.94       | 64.05           |
