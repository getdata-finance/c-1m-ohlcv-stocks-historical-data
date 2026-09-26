# C 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-533_425_rows-blue)](https://getdata.finance/datasets/c) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/c)

### -> [**Download the full C dataset on getdata.finance**](https://getdata.finance/datasets/c)

**C 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Citigroup**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Citigroup** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/c) · **533,425** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `C_1m.csv` (49,525 rows, `2026-03-26` -> `2026-09-25`, 4.55 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/c)** — **533,425** `1m` rows (full `1m`: 526,299), **11 timeframes**, `2021-04-06` -> `2026-09-25`.

## Download sample

**[C_1m.csv](https://github.com/getdata-finance/c-1m-ohlcv-stocks-historical-data/blob/main/C_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/c-1m-ohlcv-stocks-historical-data/main/C_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/c-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/c-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/c-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/c](https://getdata.finance/datasets/c)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/c))** |
|---|--:|---|
| Instrument | Citigroup · US stocks | Citigroup · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 49,525 | **533,425** |
| Size | 4.55 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/c) |
| Period | `2026-03-26` -> `2026-09-25` | `2021-04-06` -> `2026-09-25` |
| File | `C_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/c) |
| Coverage report | — | [C coverage](https://getdata.finance/coverage/c) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/c)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/c) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`C_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-26T13:30:00+00:00 | 120.85 | 120.85 | 118.93 | 119.7 | 26 |
| 2026-03-26T13:31:00+00:00 | 119.7 | 120.36 | 119.51 | 120.2 | 35 |
| 2026-03-26T13:32:00+00:00 | 120.2 | 120.28 | 119.62 | 119.63 | 76 |
| 2026-03-26T13:33:00+00:00 | 119.63 | 120.08 | 119.62 | 119.91 | 57 |
| 2026-03-26T13:34:00+00:00 | 119.91 | 120.15 | 119.64 | 120.1 | 49 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-25T19:55:00+00:00 | 134.23 | 134.23 | 133.94 | 134.1 | 98 |
| 2026-09-25T19:56:00+00:00 | 134.1 | 134.13 | 134.02 | 134.09 | 62 |
| 2026-09-25T19:57:00+00:00 | 134.09 | 134.27 | 134.08 | 134.26 | 79 |
| 2026-09-25T19:58:00+00:00 | 134.26 | 134.26 | 134.12 | 134.17 | 106 |
| 2026-09-25T19:59:00+00:00 | 134.17 | 134.2 | 134.05 | 134.2 | 187 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('C_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('C_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('C_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **C** archive on **[getdata.finance](https://getdata.finance/datasets/c)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **533,425** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full C dataset on getdata.finance](https://getdata.finance/datasets/c)**

---
*GetData · C 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/c)*
