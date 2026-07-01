# HMM Activity Recognition

Human activity recognition using Hidden Markov Models trained on smartphone 
sensor data (accelerometer + gyroscope).

## Project Overview

This project collects real motion data from a smartphone and uses a Hidden 
Markov Model (HMM) to classify four human activities: walking, standing, 
jumping, and still.

## Repository Structure

hmm-activity-recognition/

data/

walking_01/

walking_02/

...

standing_01/

...

still_01/

...

jumping_01/

...

notebook.ipynb

## Activities Recorded

| Activity | Clips | Duration per clip |
|---|---|---|
| Walking | 13 | 8–10 seconds |
| Standing | 13 | 8–10 seconds |
| Still | 13 | 8–10 seconds |
| Jumping | 13 | 8–10 seconds |

## Sensors Used

- Accelerometer (x, y, z)
- Gyroscope (x, y, z)
- Sampling rate: ~100 Hz (Sensor Logger app)

## Tools

- Python, hmmlearn, numpy, pandas, sklearn, seaborn
- Google Colab
- Sensor Logger (Android/iOS)

## Author

Josephine Duba Kanu

report.pdf

README.md
