# Fortinet — Myanmar Government & e-Government Ransomware Resilience Blueprint (v2.0 · Aug 2026)

Government edition of the June 2026 sector-resilience blueprint, re-aimed at the **lead digital-government ministry**, the e-Government Steering Committee and Union ministries. Anchored in the **Cybersecurity Law 2025** (SAC Law 1/2025, in force 30 Jul 2025) CII duties; no bank-specific framing.

> Open [`index.html`](index.html) in a browser. **Save as PDF** (top-right) exports through Chrome print CSS. Pre-rendered copy: `ftnt_ransomeware_preventive_v2_gov_aug2026.pdf`. Re-render with `./render-pdf.sh` (headless Chrome only — never WeasyPrint).

## What changed from v1 (June 2026, banking)
- All affected institutions are anonymised (non-disclosure); catalyst is the Myanmar public-sector threat snapshot described by incident type only (2025 HR-data incidents, Jun 2026 extortion, state-nexus espionage).
- New **05 Lessons from abroad**: Indonesia PDN, Costa Rica, PhilHealth, Malaysia KLIA, Thailand MoL (claimed vs. stated), Vietnam governance response.
- SWIFT CSP / PCI DSS crosswalk → **Cybersecurity Law 2025 s.17 duties · NIST CSF 2.0 · ISO 27001:2022 · CISA ZTMM v2 · ASEAN CCS 2026–2030 / ASEAN Regional CERT**, plus NCSI execution-gap callout.
- AWS band → **Sovereign cloud** (Government Data Centre / Government Cloud, FortiSASE Sovereign / Outpost, on-prem SIEM/SOAR) with architecture diagram.
- Proof points re-validated Aug 2026: MITRE and SD-WAN MQ claims retired; now Hybrid Mesh Firewall Leader (2025), 11 Gartner MQs (Mar 2026), #2 Sovereign SASE use case (Gartner CC Jul 2026), Peer Insights EPP 2026; threat stats from Fortinet 2026 Global Threat Landscape Report.
- Product naming updated: FortiEndpoint, FortiSOC (cloud option), FortiIdentity Cloud, FortiOS 8.0.

## Publish
```bash
git init -b main && git add . && git commit -m "Gov ransomware resilience blueprint v2.0"
git remote add origin https://github.com/torukung/ftnt_ransomeware_preventive_v2_gov_aug2026.git
git push -u origin main   # then Settings → Pages → main
```
Document is marked Confidential — keep the repo private unless intended for sharing.

*Fortinet brand only — Red #DA291C, Inter. Prepared by Fortinet · Myanmar · v2.0 (August 2026).*
