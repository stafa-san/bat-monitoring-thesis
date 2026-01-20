# Beyond Single Sensors: Multi-modal Edge Systems for Ecological Monitoring

## Project Overview

**Thesis Title:** Beyond Single Sensors: Quantifying Data Integrity in Multi-modal Edge Systems for Real-Time Ecological Monitoring

**Author:** Mustapha Nasomah
**Advisor:** Dr. Joseph S. Johnson
**Committee Members:** Dr. Adib Zaman, Dr. Jess Kropczynski
**Program:** Master of Science, School of Information Technology
**Expected Graduation:** May 2026

### Research Questions

- **RQ1:** What types of environmental sensors are currently used alongside acoustic bat detectors, and what are their individual performance characteristics in field deployments?
- **RQ2:** How can acoustic and environmental sensor streams be integrated using edge computing platforms for contextual bat monitoring while maintaining quantifiable data integrity metrics?

---

## Project Timeline

| Period | Phase | Status |
|--------|-------|--------|
| Oct 2025 - Nov 2025 | Phase 1: Literature Review & System Design | Completed |
| Nov 2025 - Jan 2026 | Phase 2: Platform Development & Integration | **CURRENT** |
| Feb 2026 - Apr 2026 | Phase 3: Field Testing & Data Collection | Pending |
| Apr 2026 - May 2026 | Phase 4: Analysis, Writing, & Defense | Pending |

---

## Repository Structure

```
bat-monitoring-thesis/
├── README.md                      # This file
├── PROGRESS_LOG.md                # Daily/weekly progress updates
├── CHANGELOG.md                   # Major milestones and changes
│
├── docs/
│   ├── literature-review/         # SLR documents and notes
│   ├── meeting-notes/             # Advisor meeting summaries
│   └── presentations/             # Committee presentations
│
├── resources/
│   ├── RESOURCES.md               # Curated list of all resources
│   ├── papers/                    # Reference papers (PDFs or links)
│   ├── tutorials/                 # Helpful tutorials and guides
│   └── code-references/           # External code repositories
│
├── hardware/
│   ├── HARDWARE_INVENTORY.md      # All hardware components
│   ├── setup-guides/              # Hardware setup documentation
│   └── diagrams/                  # System architecture diagrams
│
├── software/
│   ├── edge-platform/             # K3S/Raspberry Pi cluster setup
│   ├── audiomoth-integration/     # AudioMoth configuration & code
│   └── sensor-fusion/             # Multi-sensor integration code
│
├── experiments/
│   ├── lab-tests/                 # Controlled environment tests
│   ├── field-deployments/         # Field test data and logs
│   └── analysis/                  # Data analysis scripts
│
├── issues/
│   └── CHALLENGES.md              # Challenges and solutions log
│
└── .github/
    └── ISSUE_TEMPLATE/            # Templates for progress tracking
```

---

## Technology Stack

| Component | Technology | Purpose |
|-----------|------------|---------|
| Edge Computing | Raspberry Pi 4B (8GB) | Processing node |
| Orchestration | K3S (Kubernetes) | Container management |
| Protocol | HTTP/3 + Nginx | Optimized data transmission |
| Acoustic Sensor | AudioMoth Dev | Bat echolocation capture |
| Environmental | DHT22, TSL2591, etc. | Temperature, humidity, light |
| ML Framework | Audio Spectrogram Transformer | Sound classification |
| Database | PostgreSQL | Data storage |
| Monitoring | Home Assistant | Device management |

---

## Data Integrity Metrics

This research will quantify:

- **Data Loss Rate** - Percentage of expected data points captured
- **Sensor Stream Alignment Error** - Temporal offset between sensors
- **Real-time Processing Latency** - End-to-end delay
- **Power Efficiency** - Energy per data point collected

---

## Progress Summary

| Milestone | Status | Date |
|-----------|--------|------|
| Thesis Proposal Approved | Completed | Oct 2025 |
| Hardware Acquired | Completed | Jan 2026 |
| Raspberry Pi OS Installed | Completed | Jan 2026 |
| K3S Cluster Setup | In Progress | - |
| AudioMoth Integration | Pending | - |
| Sensor Fusion Pipeline | Pending | - |
| Field Deployment | Pending | - |

---

## Quick Links

- [Progress Log](PROGRESS_LOG.md)
- [Hardware Inventory](hardware/HARDWARE_INVENTORY.md)
- [Resources](resources/RESOURCES.md)
- [Challenges](issues/CHALLENGES.md)
- [Changelog](CHANGELOG.md)

---

## Key Resources

### Papers & Documentation

- Koch & Thomas (2025) - HTTP/3 Containerized Deployments
- AudioMoth GPS Sync Documentation
- Audio Spectrogram Transformers Beyond the Lab

### Community & Support

- [WILDLABS Community](https://wildlabs.net/) - Conservation tech discussions
- [Open Acoustic Devices Forum](https://www.openacousticdevices.info/support)
- [OpenSoundscape](https://opensoundscape.org/) - Acoustic localization toolkit

---

## Contact

**Mustapha Nasomah**
Graduate Student, School of Information Technology
University of Cincinnati

---

*Last Updated: January 20, 2026*
