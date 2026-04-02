# Mac Dev Setup (Homebrew + Node.js)

This repository documents how I set up my Mac for development using Homebrew and Node.js, including troubleshooting common issues.

## 🧰 Tools Installed
- Homebrew (package manager for macOS)
- Node.js (JavaScript runtime)

---

## 📦 Step 1: Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"

brew --version

Homebrew 5.x.x

brew install node@22

node -v

v22.x.x
