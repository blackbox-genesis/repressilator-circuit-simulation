# Repressilator Oscillator Simulation

This project simulates a classic Repressilator genetic circuit using Tellurium and Python. The system includes three repressors: proteins "A, B, and C", arranged in a negative feedback loop where each protein represses the transcription of the next. This creates sustained oscillations in gene expression over time.

## Model Description

The model includes:
- mRNA and protein production for genes A, B, and C
- Transcription controlled by Hill repression
- Translation of proteins from their respective mRNAs
- Degradation of both mRNA and protein

All components are implemented in Antimony format and simulated using Tellurium.

## Files

- `repressilator_simulation.py`: Simulation script
- `Repressilator Oscillator.png`: Output plot showing time-course oscillations

## Dependencies

Install required libraries:

```bash
pip install tellurium matplotlib

## Overview

- **Language:** Python
- **Modeling Framework:** Tellurium (Antimony syntax)
- **Visualization:** Matplotlib
- **Simulation Time:** 0 to 500 units, with 1000 points

Oscillations arise due to delayed negative feedback between the three repressors.


## Usage

Run the script:

```
python repressilator_simulation.py
```

This will:
- Simulate the circuit over 500 time units
- Plot the protein concentrations
- Save the plot as a high-resolution PNG

## Author

Aditya Raj (Kuro)  
GitHub: https://github.com/blackbox-genesis
