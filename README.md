# Vietnamese 500kV Transmission System Model

This repository contains the dataset and simplified model parameters for the Vietnamese 500kV transmission system, as presented in the research paper.

## Dataset Description

The data includes:
- **Bus Data:** Voltage, load demands.
- **Branch Data:** Resistance (R), Reactance (X), Susceptance (B), and transmission topologies capacity for 500kV transmission lines.
- **Generator Data:** Active, reactive power limits, shunt compensation, and load-shedding.

## File Structure
- `VN_500kV_comp.m`: Contains the network data for the scenario with RPP considered
- `VN_500kV_non_comp.m`: Contains the network data for the scenario without RPP considered

## Citation
If you use this data for your research, please cite our paper:
> [Nguyen Duc Huy Bui and Thanh Long Duong], "[An Enhanced Method For Solving Security-Constrained AC Transmission Expansion Planning Considering Reactive Power Planning: A Case Study In Vietnam]".

## Contact
For any questions, please contact: [huybnd25761@pgr.iuh.edu.vn]
