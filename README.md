A machine learning-based project that predicts future stock prices using historical market data and deep learning models. This project leverages data preprocessing, visualization, and predictive modeling to forecast price trends with improved accuracy.
git clone https://github.com/Anukriti-Srivastava/Stock-Market-Price-Prediction.git
cd Stock-Market-Price-Prediction
python3 -m venv venv
source venv/bin/activate   # (on Windows: venv\Scripts\activate)
pip install -r requirements.txt
DATA_API_KEY=your_api_key_here
STOCK_TICKER=GOOGL
python scripts/data_preprocess.py
python scripts/train_model.py
python scripts/evaluate.py
python app.py
