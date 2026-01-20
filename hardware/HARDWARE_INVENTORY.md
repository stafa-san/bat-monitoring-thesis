# Hardware Inventory

Complete list of hardware components for the thesis project.

---

## Acquired Hardware

| Item | Specifications | Quantity | Status | Date Acquired | Notes |
|------|---------------|----------|--------|---------------|-------|
| Raspberry Pi 5 | 8GB RAM | 1 | Operational | Jan 2026 | OS installed |
| SD Card | TBD GB | 1 | In Use | Jan 2026 | Raspberry Pi OS |
| AudioMoth | Dev Board | 1 | Pending Setup | Jan 2026 | For acoustic capture |

---

## Planned Hardware

| Item | Specifications | Purpose | Priority | Est. Cost |
|------|---------------|---------|----------|-----------|
| DHT22 | Temperature/Humidity | Environmental sensing | Optional | ~$10 |
| TSL2591 | Light sensor | Ambient light detection | Optional | ~$7 |
| GPS Module | NEO-6M or similar | Time synchronization | Medium | ~$15 |
| 3D Printed Enclosure | Custom design | Field deployment housing | High | Materials only |
| Power Bank / Solar | TBD | Extended field operation | High | TBD |

> **Note:** Environmental sensors (DHT22, TSL2591) are nice-to-have additions for multi-modal sensing. Core focus is acoustic (AudioMoth) + edge computing integration first.

---

## Setup Status

### Raspberry Pi 5
- [x] Hardware received
- [x] OS installed (Raspberry Pi OS)
- [ ] Docker installed
- [ ] K3S installed
- [ ] Nginx configured with HTTP/3
- [ ] Network configured for edge deployment

### AudioMoth
- [x] Hardware received
- [ ] Firmware configured
- [ ] Recording settings optimized for bat frequencies
- [ ] Connected to Raspberry Pi
- [ ] Data pipeline established

### Environmental Sensors (Optional)
- [ ] Hardware acquired
- [ ] Wiring completed
- [ ] Calibration performed
- [ ] Integration with data pipeline

### 3D Printed Enclosure
- [x] Signed up for 3D printing training
- [ ] Training completed
- [ ] Enclosure designed
- [ ] Prototype printed
- [ ] Field-ready version completed

---

## Wiring Diagrams

*To be added in `diagrams/` folder*

---

## Supplier Information

| Supplier | Items | Notes |
|----------|-------|-------|
| University (Advisor) | Raspberry Pi, SD Card, AudioMoth | Provided by Dr. Johnson |
| TBD | Environmental sensors | To be purchased |

---

## Maintenance Log

| Date | Item | Action | Notes |
|------|------|--------|-------|
| Jan 2026 | Raspberry Pi | OS Installation | Successful |
