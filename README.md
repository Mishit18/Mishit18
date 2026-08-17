# Mishit Sharma

IIT Bombay student building applied machine-learning, quantitative-finance,
analytics, and operations projects. This profile emphasizes reproducible
evidence: each highlighted claim links to code, data provenance, tests, or a
report. Simulated and real datasets are labeled explicitly.

## Live Product

### FlowFinance

[Live application](https://www.flowfinancebusiness.com) | [Public strategy case](https://github.com/Mishit18/flowfinance_market_entry_case)

- Co-founded an MSME financial-intelligence product deployed with AWS EC2 and
  RDS inside a VPC, with Secrets Manager used for application credentials.
- Built transaction intelligence over 81,813 mixed anonymized and generated
  records across 28 categories.
- Ran one-month free pilots with 10+ MSMEs; 10+ returned after initial use.
- No paid-customer or revenue claim is made for FlowFinance.

## Selected Evidence by Track

### Machine Learning

| Project | Evidence |
|---|---|
| [Mistral-7B QLoRA](https://github.com/Mishit18/ML-PROJECTS/tree/main/mistral-7b-qlora-lora-finetuning) | 1,200-step run, rank/target-module ablations, held-out perplexity reports |
| [CIFAR-10 DDPM](https://github.com/Mishit18/ML-PROJECTS/tree/main/ddpm-cifar10-from-scratch) | 71.03M-parameter U-Net, 50K-sample evaluation, FID 10.0958, IS 8.7801 |
| [Mini-GPT](https://github.com/Mishit18/ML-PROJECTS/tree/main/mini-gpt) | Decoder-only model, KV-cache benchmarks, ablations, LoRA adapters, model card |
| [ML Serving and Monitoring](https://github.com/Mishit18/ML-PROJECTS/tree/main/real-time-model-serving-monitoring) | FastAPI, Docker, latency reports, PSI drift checks, tests |

### Quantitative Research and Trading

| Project | Data status and evidence |
|---|---|
| [BTC Adaptive Grid Research](https://github.com/Mishit18/btc-adaptive-grid-research) | Live Binance WebSocket paper engine, persistent state, bid/ask fills, and 40,536-candle holdout evidence |
| [OpenBB Macro Portfolio Research](https://github.com/Mishit18/openbb-macro-portfolio-research) | 16,919 real records across seven ETFs; monthly walk-forward optimization, costs, bootstrap intervals, and dashboard |
| [Factor Modeling](https://github.com/Mishit18/QUANT-PROJECTS/tree/main/02_quant_research/01_factor_modeling_pca_eigenportfolios) | Adjusted prices for 49 real US equities; PCA and classical-factor diagnostics |
| [Regime-Aware State-Space Research](https://github.com/Mishit18/QUANT-PROJECTS/tree/main/01_universal_foundations/03_kalman_filter_hmm_regimes) | Real SPY/QQQ/TLT prices; Kalman state estimation, Gaussian HMM regimes, turnover costs, and honest passive-benchmark limits |
| [Cointegration Pairs](https://github.com/Mishit18/QUANT-PROJECTS/tree/main/02_quant_research/02_cointegration_stat_arb_kalman_spreads) | Nine real US ETFs; Johansen, Kalman, HMM, cost-aware backtests |
| [Market Making](https://github.com/Mishit18/QUANT-PROJECTS/tree/main/03_quant_trading/02_avellaneda_stoikov_market_making) | Simulated LOB; HJB-derived quotes, Monte Carlo stress tests, PnL attribution |
| [HFT Signal Research](https://github.com/Mishit18/QUANT-PROJECTS/tree/main/03_quant_trading/01_hft_microstructure_alpha_signals) | Synthetic 100K-event LOB; executable-edge and transaction-cost diagnostics |
| [Options Pricing](https://github.com/Mishit18/QUANT-PROJECTS/tree/main/04_quant_developer/01_cpp_derivatives_pricing_engine) | Heston, Black-Scholes, Monte Carlo/QE, Greeks, calibration tests |

### Data Analytics and Operations

| Project | Evidence |
|---|---|
| [Manufacturing Quality Analytics](https://github.com/Mishit18/manufacturing_quality_process_analytics) | Simulated 52K-batch operations study plus real UCI steel-fault benchmark and dashboard |
| [Credit Risk Lifecycle Analytics](https://github.com/Mishit18/ML-PROJECTS/tree/main/credit-risk-customer-lifecycle-analytics) | Synthetic portfolio plus real OpenML benchmark, SQL approval simulator, drift/fairness checks |
| [Supply-Chain Network Design](https://github.com/Mishit18/supply-chain-network-optimization) | Facility-location MILP, scenario stress tests, RAG decision support, Streamlit dashboard |
| [SQL Operations Analytics](https://github.com/Mishit18/sql_ops_analytics) | DuckDB KPI layer, cohorts, query profiling, SLA governance |
| [Demand Forecasting](https://github.com/Mishit18/demand_forecasting) | Rossmann forecasting, model comparison, safety-stock and service-level decisions |
| [Experimentation](https://github.com/Mishit18/conversion_funnel_experimentation) | Funnel analysis, A/B testing, power/MDE, CUPED and heterogeneous effects |

## Internship Evidence Policy

Funded Nation and Evore Labs work involved internal prototypes. Public claims
are limited to aggregate, employer-verifiable outcomes. No proprietary data,
customer records, strategy logic, private screenshots, or confidential source
code is published. Sanitized case studies will be added only after written
employer approval.

## Reproducibility Standard

- Real, anonymized, generated, and simulated data are identified separately.
- Negative or rejected research results remain visible when they are the honest
  result of leakage-safe and cost-aware evaluation.
- Repository metrics should be reproducible from committed reports or commands.
- Paper trading and exchange Testnet activity are not described as live-money
  trading.
