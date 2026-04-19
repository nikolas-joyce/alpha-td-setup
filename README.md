# alpha-td-setup

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/nikolas-joyce/alpha-td-setup/blob/main/notebooks/alpha_td_setup.ipynb)

> TD Sequential Setup (9-bar) alpha signal — backtest + parameter sweep

> DeMark's 9-bar setup identifies exhaustion: nine consecutive closes each below the close four bars earlier. When the count completes the market has moved too far too fast and a reversal is probable.

## Notebook structure
| Section | Description |
|---------|-------------|
| 0 | Install & imports |
| 1 | Config & data |
| 2 | Helper functions |
| 3 | TD Sequential engine |
| 4 | V1 signal generation — conventional & contrarian polarity |
| 5 | Returns & performance |
| 6 | Per-ticker breakdown |
| 7 | Parameter sensitivity (setup count 7–11) |
| 8 | Representative equity curves |
| 9 | Export signals for td-swarm |

**Run all cells top-to-bottom in a fresh Colab runtime.**

