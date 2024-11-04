# Comprehensive Voice Analysis using Signal Processing Techniques

### Author: Neelima Pulipati

---

## Overview

This project implements a comprehensive voice analysis system designed to process and analyze audio signals through various signal processing techniques. The analysis includes audio enhancement, pitch detection, formant extraction, and cepstral analysis, using libraries such as NumPy, SciPy, and librosa. The results provide insights into the acoustic characteristics of Hindi vowels.

## Key Features

1. **Audio Signal Enhancement**: 
   - Converts stereo signals to mono, normalizes the audio, removes DC bias, and applies an emphasis filter.
   - Uses a speech-optimized bandpass filter (50Hz–10000Hz) for clearer signal quality.

2. **Audio Format Transformation**:
   - Converts audio files from M4A to WAV format and standardizes parameters for further analysis.

3. **Spectrogram Visualization**:
   - Generates narrow-band and wide-band spectrograms to visualize the time-frequency characteristics of the audio signals.

4. **Pitch Analysis**:
   - Calculates mean and median pitch using the Average Magnitude Difference (AMD) method.
   - Visualizes pitch to provide insights into the fundamental frequency.

5. **Formant Extraction**:
   - Extracts the first three formants (F1, F2, F3) using Linear Predictive Coding (LPC) analysis.

6. **Cepstral Analysis**:
   - Conducts cepstral analysis to estimate pitch and understand voice periodicities.

## Results

The system analyzed three Hindi vowel sounds (`aa`, `ii`, `uu`) and extracted relevant parameters such as pitch and formant frequencies. The findings, including mean pitch, median pitch, and formant values, are detailed in the results section.

## Conclusion

This project provides a structured approach to voice analysis that can support further research in speech processing. The system effectively enhances audio quality, visualizes time-frequency characteristics, and extracts significant acoustic features.

## Repository

The full code and resources are available at [GitHub Repository](https://github.com/Neelima-Pulipati/Speech-Signal-Processing.git).

---

### Running the Code
Add input from Audio Files folder. 
Change the lines in the code where the audio file names are written as per input. 
1. Clone the repository:

    ```bash
    git clone https://github.com/Neelima-Pulipati/Speech-Signal-Processing.git
    cd Speech-Signal-Processing
    ```

2. Install the necessary dependencies:

    ```bash
    pip install numpy scipy librosa matplotlib
    ```

3. Run the analysis on the sample audio files:

    ```python
    run Code.ipynb
    ```
## Contact

Reach out to neelimapulipati13@gmail.com

---




