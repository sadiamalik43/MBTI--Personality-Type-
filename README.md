# MBTI--Personality-Type-
# ✨ JavaFX Personality Quiz Application

This is a beautifully styled JavaFX application that serves as a **personality test**. The quiz asks
users 14 thought-provoking questions, each with four answer choices. Based on the cumulative
score, the user receives a fun and informative result inspired by **MBTI (Myers-Briggs Type
Indicator)** personality types.

## 🌟 Features

- ✅ 14 personality-related multiple-choice questions
- 🎨 Custom-styled UI with vibrant colors and hover effects
- 🧠 MBTI-style result interpretation based on user score
- 🔁 Option to restart the quiz and retake the test
- 🏠 Clean home screen with start and exit options
- 📱 Responsive layout for various screen sizes

## File Location
The main class of the application is located (in the zip folder) at:
project → src → ProjectOOP → Main.java
This file contains the entry point (public static void main(String[] args)) and launches the JavaFX GUI
for the Personality Quiz.

---

## 📁 Project Structure

## 🚀 How to Run

### 🧠 Requirements

- Java JDK 8 or higher
- JavaFX SDK
- IDE like IntelliJ IDEA or Eclipse (with JavaFX properly set up)

### ▶️ Steps

1. **Clone the repository** or copy the source files into your IDE.
2. **Set up JavaFX**:
- Add JavaFX libraries to your project dependencies.
3. **Run `Main.java`**:
- Right-click `Main.java` → Run.
4. The GUI will launch showing the welcome screen. Click "Take Test" to start.

## 💡 Personality Logic

- Each answer contributes to a cumulative score.
- Answers are scored as:
- **Yes** → 2.0 points
- **Most times** → 1.5 points
- **Sometimes** → 1.0 point
- **No** → 0.0 points

### 🔢 Result Tiers

| Score Range | Personality Type | MBTI Interpretation |
|-------------|--------------------------------------------|------------------------------------|
| 26 - 28 | 💖 Radiant Extrovert | ENFJ |
| 22 - 25.5 | 🎉 Charismatic Connector | ESFP |
| 18 - 21.5 | 🔄 Ambivert Balance | INFP |

| 14 - 17.5 | 🧠 Thoughtful Introvert | ISTJ |
| 10 - 13.5 | 🎨 Quiet Creative | INTP |
| Below 10 | 🧠 Enigmatic Soul | INFJ |

## 🎨 UI Design Highlights

- Uses **VBox** for vertical layout and alignment.
- Stylish **linear-gradient** backgrounds.
- Hover effects on buttons and answers for interactive feedback.
- All text elements styled with **custom fonts** and color palette for an engaging aesthetic.

## 🔁 Reset & Restart Functionality

Once the user receives a result, they can click "🔁 Restart" to:
- Reset score and question index
- Show the first question again
- Re-enable all UI components

## 📦 Future Improvements

- Store results to a database or file
- Add question categories (e.g., Introversion, Judging)
- Introduce progress indicators
- Allow user login for tracking results
