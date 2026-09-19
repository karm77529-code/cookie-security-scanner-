# Cookie Chain Automated Security Scanner & Audit Bot 🛡️

An automated security audit tool and smart contract scanner built for the **Cookie Chain** SVM ecosystem. Designed to help developers and users inspect token metrics, evaluate authority risks, and generate real-time audit reports.

## Features
- **Mint Authority Verification:** Checks whether mint authority is renounced to prevent token dilution.
- **Freeze Authority Inspection:** Validates if freeze authority is disabled to protect user funds.
- **Liquidity Lock Analysis:** Assesses liquidity locks to eliminate rug-pull risks.
- **Concentration Risk Scoring:** Evaluates holder distribution to measure dump exposure.
- **Automated Security Scoring:** Generates a unified risk rating (0-100) based on dynamic checks.

## Tech Stack
- **Runtime:** Node.js
- **Integrations:** Cookie Chain API / RPC endpoints
- **Architecture:** Modular Async Scanner Class

## Quick Start
```bash
git clone [https://github.com/karm77529-code/cookie-security-scanner.git](https://github.com/karm77529-code/cookie-security-scanner.git)
npm install
node index.js
