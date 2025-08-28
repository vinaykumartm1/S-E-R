# Speech Emotion Recognition
---

## 🚀 About the Project

This project focuses on the development of a model for **Speech Emotion Recognition (SER)**. The main goal was to design and implement a model that can accurately recognize emotions conveyed through speech. The project uses a Long Short-Term Memory (LSTM) model, a type of recurrent neural network known for its ability to capture sequential dependencies in data. The model was trained on a dataset of pre-recorded speech samples to analyze temporal patterns and predict the underlying emotions.

### Features
- **Emotion Classification**: The model classifies speech into seven emotional categories:  
  *Angry, Disgust, Fear, Happy, Neutral, Sad, Pleasant Surprise*.

- **Feature Extraction**: Uses **Mel-frequency cepstral coefficients (MFCCs)** to capture the spectral characteristics of speech signals, which are highly effective for audio-based tasks.

- **Deep Learning Model**: Built with an **LSTM-based neural network** for the core classification task.

- **Dataset**: Trained on the [**Toronto Emotional Speech Set (TESS)**](https://www.kaggle.com/datasets/ejlok1/toronto-emotional-speech-set-tess),  
  which contains **2,940 audio clips** from North American English speakers.

## 🛠️ Getting Started

### Prerequisites

You will need to have Python and the necessary libraries installed. Based on the report, the following are likely required:

* Python 3.x
* `tensorflow` or `keras`
* `librosa`
* `seaborn`
* `matplotlib`

### Installation

1.  Clone the repository:
    ```bash
    git clone [https://github.com/vinaykumartm1/S-E-R.git]
    ```
2.  Navigate to the project directory:
    ```bash
    cd S-E-R
    ```

### Usage

The project follows a multi-stage approach for training and classification. The core steps involve:

1.  **Speech Acquisition:** Capturing or loading speech samples from the dataset.
2.  **Feature Extraction:** Transforming the raw audio data into meaningful features, such as MFCCs.
3.  **Training:** Training the LSTM model on the extracted features and their corresponding emotion labels.
4.  **Testing:** Evaluating the model's performance on unseen data to assess its accuracy.
5.  **Classification:** Using the trained model to predict the emotion label for new speech samples.

## 📈 Results

The trained model showed promising results, with training and validation accuracy increasing over 50 epochs. The model achieved a high accuracy of up to 95%.

## 🔮 Future Work

The project provides a solid foundation for future research and development in SER. Future work could focus on:

**Real-time Applications:** Integrating the model into real-time applications to allow for emotion recognition from live voice streams.
**Model Optimization:** Further enhancing the model's performance through techniques like hyperparameter tuning and data augmentation.

## 👨‍💻 Detail Report 
Detail work and reults present in the project report file.
