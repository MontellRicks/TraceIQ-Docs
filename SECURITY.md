# Security & Responsible Use

## Demo-Safe Defaults
- Live capture disabled: `TRACEIQ_DISABLE_LIVE_CAPTURE=1`
- Offensive modules disabled: `TRACEIQ_DISABLE_ATTACKS=1`
- PII masking enabled: `TRACEIQ_MASK_PII=1`
- Known-safe input: `TRACEIQ_TEST_PCAP=/opt/traceiq/test_pcaps/test_malicious.pcap`

## Data Handling
Never commit real PCAPs, credentials, keys, or customer data.

## Vulnerability Reporting
Please open a private GitHub Security Advisory rather than a public issue.
