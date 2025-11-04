# 🔐 TripleX — A C++ Console Puzzle Game

**TripleX** is a fun, text-based number puzzle game written in C++.  
You play as a secret agent breaking into secure server rooms by solving mathematical code challenges.  
Each level gets progressively harder as you advance through increasingly complex locks.

---

## 🎮 Gameplay

In each level, you’re given:
- The **sum** and **product** of three secret code numbers.  
- You must **guess all three numbers correctly** to advance to the next level.

### Example:

You are a secret agent breaking into a level 3 secure server room...
Enter the correct code to continue...

`There are 3 numbers in the code`

`The codes add-up to: 9`

`The codes multiply to give: 27`

`3 3 3`

*** Well done agent! You have extracted a file! Keep going! ***

If you guess wrong:

*** You entered the wrong code! Careful agent! Try again! ***


---

## 🧩 Features

- Progressive difficulty across multiple levels (1–20)
- Randomly generated codes using `rand()`
- Text-based gameplay (no graphics needed)
- Teaches logical reasoning and pattern deduction
- Clean and beginner-friendly C++ structure

---

## 🛠️ How to Build and Run

### **1. Clone the repository**
```bash
git clone https://github.com/yourusername/triplex.git
cd triplex
```

### **2. Compile the game**
```bash
g++ triplex.cpp -o triplex
```

### **3. Run the game**
```bash
./triplex
```

## 📁 File Structure
```bash
triplex/
│
├── triplex.cpp   # Main game source file
└── README.md     # Project documentation
```

## 💡 How It Works

Uses rand() with srand(time(NULL)) to generate pseudo-random numbers.

Difficulty scaling ensures higher levels have larger numbers.

Logical checks compare player guesses with actual code sums and products.


## 🚀 Future Improvements

Add a scoring system or timer

Display player stats at the end

Implement multiple difficulty modes (easy/medium/hard)

Create a GUI version using SDL or SFML


## 🧑‍💻 Author

Aditya Sharma
💬 "Think like a hacker. Code like a spy."
📧 nakul.adi@gmail.com


## 🪪 License

This project is open-source under the MIT License

## ⭐ If you like this project, give it a star on GitHub!
```sql
git commit -m "Agent Aditya completed TripleX mission successfully 🚀"
```
```css
Would you like me to add a **badge section** (e.g., C++ version, platform, license, etc.) and a **screenshot/demo section** too? It makes it look even more polished on GitHub.
```

