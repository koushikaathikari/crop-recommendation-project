# crop-recommendation-project
A web-based tool that suggests the best crops to grow based on soil nutrients (N, P, K), temperature, humidity, pH, and rainfall. It uses FastAPI for backend processing and recommends crops by comparing input with dataset values using Euclidean distance.

## 🔍 Features

- Input-based crop recommendation using:
  - Nitrogen (N)
  - Phosphorus (P)
  - Potassium (K)
  - Temperature
  - Humidity
  - pH
  - Rainfall
- FastAPI-based backend
- Frontend built using Vite and Tailwind CSS
- Crop prediction logic using Euclidean distance on dataset

## 📂 Project Structure

```
crop-recommendation-project/
├── backend/
│   ├── main.py                # FastAPI backend logic
│   ├── crop.csv               # Dataset used for recommendation
│   ├── requirements.txt       # Backend dependencies
├── index.html                 # Entry point for frontend
├── package.json               # Frontend dependencies
├── tailwind.config.js         # Tailwind CSS config
├── vite.config.js             # Vite config
```

## 🚀 Getting Started

### Backend Setup

```bash
cd backend
pip install -r requirements.txt
uvicorn main:app --reload
```

### Frontend Setup

```bash
npm install
npm run dev
```

## 🧠 How It Works

The system calculates the Euclidean distance between the user's input and entries in the dataset to suggest the top 5 closest matching crops.

## 📌 Tech Stack

- FastAPI
- Pandas, NumPy
- Vite + Tailwind CSS
- JavaScript, HTML

## 📬 Contact

For feedback or contributions, feel free to reach out!
