# MSFT 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_196_180_rows-blue)](https://getdata.finance/datasets/msft) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/msft)

### -> [**Download the full MSFT dataset on getdata.finance**](https://getdata.finance/datasets/msft)

**MSFT 1m OHLCV us stocks historical data** — ultra high-quality 1m OHLCV for **MSFT**. US equity cash and extended sessions — institutional-style OHLCV candles for US stocks. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 1m OHLCV** for **MSFT** (US stocks)
- **US equity cash and extended sessions — institutional-style OHLCV candles for US stocks**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/msft) · **1,196,180** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `MSFT_1m.csv` (48,750 rows, `2026-02-02` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/msft)** — **1,196,180** `1m` rows (~88.58 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2011-05-09` -> `2026-07-29`.

## Download sample

**[MSFT_1m.csv](https://github.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/blob/main/MSFT_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/main/MSFT_1m.csv)) · [GitHub Releases](https://github.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/msft-1m-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/msft-1m-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/msft](https://getdata.finance/datasets/msft)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/msft))** |
|---|--:|---|
| Instrument | MSFT · US stocks | MSFT · US stocks |
| Timeframes | `1m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 48,750 | **1,196,180** |
| Size | 4.54 MB | ~88.58 MB |
| Period | `2026-02-02` -> `2026-07-31` | `2011-05-09` -> `2026-07-29` |
| File | `MSFT_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Coverage report | — | [MSFT coverage](https://getdata.finance/coverage/msft) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/msft)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `1m` sample · [getdata.finance](https://getdata.finance/datasets/msft) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `1m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`MSFT_1m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-02T14:30:00+00:00 | 431.27 | 431.27 | 429.02 | 429.19 | 378.0684931507 |
| 2026-02-02T14:31:00+00:00 | 429.19 | 429.19 | 426.61 | 427.84 | 332.1700680272 |
| 2026-02-02T14:32:00+00:00 | 427.84 | 428.94 | 427.68 | 428.94 | 346.2589194699 |
| 2026-02-02T14:33:00+00:00 | 428.94 | 429.02 | 428.07 | 429.02 | 344.2702702703 |
| 2026-02-02T14:34:00+00:00 | 429.02 | 429.02 | 425.2 | 425.79 | 236 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:55:00+00:00 | 470.92 | 471.94 | 470.61 | 471.65 | 421 |
| 2026-07-31T19:56:00+00:00 | 471.65 | 471.88 | 471.33 | 471.76 | 299 |
| 2026-07-31T19:57:00+00:00 | 471.76 | 472.03 | 470.74 | 470.91 | 352 |
| 2026-07-31T19:58:00+00:00 | 470.91 | 471.14 | 469.96 | 471.02 | 313 |
| 2026-07-31T19:59:00+00:00 | 471.02 | 471.09 | 469.63 | 470.23 | 401 |

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
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
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

The complete **MSFT** archive on **[getdata.finance](https://getdata.finance/datasets/msft)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **1,196,180** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full MSFT dataset on getdata.finance](https://getdata.finance/datasets/msft)**

---
*GetData · MSFT 1m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/msft) · 2026-08-04 UTC*
