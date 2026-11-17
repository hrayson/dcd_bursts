# Childhood beta bursts and motor skill

Simulation and analysis code for the study of sensorimotor beta-burst waveforms and their relationship to motor skill in childhood.

## Paper and data

Rayson, H., Gerson, S. A., Keating, J., Jones, C. R. G., Purcell, C., Bonaiuto, J. J., & Vanderwert, R. E. (2026). [Functional heterogeneity of beta bursts in childhood reveals a dimensional neural signature of motor skill](https://doi.org/10.1162/IMAG.a.1376). *Imaging Neuroscience*.

- [Study dataset on OSF](https://osf.io/vnup9/)
- [Canonical analysis repository](https://github.com/danclab/dcd_bursts)
- [Preprint](https://doi.org/10.1101/2025.09.29.679222)

## Code

- [`preprocessing/`](preprocessing/) contains the MATLAB and Python EEG preprocessing scripts.
- The numbered `analysis_*.ipynb` notebooks cover preprocessing summaries, power spectra, burst extraction, lagged Hilbert autocoherence, waveform analyses and connectivity.
- [`analyze_beta_power.R`](analyze_beta_power.R) and [`analyze_pc_rates.R`](analyze_pc_rates.R) contain the statistical analyses of beta power and waveform component rates.

Set the dataset and output paths before running the scripts or notebooks. See [LICENSE](LICENSE) for the code licence.
