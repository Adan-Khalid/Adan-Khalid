<!-- Source for README.md in the special repo Adan-Khalid/Adan-Khalid (published as is; HTML comments do not show on GitHub). Update it after every /ship. No em dashes. No AI attribution. -->

# Adan Khalid

**Electrical Engineering, NUST CEME · Intelligent signal processing and autonomous systems**

I am building a portfolio of projects that turn signals into decisions, from biomedical and audio signals to radar, cameras and robots. Every project here uses real data or a clearly labelled simulation, compares against a baseline, states its limitations, and can be reproduced from the repository.

## Featured projects

### Track A: AI/ML and signal processing

| Project | What it does | Key result |
| --- | --- | --- |
| <img src="https://raw.githubusercontent.com/Adan-Khalid/ecg-quality-beat-detection/main/assets/thumb.png" width="160" alt="25 hours of wearable ECG coloured by predicted quality"><br>[ECG signal quality and beat detection](https://github.com/Adan-Khalid/ecg-quality-beat-detection) | Labels each 10 s of wearable ECG as clean, QRS-only or unusable on people the model never saw, with a Pan-Tompkins detector written from the 1985 paper | Quality macro-F1 0.77 vs 0.63 for a rule-based baseline (leave-one-subject-out); Pan-Tompkins Se 99.68 %, +P 99.47 % on MIT-BIH |

<!-- Track B: add this section when the first Track B project ships.
### Track B: Robotics and radar

| Project | What it does | Key result |
| --- | --- | --- |
| <img src="https://raw.githubusercontent.com/Adan-Khalid/<repo>/main/assets/thumb.png" width="160" alt="<alt>"><br>[<Project name>](https://github.com/Adan-Khalid/<repo>) | <one line> | <one number vs baseline> |
-->

## Tools used in these projects

Python · NumPy · SciPy · scikit-learn · PyTorch · WFDB · Streamlit · Git and GitHub Actions

<!-- Only list a tool once a shipped repo shows real use of it. -->

## Next up

Automotive radar interference mitigation: FMCW radar simulation, interference suppression and CFAR detection.
