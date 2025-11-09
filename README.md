# Task1_result
| Model | Method | Pearson | CCC | MAE |
| :--- | :--- | :--- | :--- | :--- |
| Roberta-base | Fine-tuning | 0.583728 | 0.562603 | 0.648800 |
| Roberta-large | Untlosh lora | 0.592782 | 0.571307 | 0.667617 |
| Deberta-base | Untlosh lora | 0.564427 | 0.524096 | 0.647092 |
| Deberta-large | Untlosh lora | 0.543551 | 0.495595 | 0.674155 |
| Roberta-large | SIMCSE + prompt tuning | 0.6009 | 0.5731 | 0.6413 |
| Deberta-large | SIMCSE+prompt tuning | 0.5797 | 0.5644 | 0.650423 |

Pearson = (Pearson A + Pearson V)/2  
CCC = (CCC A + CCC V)/2  
MAE = (MAE A + MAE V)/2
