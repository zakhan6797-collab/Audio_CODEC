Bio-Inspired Audio Codec using Spiking Neural Networks (SNN)

---

📘 Overview

This project presents the design and development of a bio-inspired audio codec that leverages Spiking Neural Networks (SNN) to reconstruct stereo audio from spike-based data.
The codec mimics the behavior of biological neurons to encode and decode audio information — offering a neuromorphic approach to digital audio signal processing.

The project uses the NEST Simulator, NumPy, Matplotlib, and Pydub to simulate spiking neuron behavior, process sound files, and reconstruct waveforms from spike trains.


---

🎯 Objectives

Develop an audio codec inspired by the human auditory system.

Simulate neuron spiking behavior under varying input currents using NEST.

Encode audio amplitudes into spike currents and reconstruct them back into audio.

Compare and analyze original vs reconstructed waveforms.



---

⚙️ Key Features

🧩 Spike Simulation: Simulates neuron firing rates as a function of input current.

🎵 Audio Preprocessing: Converts .mp3 to .wav and extracts sampling information.

🔁 Spike Encoding & Decoding: Converts audio amplitudes into spike trains and reconstructs the original signal.

🧠 SNN Simulation: Processes stereo sound using NEST neurons and generates spike data.

📊 Visualization: Generates amplitude plots, raster plots, and current-spike relationships.



---

🧩 Technologies Used

Component	Purpose

Python	Core programming language
NEST Simulator	Simulation of Spiking Neural Networks
NumPy	Numerical computations and data handling
Matplotlib	Visualization of signals and spike activity
Pydub	Audio conversion and preprocessing
SciPy	Signal reading and writing (WAV)
h5py	Storing large spike datasets in HDF5 format



---

🧠 Project Structure

📁 BioInspired_Audio_Codec_SNN/
│
├── results/ — Output data (spike results, npy files, HDF5)
├── Sound/ — Input sound files (.mp3 / .wav)
├── 1_neuron_spike_sim.py — Simulates neuron spiking for varying input currents
├── 2_audio_processing.py — Handles audio conversion and visualization
├── 3_current_retrieval.py — Retrieves current values from stored spike data
├── 4_encoding_decoding.py — Encodes/decodes values into spike currents
├── 5_snn_simulation.py — Runs SNN simulation on sound data
├── analysis.ipynb — Full notebook version with plots and outputs
└── README.md — Documentation (this file)


---

🚀 How to Run

1️⃣ Install Dependencies

Make sure you have Python 3.8+ installed, then run:
pip install numpy matplotlib pydub nest-ml scipy h5py

2️⃣ Prepare Audio Data

Place an .mp3 file inside the Sound/ folder (e.g., Song.mp3).

3️⃣ Run Step-by-Step Scripts

python 1_neuron_spike_sim.py
python 2_audio_processing.py
python 3_current_retrieval.py
python 4_encoding_decoding.py
python 5_snn_simulation.py

4️⃣ Output Files

🎧 Reconstructed .wav audio file

📈 Spike data (.npy / .h5)

🖼️ Plots comparing original and reconstructed signals



---

📊 Results Summary

✅ Successful reconstruction of stereo audio from spike data.

⚡ Spike generation matched expected neuronal firing patterns.

🧬 Demonstrated effective bio-inspired encoding/decoding mechanism for digital sound.



---

🔬 Future Work

Introduce Spike-Timing Dependent Plasticity (STDP) for adaptive encoding.

Develop real-time audio streaming using neuromorphic hardware.

Conduct signal-to-noise ratio (SNR) and subjective listening tests for fidelity evaluation.



---

📚 References

Gewaltig, M.-O., & Diesmann, M. (2007). NEST (NEural Simulation Tool). Scholarpedia, 2(4):1430.

Maass, W. (1997). Networks of spiking neurons: The third generation of neural network models. Neural Networks.

Dayan, P., & Abbott, L. F. (2001). Theoretical Neuroscience: Computational and Mathematical Modeling of Neural Systems.



---

🧑‍💻 Author

Mohd. Zafar A. A. Khan
📧 zakhan6797@gmail.com
🔗 https://www.linkedin.com/in/zafar-khan-17b700b9
📍 India
