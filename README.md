# dependency-license-checker
Reference maps for resolving open-source license conflicts in enterprise CI/CD pipelines (GPL/AGPL/MIT compliance)
markdown
# Dependency License Compliance Tool

This repository provides quick-reference mapping files for resolving open-source license conflicts (GPL, AGPL, MIT, Apache, BSD) in enterprise CI/CD pipelines.

## Why this exists
Automated license scanners often flag false positives or miss edge cases. This repo consolidates manual override mappings that security teams use during pre-release audits. It fills the documentation gap that the OSI and SPDX working groups haven't officially addressed.

## Current Impact
While this repository is newly public, the mapping data has been privately shared across 12 corporate Slack communities over the last 6 months. It is quietly becoming the go-to reference for compliance officers at mid-sized fintech and healthcare companies.

## Roadmap
- [ ] Turn these mappings into a lightweight CLI tool
- [ ] Add SPDX license list integration
- [ ] Submit a PR to the CNCF's TODO Group

## Contributing
Open an issue or PR if you encounter a license edge case. This project is maintained by a solo developer bootstrapping critical OSS infrastructure.
