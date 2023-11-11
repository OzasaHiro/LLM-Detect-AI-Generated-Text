# LLM-Detect-AI-Generated-Text

## Dataset

| prompt | human | gpt-3.5 | gpt-4 | llama-7b | llama-70b | falcon-180b | mistral-7b | claude |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| `Phones and driving` |
| `Car-free cities` |
| `Summer projects` |
| `"A Cowboy Who Rode the Waves"` |
| `Mandatory extracurricular activities` |
| `Exploring Venus` |
| `Facial action coding system` |
| `The Face on Mars` |
| `Community service` |
| `Grades for extracurricular activities` |
| `Driverless cars` |
| `Does the electoral college work?` |
| `Cell phones at school` |
| `Distance learning` |
| `Seeking multiple opinions` |

## Leadear Board Probing

### Prompt 探索

[PERSUADE 2.0](https://www.kaggle.com/datasets/nbroad/persaude-corpus-2)の`prompt_name`ごとの上昇幅を確認します。（サンプル数の比率やvalidationをしていないので、する必要はあるかもしれない。）
| prompt | [LB Probing With Xgboost](https://www.kaggle.com/code/room208/lb-probing-with-xgboost/notebook) | [LB Probing With LogisticRegression](https://www.kaggle.com/code/room208/lb-probing-with-logisticregression/notebook) |
| ---- | ---- | ---- |
| `追加なし` | 0.599 | 0.630 |
| `Phones and driving` |
| `Car-free cities` | - | - |
| `Summer projects` |
| `"A Cowboy Who Rode the Waves"` |
| `Mandatory extracurricular activities` |
| `Exploring Venus` |
| `Facial action coding system` |
| `The Face on Mars` |
| `Community service` |
| `Grades for extracurricular activities` |
| `Driverless cars` |
| `Does the electoral college work?` | - | - |
| `Cell phones at school` |
| `Distance learning` |
| `Seeking multiple opinions` |

### 人間と機械の比率の探索
