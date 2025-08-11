# Mini-Voting-System-Using-C-Language

## 📁 **Step-by-Step Submission Plan**

### 🔧 1. Create a folder and organize files:

**Folder name**: `ElectronicVotingSystem`

Inside it, include:

```
ElectronicVotingSystem/
├── voting_system.c       <- Your full C code file
├── README.md             <- Documentation file
└── candidate*.txt        <- (if available, during testing)
```

---

### 📝 2. Sample `README.md` file

Here's what your `README.md` file should contain (you can copy-paste this and modify):

````markdown
# 🗳️ Electronic Voting System in C

This project is a command-line-based voting system for college elections. It supports:
- Admin authentication
- Candidate management
- Student validation via user ID (e.g., 2024btechs00001)
- Vote casting and result display
- Banned user tracking
- Vote deletion

## 👨‍💼 Admin Features
- Start new elections
- Continue from previous saved state
- Ban specific user IDs
- Delete illegal votes
- View winner and vote statistics

## 👨‍🎓 Student Features
- Login with PRN/user ID
- Cast vote only once
- Input validation and banning protection

## 🛠 Compilation Instructions
```bash
gcc voting_system.c -o voting_system
./voting_system
````

Make sure files like `ElectionInfo.txt`, `candidate*.txt`, and `Banned.txt` are writable in the same folder.

## 📁 File Details

* `voting_system.c`: Main program
* `ElectionInfo.txt`: Stores ongoing election data
* `candidate1.txt` ... `candidateN.txt`: Vote logs
* `Banned.txt`: List of banned roll numbers

## 💡 Sample PRN Format

```
2024btecs00001
YYYY + BRANCH + S + ROLLNUMBER
```

## 👨‍💻 Author

Siddhant Saxena

````

---

### 🚀 3. GitHub Upload Steps

```bash
cd Desktop
mkdir ElectronicVotingSystem
cd ElectronicVotingSystem
# paste voting_system.c here

git init
git add .
git commit -m "Initial commit: Added voting system"
git branch -M main
git remote add origin https://github.com/YOUR-USERNAME/ElectronicVotingSystem.git
git push -u origin main
````

---



