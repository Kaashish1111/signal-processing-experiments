
# Signal Processing Experiments

A collection of Digital Signal Processing (DSP) experiments and exploratory notebooks focused on understanding signals, frequency analysis, filtering, and computational sensing using Python.

This repository documents my learning journey through DSP fundamentals while exploring applications connected to machine learning, human-centered AI, eye tracking, cognitive computing, and behavioral sensing systems.

---

## Topics Explored

* Signal generation and visualization
* Frequency, amplitude, and sampling concepts
* Sine and cosine signal synthesis
* Multi-frequency compound signals
* Spectrum analysis using FFT
* Harmonic structure and timbre analysis
* High-pass, low-pass, and band-stop filtering
* Audio stretching and waveform manipulation
* Practical DSP experimentation using Python and Colab

---

## Chapter 1 Exercises

### Exercise 1.2 — Spectrum Analysis and Filtering

* Downloaded and analyzed real-world audio samples
* Selected stable-pitch segments for spectral analysis
* Explored the relationship between timbre and harmonic structure
* Applied:

  * high-pass filters
  * low-pass filters
  * band-stop filters
* Reconstructed filtered signals and analyzed perceptual audio changes

### Exercise 1.3 — Compound Signal Synthesis

* Generated compound signals using:

  * `SinSignal`
  * `CosSignal`
* Combined multiple frequency components
* Computed and visualized frequency spectra
* Explored the effects of non-harmonic frequency components on signal behavior

### Exercise 1.4 — Time Stretching

Implemented a lightweight `stretch()` function to:

* speed up audio
* slow down audio

by modifying:

* timestamps (`ts`)
* frame rate (`framerate`)

---

## Motivation

Recently, I became interested in how signal processing connects to intelligent systems and behavioral AI.

Research areas such as:

* eye tracking
* pupillometry
* EEG analysis
* physiological sensing
* cognitive state estimation

all rely heavily on signal representation and processing.

This repository is part of my effort to build stronger foundations in DSP while exploring applications in machine learning and human-centered AI.

---

## Tools & Libraries

* Python
* NumPy
* Matplotlib
* SciPy
* Google Colab

---

## Future Directions

Planned future explorations include:

* Fourier Transform analysis
* audio feature extraction
* EEG signal processing
* eye movement signal analysis
* DSP for cognitive and biomedical AI systems
* machine learning on time series data
