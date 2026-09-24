# 2S Li-ion BMS USB-C Charger

Design a 2S1P Li-ion battery BMS and USB-C charging PCB.

Battery: 2 × 18650 Li-ion cells in series, 3.7 V nominal each,
4.2 V maximum each, 7.4 V nominal pack, 8.4 V full charge,
approximately 2200 mAh.

Requirements:
- USB-C 5 V input
- 5 V to 8.4 V boost CC/CV charging
- approximately 0.75 A charging current
- 2S battery protection
- overcharge protection
- overdischarge protection
- overcurrent and short-circuit protection
- individual cell voltage monitoring
- cell balancing
- back-to-back MOSFET protection
- protected P+ and P- load output
- B-, B1, B+ battery connections
- 2-layer PCB
- target load up to 5 A, subject to actual cell and MOSFET ratings
- test points for B-, B1, B+, P+, P-, 5 V and 8.4 V

Verify all IC pinouts, thresholds, component values and ratings from
official manufacturer datasheets. Do not guess.

Do not create the PCB yet. First determine the circuit architecture
and exact components.
