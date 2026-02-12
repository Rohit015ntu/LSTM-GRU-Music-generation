# Deep Learning Music Generation 🎵

This project explores music generation using Deep Learning techniques, specifically **Long Short-Term Memory (LSTM)** and **Gated Recurrent Units (GRU)** networks. The models are trained on a dataset of MIDI files to learn musical patterns and generate new, original musical sequences.

## 🚀 Features
- **Data Preprocessing**: Converts MIDI files into note sequences using `music21`.
- **Model Architectures**:
  - **LSTM**: Captures long-term dependencies in musical sequences.
  - **GRU**: A more efficient variant of RNNs for sequence modeling.
- **Music Generation**: Generates new notes based on a seed sequence.
- **MIDI Reconstruction**: Converts generated note sequences back into playable MIDI files.

## 🛠️ Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Rohit015ntu/LSTM-GRU-Music-generation.git
   cd LSTM-GRU-Music-generation
📂 Usage
Prepare Data:

Place your .mid or .midi files into the data/ directory.

Note: Ensure the dataset directory path in the notebook matches your local folder structure.

Run the Notebook:

Open Music_Generation.ipynb in Jupyter Notebook or JupyterLab.

Run the cells to preprocess data, train the models, and generate music.

Generate Music:

After training, the models will generate MIDI files (e.g., LSTM_generated_music.mid) saved in the project directory.

🧠 Model Details
LSTM (Long Short-Term Memory)

Layers: 3 LSTM layers (256 units each) with Dropout (0.3) to prevent overfitting.

Optimizer: Adam

Loss Function: Categorical Crossentropy

GRU (Gated Recurrent Unit)

Layers: 3 GRU layers (256 units each) with Dropout (0.3).

Performance: Comparable to LSTM but often faster to train.

📊 Results
The notebook includes code to visualize and compare the training metrics (Loss) of both models.

📝 License
MIT
