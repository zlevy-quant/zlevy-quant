## Zahava Levy

Quantitative trading-systems engineer. I design and build the infrastructure that sits between strategy and the market: pre-trade risk and control layers, order-management flow, and the validation systems that prove a trading system behaves correctly before it goes live.

Infracta Quantitative Systems ([infracta.com](https://www.infracta.com)).

### Focus
- Pre-trade risk and control engines, with fail-closed design, supervisory override, and audit trails
- Trading-system parity and validation: proving a reimplementation matches its reference trade for trade before production
- Backtesting and execution infrastructure (Python, Backtrader, broker API integration)
- Correctness, reproducibility, and engineering rigor under regulatory constraints

### Selected work
- **[pretrade-desk](https://github.com/zlevy-quant/pretrade-desk)**: a compact, dependency-free pre-trade risk engine. A single enforcement boundary runs a chain of fail-closed controls and returns an allow or block verdict with a full audit trail. Type-checked with mypy strict, tested, and run in CI across Python 3.10 to 3.12.
- **Cross-language strategy parity and validation engine**: a trade-by-trade parity system aligning a PineScript strategy with a Python/Backtrader reimplementation before production cutover. Private, available on request.

### Elsewhere
- Website: [infracta.com](https://www.infracta.com)
- ORCID: [0009-0002-1820-176X](https://orcid.org/0009-0002-1820-176X)
