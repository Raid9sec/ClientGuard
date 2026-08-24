# ClientGuard

ClientGuard is a defensive cybersecurity assessment platform designed for authorized network security assessments.

**Written by Raid9sec**

## Current Stable Release

ClientGuard v8.0.0

## Safety Notice

ClientGuard must only be used on systems and networks that you own or have explicit authorization to assess.

Safety boundaries include:

- No automatic exploit execution
- No automatic remediation
- No automatic finding closure
- No automatic risk acceptance
- No automatic scope expansion
- No credential persistence
- No silent upload or export

## Requirements

- Linux / Kali Linux
- Python 3
- Optional cybersecurity assessment utilities such as Nmap

## Installation

Make ClientGuard executable:

    chmod +x clientguard.py

Check the version:

    python3 clientguard.py --version

Run the native v8 self-test:

    python3 clientguard.py --v8-self-test

## Verify Integrity

    sha256sum -c SHA256SUMS

ClientGuard v8.0.0 runtime SHA-256:

    11db71b93aa030493f70a36023da36012868c2e66b2c278854fbc1f2e6daf0f5

## Compatibility

- Scoring Model: 7.5.0-1
- Report Schema: 6
- Storage Schema: 3

## Security

See `SECURITY.md`.

## Author

Written by Raid9sec.
