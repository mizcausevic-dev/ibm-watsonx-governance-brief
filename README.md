# ibm-watsonx-governance-brief

Board-readable Kinetic Gain proof repo for **IBM** signal coverage.

## Signal lane

- Vendor / platform: IBM
- Domain: Enterprise AI / Integration
- Executive question: Where is this system creating exposure, waste, or decision latency?
- Proof posture: synthetic fixture, deterministic CLI, static report, and CI gate.

## Why this exists

IBM watsonx governance, App Connect evidence, enterprise AI posture, and integration controls.

This repo is intentionally small and explicit. It gives the portfolio atlas a named, inspectable proof artifact for IBM without needing another hosted subdomain or exposing live customer data.

## Local run

`ash
npm install
npm test
npm run build
npm run demo
`

## Security posture

- No secrets, tokens, customer records, or live API calls.
- Fixture data is synthetic and stored in ixtures/sample.json.
- Output is deterministic and safe for public portfolio inspection.
