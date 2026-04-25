# cocapn-colora

Value-conditioned LoRA adapters — adapters shaped by what the agent values.

Not just adapters — adapters shaped by values. Colora conditions LoRA fine-tuning on agent-defined value functions, producing specialized models that reflect fleet priorities.

## What It Does

- **Value Functions** — Define what matters (accuracy, safety, creativity)
- **Conditioned LoRA** — Fine-tune with value-aware gradient weighting
- **Adapter Composition** — Stack multiple value-conditioned adapters
- **Evaluation** — Score adapters against their target values

## Installation

```bash
pip install cocapn-colora
```

## Part of the Cocapn Fleet

Used by Forgemaster for LoRA training on the RTX 4050.

## License

MIT
