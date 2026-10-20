# TinyML Fault Detection for Power Distribution Networks

Low-cost, machine-learning-based fault detection and classification for power distribution networks, designed to run on inexpensive microcontrollers such as the ESP32.

## Motivation
Power distribution networks in many developing regions, including Ethiopia, experience frequent outages. Faults are often located manually, which makes restoration slow and costly. This project explores whether lightweight ML models running on cheap hardware can detect and classify faults automatically.

## Approach (planned)
1. Simulation: model distribution feeders with open-source Python power-system tools and simulate different fault types and locations.
2. Dataset: generate a labeled dataset of voltage and current measurements under normal and fault conditions.
3. Modeling: train lightweight ML models to detect and classify faults.
4. Deployment: compress the best model and run it on an ESP32 microcontroller.

## Roadmap
- [ ] Literature review
- [ ] Feeder simulation and fault scenarios
- [ ] Synthetic fault dataset (to be released publicly)
- [ ] Model training and evaluation
- [ ] Model compression and ESP32 deployment
- [ ] Technical report / preprint

## Status
Early stage: planning and literature review. Undergraduate research project.

## Author
- Bernabas Mulugeta
- B.Sc. Electrical and Computer Engineering (Computer Engineering stream), Addis Ababa University
- ORCID: [0009-0009-3663-7752](https://orcid.org/0009-0009-3663-7752)
- LinkedIn: [bernabas-mulugeta](https://www.linkedin.com/in/bernabas-mulugeta/)

## License
MIT
