# Finance-in-Python
## Project Structure
project-root/
│
├── data/
│   ├── __init__.py
│   ├── blacklist.py
│   ├── fetcher.py
│   ├── intraday_fetcher.py
│   ├── storage.py
│   └── universe.py
│
├── financial_engine/
│   ├── basics.py
│   ├── cashflow.py
│   ├── derivatives.py
│   ├── portfolio.py
│   ├── pricing.py
│   ├── probability.py
│   ├── risk.py
│   └── time_value.py
│
├── fundamental_component/
│
├── ml/
│   ├── __init__.py
│   ├── features.py
│   ├── model.py
│   └── xgb_inference.py
│
├── portofolio/
│   └── allocation.py
│
├── scripts/
│   ├── __init__.py
│   ├── clean_universe.py
│   ├── download_ihsg.py
│   ├── eval.py
│   ├── eval_ensemble.py
│   ├── optimize_tbl.py
│   ├── signals.py
│   ├── sync_data.py
│   ├── train.py
│   └── tune_lstm.py
│
├── signals/
│   ├── __init__.py
│   ├── combiner.py
│   └── screener.py
│
├── utils/
│   ├── __init__.py
│   ├── logger.py
│
└── config.py
└── run.py
