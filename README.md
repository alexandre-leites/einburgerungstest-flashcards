# Flashcards: Einbürgerungstest Vocabulary

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/alexandreleites)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)]([YOUR_PAYPAL_LINK])

A simple, clean, no-fuss flashcard web app designed to help you study the key vocabulary for the German *Einbürgerungstest* (Naturalization Test).

This app focuses on the specific political, historical, and social terminology required to understand the test questions. I built it to aid in my own studies while living in Germany.

**[Try the live version here!](https://alexandre-leites.github.io/einburgerungstest-flashcards/)**

---

## 📸 Screenshot

*(Recomendo que você tire um screenshot do app e o coloque aqui)*
`![Screenshot of the Einbürgerungstest Flashcard App](./assets/screenshot.png)`

---

## ✨ Features

* **🌍 Multilingual Interface:** Choose between **English** and **Portuguese (Brazil)** for the UI and answers.
* **📊 Session Tracking:** A live scoreboard tracks your correct, incorrect, skipped answers, and average time per question.
* **💾 Game History:** All your sessions are saved in your browser's `localStorage` so you can review your progress over time.
* **🧠 Smart Quizzes:** Uses a 5-option multiple-choice format, pulling 2 "distractor" options from the same category as the correct answer to make it more challenging.
* **🔄 Dynamic Study Mode:** Randomly inverts cards (15% chance) to test you on German $\rightarrow$ Answer *and* Answer $\rightarrow$ German, keeping you on your toes.
* **📱 Responsive Design:** Clean, simple interface that works on desktop and mobile.

---

## 🚀 How to Use

### 1. Live Version (Recommended)

The easiest way to use the app is directly on GitHub Pages:
**[https://alexandre-leites.github.io/einburgerungstest-flashcards/](https://alexandre-leites.github.io/einburgerungstest-flashcards/)**
*(Lembre-se de habilitar o GitHub Pages no seu repositório, na aba "Settings", para que este link funcione. Aponte-o para a pasta `/docs`)*

### 2. Local Development

This project uses `fetch()` to load word lists, so it **must be run from a web server**. You cannot just open the `index.html` file directly in your browser.

The repository includes helper scripts to make this easy.

**Prerequisites:**
* [Python 3](https://www.python.org/) (for the development server)

**Steps:**

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/alexandre-leites/einburgerungstest-flashcards.git](https://github.com/alexandre-leites/einburgerungstest-flashcards.git)
    cd einburgerungstest-flashcards
    ```

2.  **Run the server (.bat or .sh)**

This will automatically start a server (serving the `/docs` folder), open your default browser, and reload the page whenever you make changes to the code.

---

## Credits & Support

This project was created by **alexslx** ([@alexandre-leites](https://github.com/alexandre-leites)).

If this tool helped you with your studies, please consider supporting its development or just saying thanks!

[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black)](https://buymeacoffee.com/alexandreleites)
[![PayPal](https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white)]([YOUR_PAYPAL_LINK])

---

## License

This project is licensed under the **AGPL-3.0 License**. See the `LICENSE` file for details.