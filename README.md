#🗳️ Mini Voting System in C

Welcome to the **Mini Voting System** — a simple yet effective C project that simulates a basic voting process through a command-line interface. This program allows users to vote for candidates, view current vote counts, and see who's leading. It’s a great learning project for students and beginners exploring file handling and user input in C.

---

## 📋 What This Project Does

This program mimics a small-scale electronic voting system with:

- A set of 4 predefined candidates
- A menu-driven interface
- Persistent vote count stored using file operations
- Real-time vote counting and leading candidate display

---

## 👨‍💻 How to Set It Up

### 1. Clone the Repository

```bash
git clone https://github.com/Sowmya-Chidurala/MiniVotingSystem.git
cd MiniVotingSystem
````

### 2. Compile the Code

Using GCC or any C compiler:

```bash
gcc VotingSystem.c -o VotingSystem
```

### 3. Run the Program

```bash
./VotingSystem
```

> 💡 *On Windows, use any C IDE like Dev C++, Code::Blocks, or compile via MinGW.*

---

## 🧾 Program Flow

Once the program starts, it displays a menu:

```
Welcome to the Voting System

1. Cast the Vote
2. Find Vote Count
3. Find Leading Candidate
0. Exit
```

You simply enter the number of your choice and follow the prompts.

---

## 👥 Candidates

The default candidates in this system are:

1. John
2. Alice
3. Bob
4. Diana

You can modify the candidate names in the code easily by editing the candidate array inside `VotingSystem.c`.

---

## 🔧 Customization

Want to personalize the system? You can:

* 🗳 Change the number or names of candidates
* 📁 Update how votes are stored (currently in a `.txt` file)
* 🧠 Add input validation or admin login
* 🌐 Build a GUI or web-based version in the future!

---

## 📷 Sample Output

```plaintext
*** Voting System ***

1. Cast Vote
2. Find Vote Count
3. Find Leading Candidate
0. Exit

Enter your choice: 1

*** Please choose your candidate ***
1. John
2. Alice
3. Bob
4. Diana

Enter your choice: 2

Thanks for voting!
```

---

## 🙌 Contributions

This is a simple educational project, but if you'd like to contribute or extend it — feel free! Suggestions, bug reports, and pull requests are always welcome.


## 👩‍💻 Author

**Sowmya Chidurala**
Made with ❤️ as a beginner-level C programming project.

If you find this useful, give the repo a ⭐ and share it with fellow learners!

``
