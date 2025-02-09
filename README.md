# 🎮 Word Game - A Wordle Clone

A fun word puzzle game built with **React** and **Redux**! Guess the target word in 6 attempts. Each letter gets colored to show how close you are to the answer!

---

## 🚀 **Features**
- 🎨 **Color-coded hints** (Green, Yellow, Gray)
- 🖥️ **Keyboard input support**
- 🔄 **Automatic state updates with Redux**
- 📱 **Responsive UI**
- ✅ **Valid word checking**

---

## 🎯 **How to Play**
1. **Enter a 5-letter word** using your keyboard or the on-screen keys.
2. Press **Enter (↩)** to submit.
3. Letters will turn:
   - 🟩 **Green** → Correct letter, correct position.
   - 🟨 **Yellow** → Correct letter, wrong position.
   - ⬜ **Gray** → Letter is not in the word.
4. Keep guessing until you find the **target word** or **run out of attempts**.

---

## 🛠️ **Installation**
### 1️⃣ **Clone the repository**
```bash
git clone https://github.com/hellmelon/wordgame.git
cd nerdle
```

### 2️⃣ **Install dependencies**
```bash
npm install
```

### 3️⃣ **Run the game**
```bash
npm start
```

---

## 👷🏽‍♀️ **Structure**
📂 nerdle
 ├── 📂 src
 │   ├── 📂 components
 │   │   ├── 🏗️ Board.tsx     # Displays the guessed words
 │   │   ├── ⌨️ Keyboard.tsx  # Handles user input
 │   │   ├── 🎨 funcs.ts      # Game logic for word checks
 │   ├── 📂 store
 │   │   ├── 🔄 store.ts      # Redux store setup
 │   │   ├── 📜 wordlist.json # Valid words
 ├── 📜 README.md
 ├── 📜 package.json

