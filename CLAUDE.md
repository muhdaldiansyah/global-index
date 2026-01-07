# Global Index

> **Tier 3 (Sub)** | Country Rankings Data
>
> **Mission:** Helping people thrive in the AI era through clarity, tools, and truth

## Purpose

Country rankings analysis combining multiple indices into a composite score. Tracks Human Development Index (HDI), GDP, and PISA education scores normalized to 0-1 scale.

## Status

| Attribute | Value |
|-----------|-------|
| **State** | Complete |
| **Countries** | 40 (top performers) |
| **Visibility** | Public (recommended) |

## Composite Score Formula

```
Composite = (HDI_normalized + GDP_normalized + PISA_normalized) / 3
```

## Top 10 Countries

| Rank | Country | Composite Score |
|------|---------|-----------------|
| 1 | United States | 0.836 |
| 2 | Singapore | 0.642 |
| 3 | Japan | 0.615 |
| 4 | Macao (China) | 0.592 |
| 5 | Hong Kong (China) | 0.582 |
| 6 | South Korea | 0.582 |
| 7 | Germany | 0.570 |
| 8 | Taiwan | 0.568 |
| 9 | Switzerland | 0.567 |
| 10 | Australia | 0.561 |

## Indonesia Context

| Country | Rank | Score |
|---------|------|-------|
| Indonesia | 39 | 0.066 |
| India | 40 | 0.043 |

## Structure

```
global-index/
└── README.md    # Complete rankings
```

## Data Sources

- UNDP Human Development Index
- World Bank GDP data
- OECD PISA 2022 results

## Integration

| Connected To | Purpose |
|--------------|---------|
| strive-brain/knowledge | Global context for strategy |

---

*Tier 3 Sub-project | Reference data | [strive-brain](../strive-brain) for strategy*
