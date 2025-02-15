# Mentor Matching Platform

## 📌 Overview
The **Mentor Matching Platform** is an AI-powered web application designed to streamline the mentor-mentee pairing process. It uses a similarity-based matching algorithm to connect club members with suitable mentors based on their project requirements, interests, and expertise.

## 🚀 Features
- **One-to-One and One-to-Many Matching:** Users can choose between single mentor-mentee pairings or group mentor assignments.
- **Streamlit Frontend:** Interactive forms for data input and displaying match results.
- **AI-Driven Matching Algorithm:** Utilizes similarity scoring and NLP-based techniques for better mentor-mentee alignment.
- **Database Integration:** Uses SQLite or Pandas for efficient data storage and retrieval.
- **User-Friendly UI:** Simple and intuitive interface for seamless interaction.

## 🛠️ Technologies Used
- **Frontend:** Streamlit
- **Backend:** Python (Pandas, NumPy, SQLite)
- **NLP:** NLTK or TextBlob (for text-based profile matching)
- **Data Storage:** SQLite/Pandas

## 🏗️ Setup Instructions
### 1️⃣ Clone the Repository
```sh
git clone https://github.com/advika31/mentormatching.git
cd mentormatching
```

### 2️⃣ Install Dependencies
```sh
pip install -r requirements.txt
```

### 3️⃣ Run the Application
```sh
streamlit run app.py
```

## 📌 How It Works
1. Users fill out a form specifying their project details, skills, and preferences.
2. The matching algorithm computes similarity scores between mentees and available mentors.
3. The best-matched mentors are displayed, allowing users to finalize their selections.
4. The results are stored and can be retrieved for future reference.

## 🤝 Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request.

## 📬 Contact
For any queries or suggestions, reach out via [LinkedIn](www.linkedin.com/in/advika-singhal-ab97a7285) or open an issue on GitHub.
