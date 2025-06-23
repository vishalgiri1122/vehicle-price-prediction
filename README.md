# Vehicle Price Prediction 

This machine learning project predicts the sale prices of used heavy-duty vehicles (e.g., bulldozers) using historical auction data.

##  Project Structure

- `end-to-end-bulldozer-price-regression.ipynb`: Main notebook containing EDA, preprocessing, training, and evaluation.
- `data/`: Contains training and validation CSV files (large files excluded from Git).
- `env/`: Local virtual environment (ignored in `.gitignore`).

##  Dataset Source

The data used in this project is from the [**Blue Book for Bulldozers** competition on Kaggle](https://www.kaggle.com/competitions/bluebook-for-bulldozers/overview).

##  Tools Used

- Python 
- pandas, NumPy, matplotlib
- scikit-learn
- Jupyter Notebook

##  Model Highlights

- End-to-end pipeline from raw data to price prediction.
- Preprocessing: missing values, categorical encoding, and date feature extraction.
- Model: RandomForestRegressor with hyperparameter tuning.
- Evaluation metrics: MAE, R² score.

##  How to Run

```bash
# Clone the repo
git clone https://github.com/vishalgiri1122/vehicle-price-prediction.git
cd vehicle-price-prediction

# (Optional) Create a virtual environment
python -m venv env
source env/bin/activate  # or env\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt

# Open the notebook
jupyter notebook
