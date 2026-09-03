# MSFT 1m OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-636_443_rows-blue)](https://getdata.finance/datasets/msft) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/msft)

### -> [**Download the full MSFT dataset on getdata.finance**](https://getdata.finance/datasets/msft)

**MSFT 1m OHLCV stocks historical data** — ultra high-quality 1m OHLCV for **Microsoft**. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 1m OHLCV** for **Microsoft** (US stocks)
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`1m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/msft) · **636,443** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `1m` sample updated in sync

> **Sample on GitHub** · `MSFT_1m.csv` (55,440 rows, `2026-02-06` -> `2026-09-01`). **Full archive on [getdata.finance](https://getdata.finance/datasets/msft)** — **636,443** `1m` rows, **11 timeframes**, `2020-02-25` -> `2026-09-01`.

## Download sample

**[MSFT_1m.csv](https://github.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/blob/main/MSFT_1m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/msft-1m-ohlcv-stocks-historical-data/main/MSFT_1m.csv))

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/msft))** |
|---|--:|---|
| Instrument | Microsoft · US stocks | Microsoft · US stocks |
| Timeframes | `1m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 1m rows | 55,440 | **636,443** |
| Period | `2026-02-06` -> `2026-09-01` | `2020-02-25` -> `2026-09-01` |
| File | `MSFT_1m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/msft) |
| Coverage report | — | [MSFT coverage](https://getdata.finance/coverage/msft) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`1m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/msft)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes**:

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **4H** · **12H** · **1D** · **3D** · **1W**

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples refreshed weekly, in sync with getdata.finance.

## Data preview

First and latest rows from the GitHub sample **`MSFT_1m.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-06T19:54:00+00:00 | 398.25 | 398.26 | 398.03 | 398.23 | 96 |
| 2026-02-06T19:55:00+00:00 | 398.23 | 398.32 | 397.95 | 397.95 | 170 |
| 2026-02-06T19:56:00+00:00 | 397.95 | 398.06 | 397.75 | 398.03 | 172 |
| 2026-02-06T19:57:00+00:00 | 398.03 | 398.35 | 397.99 | 398.08 | 139 |
| 2026-02-06T19:58:00+00:00 | 398.08 | 398.3 | 397.97 | 398.3 | 98 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-01T19:55:00+00:00 | 500.36 | 500.4 | 499.93 | 500.05 | 151 |
| 2026-09-01T19:56:00+00:00 | 500.05 | 500.11 | 499.79 | 500 | 136 |
| 2026-09-01T19:57:00+00:00 | 500 | 500.03 | 499.71 | 499.94 | 170 |
| 2026-09-01T19:58:00+00:00 | 499.94 | 500.12 | 499.75 | 500.03 | 180 |
| 2026-09-01T19:59:00+00:00 | 500.03 | 500.87 | 499.89 | 500.48 | 229 |

## Schema

| Column | Description |
| --- | --- |
| `time` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
time,open,high,low,close,volume
```

## Download full data

Full MSFT archive — 11 timeframes, gap-free, updated weekly:

**[-> Get the full MSFT dataset on getdata.finance](https://getdata.finance/datasets/msft)**
