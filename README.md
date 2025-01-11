# 🎵 Audio Data Augmentation Tool

This project provides a **Python-based audio augmentation tool** that generates diverse variations of `.wav` files for machine learning datasets or audio processing tasks. It employs the **Librosa** library and other tools to enhance audio data by applying transformations like adding noise, pitch shifting, time-stretching, speed alterations, and flipping audio.**This project is a part of my bigger project 'Sound Event Localization' I am currently working on**.

## ✨ Features
- **Noise Addition**: Introduces controlled levels of Gaussian noise to audio files.
- **Pitch Shifting**: Modifies the pitch by varying the number of semitone steps.
- **Time Stretching**: Resamples audio to simulate faster or slower playback.
- **Speed Changes**: Adjusts the playback speed with different factors.
- **Audio Flipping**: Reverses the waveform for additional augmentation.

## 🛠️ Technologies Used
- **Python**
- **Librosa**: For audio loading and augmentation.
- **Resampy**: For high-quality audio resampling.
- **Scipy**: For saving augmented audio in `.wav` format.




## 🛠️ How to Use (Kaggle Edition)

### 1️⃣ Clone or Fork the Notebook
- Open the Kaggle Notebook containing this script.  
- Fork the notebook to your Kaggle workspace.

### 2️⃣ Prepare the Input Directory
- Upload your `.wav` files to a custom dataset or use an existing Kaggle dataset.
- Update the `input_dir` variable in the notebook to point to your dataset directory.  
  Example:  
  ```python
  input_dir = "/kaggle/input/your-audio-dataset"
  
### 3️⃣ Run the Notebook
Execute all cells in the notebook.
Augmented files will be saved in the output/augmented_audio directory.

## 🎛️ Customization
Modify Augmentation Parameters
Noise Levels: Adjust levels in noise_levels (e.g., [0.01, 0.02]).
Time Stretch Rates: Change rates in time_stretch_rates (e.g., [0.8, 1.2]).
Pitch Shifting Steps: Customize steps in pitch_shift_steps (e.g., [-2, 0, 2]).
Speed Factors: Define factors in speed_factors (e.g., [0.5, 1.5]).

## 🔥 Applications
This tool can be used for:

Machine Learning: Generate diverse audio datasets for training robust models.
Speech Processing: Enhance datasets with varied transformations.
Creative Projects: Experiment with new and unique audio variations.
### Developed by-Dheer N Raijada
