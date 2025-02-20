# 🎮 Hangman Game – Web Application

## 📌 Overview
The *Hangman Game* is a classic word-guessing game where players try to guess a hidden word by selecting letters within a limited number of attempts. This project is built using *HTML, CSS, JavaScript* for the frontend and *PHP* for the backend to handle user interactions and score tracking.

---

## 🚀 Features
- 📝 *Dynamic Word Selection* – Words are fetched from a server-side database.
- 🎨 *Interactive UI* – Smooth animations and visually engaging game elements.
- 🎯 *Score Tracking* – Keeps track of wins/losses using PHP & MySQL.
- 🔄 *Hint System* – Provides clues to help players guess the word.
- 🖥 *Responsive Design* – Works seamlessly on desktops, tablets, and mobile devices.

---

## 🛠 Tech Stack
| Technology | Purpose |
|------------|---------|
| *HTML, CSS* | Structure & styling of the game |
| *JavaScript* | Game logic & user interactions |
| *PHP* | Backend handling & database communication |
| *MySQL* | Storing words, scores, and user data |

---

## 📂 Project Structure
📁 hangman-game/ │── 📂 assets/ # Images, stylesheets, and sound files │── 📂 js/ # JavaScript game logic │── 📂 php/ # Backend PHP scripts │── 📂 db/ # Database scripts │── index.html # Main game page │── styles.css # CSS styles │── script.js # JavaScript file │── config.php # Database connection │── fetch_word.php # PHP script to fetch words from DB │── update_score.php # PHP script to store scores │── README.md # Project documentation

yaml
Copy
Edit

---

## 🔧 Installation & Setup
### 🔽 Prerequisites:
- PHP installed (>=7.4)
- MySQL Server installed (>=5.7)
- A local server (XAMPP/LAMP/WAMP)

### ▶ Steps to Run:
1. *Clone the repository:*
   ```bash
   git clone https://github.com/hangman-game.git
   cd hangman-game
Set up the database:

Open MySQL and create a database:
sql
Copy
Edit
CREATE DATABASE hangman;
Import the db/hangman.sql file into the database.
Update config.php with your database credentials.
Start the local server:

If using XAMPP, place the project in the htdocs/ folder.
Start Apache and MySQL from the XAMPP control panel.
Run the game:

http://localhost/hangman-game/
*🎮 How to Play*
1.A random word is selected, and blank spaces are shown.
2.Click on a letter to guess it.
3.If the letter is in the word, it appears in the blanks.
4.If the letter is incorrect, a part of the hangman is drawn.
5.Win by guessing all letters before the hangman is fully drawn
