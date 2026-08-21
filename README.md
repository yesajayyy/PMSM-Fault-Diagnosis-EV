# AI-Based Fault Diagnosis and Fault-Tolerant Control of PMSM for Electric Vehicles

Project Overview
A year-long research project focused on developing an AI-driven system to detect,
diagnose, and respond to faults in Permanent Magnet Synchronous Motors (PMSM)
used in electric vehicle drivetrains — aimed at improving motor reliability,
safety, and operational continuity under fault conditions.

**Status:** 🟡 Planning phase — starting August 2026 · Duration: ~1 year

## 🎯 Objectives
- Study common PMSM fault modes relevant to EV motor drives
- Develop simulation models of healthy and faulty PMSM operation
- Design an AI/ML-based fault diagnosis system to detect and classify faults
- Implement fault-tolerant control strategies to maintain safe motor operation
  after fault detection

Target Fault Types

- **Electrical faults** — inter-turn short circuits, winding faults
- **Demagnetization faults** — partial/total loss of magnet strength
  (common in EVs due to thermal stress and aging)
- **Sensor faults** — position/speed sensor failure or drift

Approach

**Simulation**
- MATLAB/Simulink for PMSM modeling and fault injection
- Generation of healthy and faulty operating condition datasets
  (current, voltage, speed signals)

**Fault Diagnosis**
- Signal processing (FFT/wavelet analysis) for feature extraction
- Machine learning / deep learning models for fault classification

**Fault-Tolerant Control**
- Control strategy design to maintain safe motor operation after a fault
  is detected and classified

Roadmap
- [ ] Literature review on PMSM faults and diagnosis methods
- [ ] Build baseline PMSM simulation model in MATLAB/Simulink
- [ ] Fault injection and dataset generation
- [ ] Feature extraction and fault diagnosis model development
- [ ] Fault-tolerant control design and integration
- [ ] Testing, validation, and results documentation

Tools
MATLAB · Simulink · Python (for ML/DL modeling)


This repository will be updated progressively as the project develops over
the coming months.
