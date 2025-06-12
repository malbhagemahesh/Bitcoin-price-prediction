# 🪙 Bitcoin Price Prediction using RNN-LSTM

This project demonstrates how to predict future Bitcoin prices using Recurrent Neural Networks (RNN) and Long Short-Term Memory (LSTM) models — popular deep learning architectures for time series forecasting.

---

## 📊 Dataset

We used historical Bitcoin price data from:
> 📈 [Kaggle: Bitcoin Historical Data by mczielinski](https://www.kaggle.com/mczielinski/bitcoin-historical-data)

Missing data was scraped using **Selenium**, and the complete set is available in `bitcoinunix.csv`.

---

## 📁 Project Structure

📦 Bitcoin-price-prediction/
┣ 📂 img/ # GIFs/Visuals of model architecture
┣ 📂 model/ # Trained RNN/LSTM models (ignored from pushes)
┣ 📄 bitcoin_price_predict_cleaned.ipynb # Main analysis and model notebook
┣ 📄 extract_data_cleaned.ipynb # Web scraping script
┣ 📄 bitcoinunix.csv # Cleaned/scraped dataset
┣ 📄 bitcoincharts.txt # Original data file
┣ 📄 requirements.txt # Python dependencies
┣ 📄 .gitignore # File exclusions
┗ 📄 README.md # Project overview

---

## 🛠️ Tools & Libraries Used

- Python 3.x
- NumPy, Pandas
- Matplotlib, Seaborn
- TensorFlow / Keras
- Selenium

---

## 🧠 Key Learnings

- Time series forecasting with LSTM
- Handling missing data using automation
- Training and evaluating RNN-based models
- Visualizing deep learning predictions

---

## 🙏 Credits

> This project is inspired by a hands-on assignment from the **DevTown Data Science Training Program**.  
> Implementation and refinement by [@malbhagemahesh](https://github.com/malbhagemahesh)

---

## 🚀 How to Run

```bash
git clone https://github.com/malbhagemahesh/Bitcoin-price-prediction.git
cd Bitcoin-price-prediction
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
jupyter notebook

