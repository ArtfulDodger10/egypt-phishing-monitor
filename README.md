# Egypt Phishing Monitor

> **Coming soon.** This repo is being prepared; the code, detections and report land here as soon as they are finished.

A lookalike-domain monitor for Egyptian banks and fintechs (certificate transparency, dnstwist, urlscan) with STIX 2.1 output, and the passive-only research on the phishing infrastructure it found.

- Write-up (coming soon): https://artfuldodger10.github.io/posts/Egypt-Phishing-Infrastructure/
- Case file in my portfolio: https://artfuldodger10.github.io/portfolio/#/case/egypt-phishing

## What it will cover

- Passive sources only: crt.sh, CertStream, urlscan, dnstwist, RDAP, Shodan, Censys
- Clustering by certificates, hosting, registrars and phishing-kit traits
- Live phishing sites are reported to the brands and hosts before anything is published

## Planned contents

| Path | What it will hold |
|---|---|
| `tools/` | The monitor (Python) |
| `reports/` | The research write-up |
| `iocs/` | Defanged IOCs and a STIX 2.1 bundle |

---
Nader Ayman · [Portfolio](https://artfuldodger10.github.io/portfolio/) · [Blog](https://artfuldodger10.github.io/) · [GitHub](https://github.com/ArtfulDodger10)
