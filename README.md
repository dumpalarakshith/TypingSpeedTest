# TypingSpeedTest

##  Overview
The **Typing Speed Test** is a simple Java console application that tests your typing speed and accuracy. It displays a random sentence, tracks your typing time, and evaluates your typing speed (WPM) and accuracy percentage.

---

##  Key Features
- **Random Sentence Generation:** Displays unique sentences to type.
- **Typing Time Tracking:** Measures the time taken to complete typing.
- **WPM Calculation:** Computes Words Per Minute (WPM).
- **Accuracy Check:** Compares the typed sentence with the original to calculate accuracy.
- **Retry or Exit Option:** Allows you to retry or exit after each test.

---

##  Project Structure

TypingSpeedTest/ ├── src/ │ └── com/ │ └── typingtest/ │ ├── TypingSpeedTest.java # Main class that controls the application flow │ ├── SentenceManager.java # Generates and displays random sentences │ ├── InputHandler.java # Captures and validates user input │ ├── ResultCalculator.java # Calculates WPM and accuracy │ └── Utility.java # Utility methods for validations and formatting └── README.md # Project documentation


---

## File Descriptions

### 1. `TypingSpeedTest.java`
- Entry point of the application.
- Controls program flow and invokes methods from other classes.

### 2. `SentenceManager.java`
- Selects and displays a random sentence from a predefined list.
- Prevents repetition of recent sentences.

### 3. `InputHandler.java`
- Takes user input and validates it.
- Tracks the time taken by the user to type the sentence.

### 4. `ResultCalculator.java`
- Calculates typing speed (WPM) and accuracy percentage.
- Compares typed input with the original sentence.

### 5. `Utility.java`
- Provides helper methods for trimming spaces and formatting results.

---

##  How to Run

### Step 1: Download/Extract the Project
- Download the project as a ZIP file.

