# 🎤 Voice-Based Calculator

A simple voice-based calculator developed using **MIT App Inventor**.  
The application allows users to speak a basic arithmetic calculation and displays the calculated result.

## 🌐 Live Website

[Click here to open the Voice-Based Calculator]()

## 📱 Application

The application uses voice recognition to take an arithmetic expression from the user.

For example:

- "5 + 3" → 8
- "10 - 4" → 6
- "6 × 7" → 42
- "20 ÷ 5" → 4

## ⚙️ How It Works

1. The user taps the **Speak** button.
2. The application activates the **Speech Recognizer**.
3. The user speaks an arithmetic expression.
4. The recognized text is displayed on the screen.
5. The expression is split into:
   - First number
   - Operator
   - Second number
6. The application performs the corresponding arithmetic operation.
7. The result is displayed on the screen.

## 🧩 Technologies Used

- **MIT App Inventor**
- Speech Recognizer
- Text-to-Speech
- Blocks-based programming

## 🔧 Components Used

- `SpeakButton`
- `RecognizedLabel`
- `ResultLabel`
- `SpeechRecognizer1`
- `TextToSpeech`

## ➕ Supported Operations

| Operation | Symbol |
|---|---|
| Addition | + |
| Subtraction | - |
| Multiplication | × |
| Division | ÷ |

## 🧠 Logic

The application uses the following basic logic:

```text
Voice Input
     ↓
Speech Recognition
     ↓
Split the input into words
     ↓
Identify numbers and operator
     ↓
Perform calculation
     ↓
Display Result
