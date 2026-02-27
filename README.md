# Calculator
Open-source calculator that accurately models UK solar and battery storage returns. Simulates system performance across all half-hourly periods per year, incorporating flexibility services, and tariff arbitrage. Single HTML file, zero dependencies, fully auditable. No data leaves your browser.

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-None-green)]()

## Overview

The Levelise Calculator is a free, transparent, client-side tool that simulates the financial performance of residential and commercial battery storage systems across a full year at **half-hourly granularity** (17,520 periods).

Unlike conventional calculators that rely on high-level assumptions, this tool incorporates real UK market revenue mechanisms and lets users validate proposals with site-specific data — no black boxes, no opaque estimates.

🔗 **Live tool:** [labs.levelise.com](https://labs.levelise.com)

## Key Features

- **Half-hourly simulation** — Models system performance across all 17,520 half-hour periods in a year for precise financial projections.
- **Real UK revenue stacking** — Assesses value across multiple income streams including Capacity Market, flexibility/frequency response services, and smart tariff arbitrage.
- **Site-specific inputs** — Paste consumption and generation profiles directly from spreadsheets to model real operational data.
- **Fully transparent** — Delivered as a single HTML file. All calculations are visible in the source code — verify the maths, challenge the assumptions.
- **Zero server dependencies** — Runs entirely in the browser. No user data is transmitted or stored.
- **Cross-sector applicability** — Works for residential battery evaluations, housing developments, and commercial/industrial energy strategy.

## Getting Started

### Option 1: Use Online
Visit [labs.levelise.com](https://labs.levelise.com) — no installation required.

### Option 2: Run Locally
```bash
# Clone the repository
git clone https://github.com/levelise/calculator.git

# Open directly in your browser
open index.html
```
No build step, no dependencies, no server — just open the HTML file.

## How It Works

1. **Configure your system** — Set battery capacity, solar array size, and inverter specifications.
2. **Input your data** — Paste half-hourly consumption and generation profiles from a spreadsheet, or use default profiles.
3. **Select revenue streams** — Choose which UK market mechanisms to include in the simulation (Capacity Market, flexibility services, tariff arbitrage, etc.).
4. **Run the simulation** — The calculator models every half-hour of the year, optimising battery dispatch against your chosen revenue stack.
5. **Review results** — Get a transparent breakdown of projected savings and revenues with full auditability.

## Use Cases

| Audience | Application |
|---|---|
| **Solar & battery installers** | Validate customer proposals with real data and verifiable methodology |
| **Energy managers** | Stress-test assumptions and compare design options for commercial sites |
| **Housing developers** | Model returns across developments with region-specific tariffs and profiles |
| **System designers** | Compare battery sizing, solar configurations, and revenue stack scenarios |

## Technical Details

- **Format:** Single self-contained HTML file
- **Runtime:** Client-side JavaScript — no backend, no API calls
- **Resolution:** Half-hourly (48 periods/day × 365 days = 17,520 data points)
- **Data privacy:** All data stays in the browser. Nothing is transmitted externally.

## About Levelise

[Levelise](https://www.levelise.com) is a UK energy technology company operating as a Virtual Power Plant (VPP). We connect home batteries, EVs, and heat pumps to energy markets, and have paid over £2 million to customers since October 2019 through participation in Capacity Market, frequency response, Balancing Mechanism, and wholesale energy markets.

The Levelise Calculator is built on the same methodology and market understanding that underpins our live trading platform.

## Contributing

We welcome contributions. If you'd like to improve the calculator, add features, or fix bugs:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Contact

- **Website:** [levelise.com](https://www.levelise.com)
- **Calculator:** [labs.levelise.com](https://labs.levelise.com)
- **Issues:** [GitHub Issues](../../issues)
