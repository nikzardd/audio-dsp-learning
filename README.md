# audio-dsp-learning
A hands-on learning repository documenting my journey into **audio digital signal processing (DSP)** with Python.

I'm building this repository as I learn the mathematical foundations of audio, experiment with signals, and gradually apply those concepts to real recordings and music technology projects.

## About this repository
This is a learning lab, not a claim of expertise. Each topic should include:
- a short explanation in my own words;
- code that can be run and inspected;
- plots or measurements where useful;
- observations, limitations, and questions that remain.

## Topics

| Folder | Focus | Status |
|---|---|---|
| `01_python_audio_basics/` | Arrays, sampling, loading audio, plotting waveforms | In progress |
| `02_sampling_and_sinusoids/` | Sample rate, frequency, amplitude, phase | Planned |
| `03_dft_fft/` | DFT, FFT, frequency bins, magnitude and phase | In progress |
| `04_spectral_leakage_windows/` | Leakage, window functions, zero-padding | Planned |
| `05_stft_spectrograms/` | Frames, hop size, STFT and spectrograms | Planned |
| `06_filters_and_eq/` | Filtering, frequency response, EQ concepts | Planned |
| `07_audio_measurements/` | RMS, peak, dBFS, loudness concepts | Planned |
| `08_mini_projects/` | Small end-to-end audio tools | Planned |

## Getting started

Python 3.10 or newer is recommended.

```bash
python -m venv .venv
```

Activate it:
- Windows PowerShell: `.venv\\Scripts\\Activate.ps1`
- macOS/Linux: `source .venv/bin/activate`

Install dependencies:

```bash
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Run the first experiment from the repository root:

```bash
python 01_python_audio_basics/plot_sine_wave.py
```

For notebooks, run `jupyter lab`.

## Suggested workflow
1. Read the explanation before running the code.
2. Run the example unchanged.
3. Change one parameter at a time.
4. Predict what will happen before running it.
5. Record the observation and explain why it happened.
6. Commit meaningful progress to Git.

## Reproducibility and audio files
- Prefer synthetic signals or audio you created, own, or have permission to use.
- Do not commit copyrighted commercial recordings unless you have permission to redistribute them.
- Do not commit private recordings, personal information, credentials, or API keys.
- Keep local audio in `data/local/`; it is ignored by Git.
- Record important settings such as sample rate, FFT size, window, hop size, and normalization method.

## Current learning goals
- Understand sampling and sinusoidal signals.
- Explain the DFT and FFT, including frequency bins and magnitude.
- Understand spectral leakage, windowing, and the STFT.
- Use Python, NumPy, SciPy, and Matplotlib to inspect audio.
- Build small, understandable audio-analysis tools.
- Connect DSP concepts to practical music production and, where appropriate, folk-music research.

## About me
I'm a musician and singer-songwriter interested in the intersection of music, technology, audio DSP, and cultural heritage. I'm using this repository to document my technical learning in public, one experiment at a time.
 
**Instagram:** [@nikzard](https://www.instagram.com/nikzard/)
**LinkedIn:** https://www.linkedin.com/in/nikzard/

---
*Learning in public. Explanations and code will improve as my understanding develops.*
