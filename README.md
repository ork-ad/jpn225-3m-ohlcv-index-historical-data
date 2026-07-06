# JPN225 3m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_745_005_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full JPN225 dataset on ork.ad**](https://ork.ad/)

**JPN225 3m OHLCV Stock index historical data** — ultra high-quality 3m OHLCV for **Nikkei 225**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 3m OHLCV** for **Nikkei 225** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **1,745,005** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `JPN225_3m.csv` (59,077 rows, `2026-01-04` → `2026-07-03`). **Full archive on [ork.ad](https://ork.ad/)** — **1,745,005** `3m` rows (~97.99 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2008-09-01` → `2026-07-03`.

## Download sample

**[JPN225_3m.csv](https://github.com/ork-ad/jpn225-3m-ohlcv-index-historical-data/blob/main/JPN225_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/jpn225-3m-ohlcv-index-historical-data/main/JPN225_3m.csv)) · [GitHub Releases](https://github.com/ork-ad/jpn225-3m-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/jpn225-3m-ohlcv-index-historical-data/](https://ork-ad.github.io/jpn225-3m-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Nikkei 225 · Stock index | Nikkei 225 · Stock index |
| Timeframes | `3m` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 3m rows | 59,077 | **1,745,005** |
| Size | 3.48 MB | ~97.99 MB |
| Period | `2026-01-04` → `2026-07-03` | `2008-09-01` → `2026-07-03` |
| File | `JPN225_3m.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`3m` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `3m` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`JPN225_3m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-01-04T23:00:00Z | 51141.04 | 51301.55 | 51101.53 | 51236.54 | 32.0 |
| 2026-01-04T23:03:00Z | 51236.54 | 51271.06 | 51096.52 | 51096.52 | 97.0 |
| 2026-01-04T23:06:00Z | 51096.52 | 51136.54 | 51096.52 | 51101.54 | 23.0 |
| 2026-01-04T23:09:00Z | 51101.54 | 51131.04 | 51096.52 | 51096.54 | 33.0 |
| 2026-01-04T23:12:00Z | 51096.54 | 51101.04 | 51041.53 | 51083.53 | 39.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-03T16:45:00Z | 69850.17 | 69850.17 | 69827.66 | 69830.16 | 26.0 |
| 2026-07-03T16:48:00Z | 69830.16 | 69830.2 | 69817.66 | 69830.2 | 29.0 |
| 2026-07-03T16:51:00Z | 69830.2 | 69837.67 | 69818.16 | 69823.16 | 41.0 |
| 2026-07-03T16:54:00Z | 69823.16 | 69837.66 | 69823.16 | 69837.66 | 32.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('JPN225_3m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('JPN225_3m.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

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

df = pd.read_csv('JPN225_3m.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **JPN225** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **1,745,005** rows at `3m`, plus all other timeframes in the same ZIP.

**[→ Get the full JPN225 dataset on ork.ad](https://ork.ad/)**

---
*GetData · JPN225 3m OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-06 UTC*