# Kresh Uttam Vikalp

I built this full-stack crop recommendation and yield prediction platform to empower farmers and agricultural stakeholders with data-driven insights. The application leverages machine learning models to provide personalized crop, yield, and fertilizer recommendations based on user input and historical data.

---

## 🚀 Features
- **Crop Recommendation:** I suggest the best crops to grow based on soil and weather data.
- **Yield Prediction:** The app predicts expected crop yield and market price for selected crops and districts.
- **Fertilizer Recommendation:** I recommend optimal fertilizers based on land and crop details.
- **Crop Registration:** You can register your crops for better market visibility.
- **Statistics & Visualization:** I provide production vs. demand graphs and other agricultural statistics.
- **Chat Support:** Integrated chat interface for user assistance.

---

## 🛠️ Tech Stack
- **Frontend:** React Native (TypeScript), Expo, Axios
- **Backend:** Flask (Python), Flask-CORS, REST API
- **Machine Learning:** scikit-learn (Decision Trees, Linear Regression), Pandas, Pickle
- **Visualization:** Matplotlib

---

## 📦 Project Structure
```
krshaknew2-main/
  ├── app_run_flask.py           # Flask backend entry point
  ├── codes/                    # ML model training scripts
  ├── datasets/                 # CSV datasets for training/inference
  ├── pkl_files/                # Pre-trained ML model files
  ├── user_entry/               # User crop registration logs
  ├── frontend/                 # React Native (Expo) frontend
  └── requirements.txt          # Python dependencies
```

---

## ⚙️ Setup Instructions

### 1. Backend (Flask/Python)
```sh
cd krshaknew2-main
pip install -r requirements.txt
python app_run_flask.py
```

### 2. Frontend (Expo/React Native)
```sh
cd frontend
npm install
npx expo start
```

- The backend runs on `http://127.0.0.1:5000` by default.
- The frontend can be accessed via Expo Go app or web browser.

---

## 🧠 Machine Learning Models
- **Crop Recommendation:** Decision Tree Classifier
- **Fertilizer Recommendation:** Decision Tree Classifier
- **Yield & Price Prediction:** Linear Regression (per crop)
- **District Demand Prediction:** Linear Regression (per crop)
- Models are trained on historical datasets and stored as `.pkl` files for fast inference.

---

## 📈 Usage
1. **Start the backend and frontend as described above.**
2. **Navigate through the app to:**
   - Register crops
   - Get crop, yield, and fertilizer recommendations
   - View statistics and predictions
3. **New user data is logged for future model retraining (not used in real-time predictions).**

---

## 🤝 Contributing
1. Fork the repository
2. Create your feature branch (`git checkout -b feature/YourFeature`)
3. Commit your changes (`git commit -m 'Add some feature'`)
4. Push to the branch (`git push origin feature/YourFeature`)
5. Open a Pull Request

---

## 📄 License
This project is for educational and demonstration purposes. If you wish to use it commercially, please contact me.

---

## 🙋‍♂️ Contact
If you have any questions or suggestions, please open an issue or contact me through my [GitHub profile](https://github.com/ReshwanthKudikala). 
