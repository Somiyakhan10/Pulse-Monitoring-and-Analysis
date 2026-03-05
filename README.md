# Pulse Signal Analysis using Python

## Project Overview
This project performs a basic analysis of pulse signals during different activities (rest, walking, running) using Python. The analysis includes:

- Plotting the raw pulse signal
- Calculating the pulse change rate (velocity)
- Smoothing the pulse signal to observe trends

## Dataset
The dataset `exercise.csv` contains the following columns:

| Column | Description |
|--------|-------------|
| id     | Participant ID |
| diet   | Type of diet (low fat / no fat) |
| pulse  | Pulse rate (beats per minute) |
| time   | Measurement time |
| kind   | Activity type (rest, walking, running) |

**Note:** The dataset must be uploaded before running the code.

## Libraries Used
- `pandas` – for data manipulation
- `numpy` – for numerical operations
- `matplotlib` – for plotting
- `google.colab.files` – for uploading datasets in Colab

