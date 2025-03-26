Music Genre Clustering 🎵

OVERVIEW:

This project performs unsupervised clustering of music genres based on audio features such as tempo, loudness, energy, and danceability. Using K-Means clustering, the algorithm groups similar songs, allowing for music discovery and recommendation.

FEATURES:

✅ Load and preprocess a Spotify dataset

✅ Extract key audio features for clustering

✅ Normalize data using MinMaxScaler

✅ Cluster songs using K-Means

✅ Visualize clusters using Plotly 3D scatter plots

DATASET:

We use a dataset containing 2000+ songs with attributes like:

🎵 Beats Per Minute (BPM)

🔊 Loudness (dB)

⚡ Energy & Danceability

🎤 Speechiness & Acousticness


INSTALLATION:

1️⃣ Clone the Repository

git clone https://github.com/SVarunKrishna/Music-Genre-Clustering.git
cd Music-Genre-Clustering

2️⃣ Install Dependencies

pip install -r requirements.txt

3️⃣ Run the Jupyter Notebook

jupyter notebook clustering-music-genres.ipynb


USAGE:

Load your dataset (Spotify-2000.csv)

Run the data preprocessing steps

Apply K-Means clustering

Visualize genre clusters


TECHNOLOGIES USED:

🚀 Python

📊 Pandas, NumPy – Data processing

🧠 Scikit-Learn – Clustering

📈 Matplotlib, Seaborn, Plotly – Visualization

📂 Jupyter Notebook


RESULTS & VISUALIZATION:

📊 2D & 3D plots of clustered genres

📈 Insights into music patterns

📊 Interactive exploration of genre similarities


CONTRIBUTING:

Got ideas? Open an issue or pull request!

License

📝 This project is open-source under the MIT License.
