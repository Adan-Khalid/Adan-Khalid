# Adan Khalid

Electrical Engineering student at NUST CEME, Pakistan. I work on signal processing and machine learning: taking noisy real-world signals such as ECG, audio, radar and sensor data, and building systems that know when those signals can be trusted.

I like projects that can be checked: real data, a baseline to beat, honest limitations, and code that reproduces every result.

## Projects

### Radar

| Project | What it does | Result |
| --- | --- | --- |
| <img src="https://raw.githubusercontent.com/Adan-Khalid/radar-waveform-design/main/assets/social-preview.png" width="160" alt="Chart of detection loss against ADC bits for three code lengths, beside the project title"><br>[Radar Waveform Design and Matched Filtering: LFM, Phase-Coded and OFDM Pulses with Low-Bit ADC Analysis](https://github.com/Adan-Khalid/radar-waveform-design) | Compares five radar pulses at equal bandwidth and duration (sidelobes, Doppler tolerance, sidelobe filters and their SNR cost) and measures what a 1 to 4-bit ADC costs in detection, by Monte Carlo checked against theory | 3 bits cost 0.17 dB and 1 bit 2.34 dB of detection SNR (theory 0.17 and 1.96 dB); with a 13-chip code, 1 bit costs 5.4 dB |
| <img src="https://raw.githubusercontent.com/Adan-Khalid/radar-perception-tracking/main/assets/social-preview.png" width="160" alt="Radar bird's-eye view with two tracks following a pedestrian and a cyclist at their labelled boxes"><br>[Pedestrians, cyclists and cars from one radar chip](https://github.com/Adan-Khalid/radar-perception-tracking) | Turns raw 77 GHz samples from a TI radar chip into tracked, classified road users: range, Doppler and angle FFTs, CFAR detection, a Kalman tracker that uses radial speed, and a per-track classifier | On a recording day held out until the end: identity kept over time (IDF1) 0.48 vs 0.33 for a nearest-neighbour baseline; right class for 15 of 18 tracks |

### Biomedical signals

| Project | What it does | Result |
| --- | --- | --- |
| <img src="https://raw.githubusercontent.com/Adan-Khalid/ecg-quality-beat-detection/main/assets/thumb.png" width="160" alt="25 hours of wearable ECG coloured by predicted quality"><br>[ECG signal quality and beat detection](https://github.com/Adan-Khalid/ecg-quality-beat-detection) | Labels each 10 s of wearable ECG as clean, QRS-only or unusable on people the model never saw, with a Pan-Tompkins detector written from the 1985 paper | Quality macro-F1 0.77 vs 0.63 for a rule-based baseline (leave-one-subject-out); Pan-Tompkins Se 99.68 %, +P 99.47 % on MIT-BIH |

## Tools

Python · NumPy · SciPy · Matplotlib · scikit-learn · PyTorch · Stone Soup · Rerun · WFDB · Streamlit · pytest · Git and GitHub Actions

## Up next

Interference mitigation for automotive FMCW radar: simulating interference between radars, suppressing it, and measuring the effect on CFAR detection.
