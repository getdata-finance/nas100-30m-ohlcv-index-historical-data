# NAS100 30m OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-205_310_rows-blue)](https://getdata.finance/datasets/nas100) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/nas100)

### -> [**Download the full NAS100 dataset on getdata.finance**](https://getdata.finance/datasets/nas100)

**NAS100 30m OHLCV index historical data** — ultra high-quality 30m OHLCV for **NASDAQ 100**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 30m OHLCV** for **NASDAQ 100** (Index)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`30m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/nas100) · **205,310** `30m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `30m` sample updated in sync

> **Sample on GitHub** · `NAS100_30m.csv` (5,967 rows, `2026-03-10` -> `2026-09-09`, 505.18 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/nas100)** — **205,310** `30m` rows (full `1m`: 5,050,229), **11 timeframes**, `2009-01-02` -> `2026-09-09`.

## Download sample

**[NAS100_30m.csv](https://github.com/getdata-finance/nas100-30m-ohlcv-index-historical-data/blob/main/NAS100_30m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/nas100-30m-ohlcv-index-historical-data/main/NAS100_30m.csv)) · [GitHub Releases](https://github.com/getdata-finance/nas100-30m-ohlcv-index-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/nas100-30m-ohlcv-index-historical-data/](https://getdata-finance.github.io/nas100-30m-ohlcv-index-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/nas100](https://getdata.finance/datasets/nas100)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/nas100))** |
|---|--:|---|
| Instrument | NASDAQ 100 · Index | NASDAQ 100 · Index |
| Timeframes | `30m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 30m rows | 5,967 | **205,310** |
| Size | 505.18 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/nas100) |
| Period | `2026-03-10` -> `2026-09-09` | `2009-01-02` -> `2026-09-09` |
| File | `NAS100_30m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/nas100) |
| Coverage report | — | [NAS100 coverage](https://getdata.finance/coverage/nas100) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`30m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/nas100)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `30m` sample · [getdata.finance](https://getdata.finance/datasets/nas100) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `30m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`NAS100_30m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-10T19:00:00+00:00 | 25007.24 | 25050.74 | 24964.49 | 24967.86 | 141610 |
| 2026-03-10T19:30:00+00:00 | 24967.86 | 25010.11 | 24919.74 | 24961.61 | 143272 |
| 2026-03-10T20:00:00+00:00 | 24961.61 | 25015.96 | 24961.61 | 25001.71 | 29920 |
| 2026-03-10T20:30:00+00:00 | 25001.71 | 25006.84 | 24971.09 | 24987.54 | 16945 |
| 2026-03-10T22:00:00+00:00 | 24987.54 | 24997.52 | 24948.27 | 24950.89 | 9596 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-09T00:00:00+00:00 | 29475.95 | 29536.83 | 29475.2 | 29500.95 | 35700 |
| 2026-09-09T00:30:00+00:00 | 29500.95 | 29537.7 | 29484.95 | 29535.7 | 28163 |
| 2026-09-09T01:00:00+00:00 | 29535.7 | 29574.83 | 29531.58 | 29565.58 | 23083 |
| 2026-09-09T01:30:00+00:00 | 29565.58 | 29583.2 | 29553.33 | 29568.33 | 21258 |
| 2026-09-09T02:00:00+00:00 | 29568.33 | 29568.33 | 29568.33 | 29568.33 | 0 |

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

df = pd.read_csv('NAS100_30m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('NAS100_30m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('NAS100_30m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='30min')
print(pf.stats())
```

## Download full data

The complete **NAS100** archive on **[getdata.finance](https://getdata.finance/datasets/nas100)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **205,310** rows at `30m`, plus all other timeframes in the same ZIP.

**[-> Get the full NAS100 dataset on getdata.finance](https://getdata.finance/datasets/nas100)**

---
*GetData · NAS100 30m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/nas100)*
