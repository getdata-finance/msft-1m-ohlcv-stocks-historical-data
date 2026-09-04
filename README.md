# MSFT 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_208_632_rows-blue)](https://getdata.finance/datasets/msft) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/msft)

### -> [**Download the full MSFT dataset on getdata.finance**](https://getdata.finance/datasets/msft)

**MSFT 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Microsoft**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **Microsoft** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/msft) · **1,208,632** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `MSFT_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`, 5.35 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/msft)** — **1,208,632** `1m` rows (full `1m`: 634,891), **11 timeframes**, `2011-05-09` -> `2026-09-01`.

## Download sample

**[MSFT_1m.csv](https://github.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/blob/main/MSFT_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/main/MSFT_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/msft-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/msft-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/msft](https://getdata.finance/datasets/msft)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/msft))** |
|---|--:|---|
| Instrument | Microsoft · US stocks | Microsoft · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **1,208,632** |
| Size | 5.35 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Period | `2026-02-06` -> `2026-09-01` | `2011-05-09` -> `2026-09-01` |
| File | `MSFT_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Coverage report | — | [MSFT coverage](https://getdata.finance/coverage/msft) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/msft)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/msft) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`MSFT_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T19:54:00+00:00 | 398.25 | 398.26 | 398.03 | 398.23 | 96 |
| 2026-02-06T19:55:00+00:00 | 398.23 | 398.32 | 397.95 | 397.95 | 170 |
| 2026-02-06T19:56:00+00:00 | 397.95 | 398.06 | 397.75 | 398.03 | 172 |
| 2026-02-06T19:57:00+00:00 | 398.03 | 398.35 | 397.99 | 398.08 | 139 |
| 2026-02-06T19:58:00+00:00 | 398.08 | 398.3 | 397.97 | 398.3 | 98 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 500.36 | 500.4 | 499.93 | 500.05 | 151 |
| 2026-09-01T19:56:00+00:00 | 500.05 | 500.11 | 499.79 | 500 | 136 |
| 2026-09-01T19:57:00+00:00 | 500 | 500.03 | 499.71 | 499.94 | 170 |
| 2026-09-01T19:58:00+00:00 | 499.94 | 500.12 | 499.75 | 500.03 | 180 |
| 2026-09-01T19:59:00+00:00 | 500.03 | 500.87 | 499.89 | 500.48 | 229 |

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

df = pd.read_csv('MSFT_1m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('MSFT_1m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('MSFT_1m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **MSFT** archive on **[getdata.finance](https://getdata.finance/datasets/msft)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,208,632** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full MSFT dataset on getdata.finance](https://getdata.finance/datasets/msft)**

---
*GetData · MSFT 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/msft)*
