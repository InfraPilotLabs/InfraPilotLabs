# InfraPilotLabs

**LLM Training Data Services**

We clean, format and validate datasets for LLM fine-tuning.  
Raw data in → clean `train.jsonl` out. Every job includes a quality report.

---

## What We Do

| Service | Details |
|---|---|
| Format Conversion | CSV / JSON / PDF → Alpaca, ShareGPT, ChatML JSONL |
| Deep Cleaning | HTML removal, deduplication, encoding fixes, length filtering |
| PII Anonymization | Patient names, emails, phone numbers, SSNs detected and removed |
| Multilingual Data | Tamil · Hindi · French — Tamil outputs natively verified |
| Dataset Audit | Quality report on your existing dataset before you train |
| PDF → Dataset | Extract text, generate Q&A pairs, format for fine-tuning |

---

## Portfolio

| Project | Dataset | Raw | Clean | Format |
|---|---|---|---|---|
| [alpaca-dataset-cleaning-pipeline](https://github.com/InfraPilotLabs/alpaca-dataset-cleaning-pipeline) | yahma/alpaca-cleaned | 51,760 | 50,350 | Alpaca JSONL |
| [squad-qa-dataset-pipeline](https://github.com/InfraPilotLabs/squad-qa-dataset-pipeline) | rajpurkar/squad | 87,599 | 85,467 | Alpaca JSONL + Context |
| [oasst-sharegpt-pipeline](https://github.com/InfraPilotLabs/oasst-sharegpt-pipeline) | OpenAssistant/oasst1 | 84,437 msgs | 8,519 pairs | ShareGPT JSONL |
| [medical-qa-dataset-pipeline](https://github.com/InfraPilotLabs/medical-qa-dataset-pipeline) | medalpaca/medical_meadow_medqa | 10,178 | 9,837 | Alpaca JSONL |
| [multilingual-dataset-pipeline](https://github.com/InfraPilotLabs/multilingual-dataset-pipeline) | Helsinki-NLP/opus-100 | 1,761,333 | 1,269,661 | Alpaca JSONL |

---

## Free Tool

**[Dataset Benchmark](https://dataset-benchmark.vercel.app)** — Upload your CSV and get an instant quality score.  
No login. No data storage. No AI. Fully deterministic. Free.

---

## Framework Compatibility

Every dataset we deliver works out of the box with:

```
Axolotl · LLaMA Factory · Unsloth · HuggingFace TRL
```

---

## Start a Project

**Email:** contact@infrapilotlabs.com  
**Website:** [infrapilotlabs.github.io](https://infrapilotlabs.github.io)

Custom quote based on your data size and complexity. Reply within 24 hours.
