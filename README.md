# Localization of Signals

This project is being conducted under the guidance of **Prof. Rajesh M. Hegde**, Department of Electrical Engineering, IIT Kanpur. The work focuses on deep learning approaches for signal classification using image-based inputs and is currently expanding into multilingual audio processing through Transformer-based models and sound source separation.

---

## Objectives

- Implement and compare deep learning architectures (**DNN**, **CNN**, **RNN**, **CRNN**) for classification of image-based signal data.
- Analyze spatial (**CNN**) vs. temporal (**RNN**) feature learning, and evaluate hybrid architectures (**CRNN**).
- Visualize training performance across models using accuracy/loss curves.
- **[Ongoing]** Explore Transformer-based models for sequence-to-sequence translation of multilingual audio.
- **[Upcoming]** Begin implementing sound source separation for multi-speaker scenarios, with plans to support downstream translation and localization tasks.

---

## Dataset Overview

### Image-Based Signal Data
- **MNIST**: Handwritten digit classification as a base task.
- **Synthetic Sequence Data**: Custom-generated datasets for spatio-temporal pattern learning.

### Audio Data (Planned)
- Real-world multilingual audio clips to be used for training translation and separation models.

---

## Models Implemented

| Model | Test Accuracy (%) |
|-------|-------------------|
| DNN   | 96.95             |
| CNN   | 98.12             |
| RNN   | 96.48             |
| CRNN  | 97.73             |

- Implemented using **TensorFlow** and **Keras**
- Trained and validated using **Google Colab**
- Performance analyzed through **epoch-wise training/validation accuracy and loss plots**

---

## Performance Insights

- All models demonstrated consistent classification accuracy (~97%)
- **CRNN** showed superior ability to model combined spatial and temporal features
- Accuracy and loss curves were plotted for each model to monitor convergence and overfitting

---

## Ongoing Work

- Developing **Transformer-based models** for sequence-to-sequence translation of multilingual audio
- Preparing datasets involving **paired audio-text inputs**
- Integrating **source separation models** to isolate individual voices from multi-speaker recordings
- **End Goal**: Combine translation and localization for real-time audio understanding

---

## Technologies Used

- **Programming**: Python 3.9+
- **Frameworks**: TensorFlow, Keras
- **Visualization**: Matplotlib, Seaborn
- **Data Handling**: NumPy, Pandas
- **Development Environment**: Google Colab

---

## Future Work

- Implement end-to-end pipeline for:
  - Voice separation
  - Individual speaker translation
  - Spatial localization
- Optimize models for real-time or low-latency inference
- Explore applications in **surveillance**, **assistive communication**, and **emergency systems**

---

## Results Summary

- All four models (**DNN, CNN, RNN, CRNN**) achieved approximately **97% accuracy** on classification tasks
- **CRNN** outperformed others in scenarios requiring spatio-temporal learning
- Training dynamics were thoroughly analyzed through visualizations

---



