# ⚽ Fußball Wettanalyse – Football Match Prediction Dashboard

An interactive **Streamlit web app** for analyzing football (soccer) match statistics and predicting match outcomes using **Poisson probability models**.  
This tool helps analysts and fans explore team performance metrics, expected goals, and win/draw/loss probabilities — all in a sleek and visual interface.

---

## 🌟 Features

- 🧮 **Poisson-based match prediction** – estimate win, draw, and loss probabilities  
- 📈 **Interactive visualizations** using Matplotlib and Seaborn  
- 📊 **Dynamic data filtering** by league, team, and date  
- 🌐 **Live data fetching** (via API or CSV upload)  
- 💡 **Custom-styled Streamlit UI** with clean layout and color-coded metrics  
- 📅 **Historical and upcoming match insights**

---

## 🚀 Quick Start

### 1️⃣ Clone the Repository
 git clone https://github.com/yourusername/football-analysis.git
 cd football-analysis 

### 2️⃣ Install Requirements
Make sure you have Python ≥ 3.9 and install the dependencies:
pip install -r requirements.txt

### 3️⃣ Run the Streamlit App
streamlit run Football_analysis.py
Then open your browser at http://localhost:8501


## 🧠 How It Works
The app uses Poisson distribution modeling to estimate the probability of different match outcomes based on each team’s scoring rates.

1. Data Collection:
Pulls or loads match data (e.g. from APIs or local CSVs).

2. Statistical Analysis:
Calculates expected goals (xG), attack and defense strengths.

3. Poisson Simulation:
Generates outcome probabilities (Home Win, Draw, Away Win).

4. Visualization:
Displays results with interactive charts and metrics in Streamlit.


## 📂 Project Structure

- Football_analysis.py      || Main Streamlit app
- requirements.txt          || Dependencies
- data/                     || Optional data folder for CSVs
- README.md                 || Project documentation


## 🧩 Dependencies

- streamlit
- pandas
- numpy
- matplotlib
- seaborn
- scipy
- requests

Install them manually if needed:

pip install streamlit pandas numpy matplotlib seaborn scipy requests

## 🎨 UI Preview

<img width="1417" height="613" alt="Bildschirmfoto 2025-10-30 um 10 40 50" src="https://github.com/user-attachments/assets/bd2e1c51-6370-4015-9b9f-37638dcdafce" />

<img width="1154" height="868" alt="Bildschirmfoto 2025-10-30 um 10 40 32" src="https://github.com/user-attachments/assets/47a96355-9b8e-4bee-a844-cd13482bff75" />


## 🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to open a Pull Request or report a Bug.


## 🧾 License
This project is licensed under the MIT License – see the LICENSE file for details.

## ❤️ Acknowledgments
Data sources: football-data.org and FiveThirtyEight

Visualization style inspired by Seaborn & Streamlit examples

Developed with passion for the beautiful game ⚽

## 👨‍💻 Author
Lukas Fichtner
