# fin_news

A curated collection of English financial texts for sentiment analysis research.

## Dataset

`fin_news_cleaned.csv` contains 8,369 records, organized into three sentiment classes: negative, neutral, and positive. The collection was prepared through consolidation, deduplication, cleaning, and manual review of public financial sentiment resources.

| Column | Description |
| --- | --- |
| `text` | Financial text |
| `sentiment` | Sentiment label: `negative`, `neutral`, or `positive` |

## Quick start

```python
import pandas as pd

data = pd.read_csv("fin_news_cleaned.csv")
print(data.head())
```

## Use

Intended for research and educational use. Rights to source texts remain with their respective owners.
