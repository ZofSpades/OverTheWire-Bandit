# OverTheWire-Bandit

This repository contains concise, step-by-step solutions for each level of the [OverTheWire: Bandit](https://overthewire.org/wargames/bandit/) wargame.

## 📁 Repository Structure

The repository is organized into clearly separated sections:

```
📁 OverTheWire-Bandit/
├── All Passwords/
│   └── bandit_all_passwords.txt     # Cumulative passwords for all levels
├── Levels/
│   ├── _bandit_0.txt                # Starting info or login instructions
│   ├── bandit_0_1.txt               # Steps to go from Level 0 to 1
│   ├── bandit_1_2.txt               # Steps to go from Level 1 to 2
│   ├── bandit_2_3.txt
│   └── ...
├── LICENSE                         # MIT License
└── README.md                       
```

### 🔹 File Naming Convention
- `_bandit_0.txt` — optional setup/login instructions.
- `bandit_X_Y.txt` — contains the commands used to solve level X and obtain the password for level Y.
- `__bandit_all_passwords.txt` — contains the final passwords collected from each level for quick reference.

## 📄 File Style & Contents

Each file (`bandit_X_Y.txt`) includes:
- The commands to solve the level, marked with the prefix `cmdit`
- The final password for level `Y` at the end

### 🔹 Example Format (inside each level file)
```
# bandit_0_1.txt
cmdit: ssh -p 2220 bandit0@bandit.labs.overthewire.org
password: <password_here>

cmdit: ls
cmdit: cat readme
# Short explanation (optional)

Tip: You can add multi-line comments or guidance.
```

### 🧠 Tips
- Commands start with `cmdit:` for clarity.
- `cmdit:` stands for a command to be typed in the terminal.
- Explanations follow the relevant command.
- Use `Tip:` lines to offer helpful hints.
- Passwords are shown at the **end** of each file with `password:`.
- Relevant external references or tools are mentioned when necessary to help understand or solve a level.

## 🛑 Disclaimer

This repository was originally created for my personal reference while solving the Bandit wargame. I decided to upload it in case it helps others facing similar challenges.

These solutions are for educational purposes only and are personally written by me based on my own solving of the levels. Try solving the levels yourself first — use this repo as a reference or last resort.

## 📣 Found a Mistake?

If you notice any errors or have suggestions to improve the solutions, feel free to [open an issue](https://github.com/zofspades/OverTheWire-Bandit/issues). Contributions and corrections are welcome!



## 📜 License

Licensed under the [MIT License](LICENSE).

---

Happy hacking! 🐚
