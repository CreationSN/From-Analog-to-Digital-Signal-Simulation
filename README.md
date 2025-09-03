# From-Analog-to-Digital-Signal-Simulation
Assigment of Mathematical Algorithms

Sampling Experiment (Nyquist Theorem Demo)

In this project, I did a project in MATLAB to see how sampling a 100 Hz sine wave works with different sampling rates.

What I Did ?
Made a smooth analog sine wave (100 Hz).

Sampled it at 150 Hz (below Nyquist), 200 Hz (at Nyquist), and 250 Hz (above Nyquist).

Plotted the samples and compared them with the original wave.

What I Saw

Fs = 150 Hz (< 200 Hz) → The digital signal does not match the analog wave.

Fs = 200 Hz (= 200 Hz) → The digital signal follows the analog wave, but not perfect.

Fs = 250 Hz (> 200 Hz) → The digital signal matches the analog wave very well.

Conclusion
I learned that to get a correct digital signal from an analog signal, the sampling rate must be more than 2 times the signal frequency.
