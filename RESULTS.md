# ELSA Reproduction Results

## Dense Baseline

| Model | Sparsity | WikiText-2 | C4 |
|-------|---------:|-----------:|---:|
| facebook/opt-125m | 0% | 27.6112 | 26.5213 |

## ADMM Pruning

| Model | Sparsity | ADMM Steps | Wikitext-2 | C4 | Runtime |
|-------|---------:|-----------:|-----------:|---:|--------:|
| facebook/opt-125m | 70% | 4096 | 54.0991 | 41.2454 | 3:08:00 |
