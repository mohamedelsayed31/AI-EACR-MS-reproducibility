# AI-EACR-MS — Research Reproducibility Archive

**AI-EACR-MS: Receipt-Audited Gateway Staging and Learned Mobile-Sink Collection in Wireless Sensor Networks**

Authors: Mohamed Elsayed Eldesouky, Youssef Mohammed Alsayed, Mohamed Labib Borham  
Institution: October University for Modern Sciences and Arts, Giza, Egypt  
Corresponding author: mohamed.elsayed30@msa.edu.eg

## Research archive

**[Download research evidence and simulator — v1.0.0](https://github.com/mohamedelsayed31/AI-EACR-MS-reproducibility/releases/tag/v1.0.0)**

In the release's **Assets**, download `AI_EACR_MS_Research_Archive_FRESH.zip`. It contains:

- `WSN_SOURCE_ORIGINAL.zip`: archived simulator source with frozen GNN/PPO checkpoint.
- `REPRO_EVIDENCE.zip`: evaluation data, configurations, analysis scripts and audits.
- `README_FOR_DEPOSIT.md`: archival provenance note (written before the public release).
- `RELEASE_SHA256.txt`: SHA-256 digests of the two nested archives.

Expected SHA-256 for the complete downloadable outer archive:
`907755f8297e9e4e1465846d83e3e2ecacf9de304f7c46c156bb5bc943a8ed8c`

### Extraction

Download the outer ZIP and extract it. Then extract `WSN_SOURCE_ORIGINAL.zip` and `REPRO_EVIDENCE.zip` into separate folders. Consult their included run and configuration files before launching an experiment.

### Interpretation and limits

The paired controller evaluations and native-protocol replays have **different comparability conditions**. Native replays are descriptive and must not be interpreted as a causal speed ranking. Sink payload receipt is modeled and audited; the internal ACK ledger is not physical wireless source-return ACK verification. Some historical training commands and per-message traces were not archived, and an independent clean-environment full reproduction is not claimed.

### Status

Research submission archive; not yet journal-accepted. No persistent DOI has been assigned. Please cite the associated manuscript if/when it is published.

The original release is public; inspect any redistributable third-party material and software-license terms before reuse.
