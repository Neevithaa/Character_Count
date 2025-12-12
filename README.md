# Character Counter Application

A simple and interactive character counting tool built using HTML, CSS, and JavaScript.  
This project demonstrates real-time character tracking for text inputs with a maximum limit.

## 🚀 Features
- Real-time character counter
- Displays characters typed and remaining (e.g., `150/200`)
- Prevents typing beyond the maximum character limit
- Shows a warning message when the limit is reached
- Clean and minimal UI

## 📋 How It Works
1. User types inside the text area.
2. The `input` event triggers a JavaScript function.
3. The function:
   - Counts the characters typed
   - Updates the display counter (`typed/limit`)
   - Prevents further typing at the max limit
   - Shows a warning message when the limit is reached

## 🛠️ Technologies Used
- **HTML** – Structure of the text area and UI
- **CSS** – Styling for the text area, counter, and warning message
- **JavaScript** – Logic for character counting and preventing overflow
