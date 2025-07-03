# 🧠 QuizApp – Python GUI Trivia Game

This is an interactive **Quiz Application** built with Python using the **Tkinter** GUI toolkit. The app displays a series of true/false questions and provides instant feedback. It’s designed to demonstrate object-oriented programming and GUI development with clean modularity.

---

## 🎯 Features

- ✅ GUI built with Tkinter
- ✅ True/False quiz interface
- ✅ Score tracking and progress display
- ✅ Clean modular code with OOP structure
- ✅ Visual feedback using image buttons
- ✅ Data abstraction with JSON/question API (via `data.py`)

---

## 🧱 Project Structure

QuizApp-main/
├── quiz_gui/
│ ├── main.py # App entry point
│ ├── ui.py # GUI setup and event handling
│ ├── quiz_brain.py # Quiz logic and state tracking
│ ├── question_model.py # Question object model
│ ├── data.py # Quiz question data or API calls
│ ├── images/
│ │ ├── true.png # Image for true button
│ │ └── false.png # Image for false button
├── README.md

Run the application:
cd quiz_gui
python main.py
