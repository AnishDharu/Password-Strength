# 🔐 Password Strength Evaluator (Python)

This Python script evaluates the strength of a user-provided password based on several key criteria. It provides real-time feedback on each aspect of the password and classifies it as **Strong**, **Moderate**, or **Weak**.

## 🧩 Features

- ✅ Checks password **length** (minimum 8 characters)
- ✅ Detects **uppercase letters**
- ✅ Detects **lowercase letters**
- ✅ Verifies the presence of **digits**
- ✅ Confirms inclusion of **special characters** (e.g. `!@#$%^&*`)

## 🛠 How It Works

The script uses Python's built-in functions and regular expressions to evaluate the password based on five criteria. Each satisfied criterion contributes to a score that determines the final strength rating.

### Strength Ratings:

| Criteria Met | Strength         |
|--------------|------------------|
| 5/5          | Strong Password  |
| 3–4/5        | Moderate Password|
| 0–2/5        | Weak Password    |

## 📦 Requirements

- Python 3.x  
- No external dependencies (uses standard library)

## 🚀 Usage

1. Clone or download the repository.
2. Run the script using Python:

```bash
python password_strength_checker.py
