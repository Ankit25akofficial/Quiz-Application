# Quiz-Application

# 🎉 Interactive Java Swing Quiz Application with SQLite 📝

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white)
![GUI](https://img.shields.io/badge/Swing-GUI-blueviolet?style=for-the-badge)
![Animated](https://img.shields.io/badge/Animated-UI-ff69b4?style=for-the-badge&logo=adobeaftereffects&logoColor=white)

---

## ✨ Features

- 🎨 **Colorful, animated Java Swing GUI**
- 🗂️ **Multiple subjects** (Math, Science, History, English)
- ⏱️ **Animated per-question timer**
- ✅ **Animated feedback** with color transitions and fade-in effects
- 📊 **Score & marks calculation** (positive/negative marking)
- 🔄 **Retry or quit** after results
- 💾 **SQLite database** for easy question management

---

## 🚀 Demo

![QuizApp Animation](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExd3Z2d3R6b3Z2b2F3d3Z2d3Z2d3Z2d3Z2d3Z2d3Z2d3Z2d3Z2/giphy.gif)
<!-- Replace this GIF with your own animated screen recording of the app! -->

---

## 🖼️ Screenshots

| Welcome Screen | Subject Selection | Result InterFace |
|:--------------:|:----------------:|:----------------:|
| ![image](https://github.com/user-attachments/assets/6c132295-4962-4eb2-af6c-5b03dce1f475) |![image](https://github.com/user-attachments/assets/5293437c-9688-46c1-b91f-31d3a3afcf7a) | ![image](https://github.com/user-attachments/assets/b96037c5-b8e8-4e63-8ed4-2784fc51ae4c)


---

## 🛠️ Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/Quiz-Application.git
   cd Quiz-Application
   ```

2. **Add the SQLite JDBC driver** to your project’s classpath.  
   Download from [here](https://github.com/xerial/sqlite-jdbc).

3. **Create your `quiz.db` database** with a `question` table:
   ```sql
   CREATE TABLE question (
     id INTEGER PRIMARY KEY AUTOINCREMENT,
     subject TEXT,
     question TEXT,
     option1 TEXT,
     option2 TEXT,
     option3 TEXT,
     option4 TEXT,
     answer INTEGER
   );
   ```
   *(Add your questions!)*

4. **Compile and run:**
   ```sh
   javac QuizApp.java
   java QuizApp
   ```

---

## 🌈 Animation & Visual Effects

- **Animated Timer:** The timer label updates every second with a smooth color transition as time runs out.
- **Animated Feedback:** When you answer, feedback text fades in and the correct/wrong options flash with color.
- **Panel Transitions:** CardLayout provides smooth animated transitions between screens.
- **Button Highlights:** Option buttons animate with color when selected or when showing correct/wrong answers.

> _All animations are implemented using Java Swing Timers and color transitions for a lively user experience!_

---

## 📄 License

MIT License

---

> Made with ❤️ using Java Swing and SQLite!  
> _Enjoy the quiz and the animations!_
