# Mac Dev Setup (Homebrew + Node.js)

> Documenting my journey into development, AI, and automation 🚀

This repository documents how I set up my Mac for development using Homebrew and Node.js, including troubleshooting common issues.

---

## 🧰 Tools Installed
- Homebrew (package manager for macOS)
- Node.js (JavaScript runtime)

---

## 📦 Step 1: Install Homebrew

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
Notes:
Requires admin access
Enter your Mac password when prompted
Press Enter to continue installation
⚙️ Step 2: Add Homebrew to PATH
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
✅ Step 3: Verify Homebrew
brew --version

Expected output:

Homebrew 5.x.x
📦 Step 4: Install Node.js
brew install node@22
✅ Step 5: Verify Node
node -v

Expected output:

v22.x.x
