# Mac Dev Setup (Homebrew + Node.js)

This repository documents how I set up my Mac for development using Homebrew and Node.js, including troubleshooting common issues.

## 🧰 Tools Installed
- Homebrew (package manager for macOS)
- Node.js (JavaScript runtime)

---

## 📦 Step 1: Install Homebrew
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```


### Notes:
- Requires admin access
- Enter your Mac password when prompted
- Press Enter to continue installation

---

## ⚙️ Step 2: Add Homebrew to PATH
bash
```
echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> ~/.zprofile
eval "$(/opt/homebrew/bin/brew shellenv)"
```


---

## ✅ Step 3: Verify Homebrew
bash
```
brew --version
```


Expected output:
nginx
```
Homebrew 5.x.x


---

## 📦 Step 4: Install Node.js
bash
```
brew install node@22
```


---

## ✅ Step 5: Verify Node
bash
```
node -v
```


Expected output:
```
v22.x.x
```



---

## 🧠 Issues I Encountered

### ❌ command not found
- Cause: Homebrew not added to PATH  
- Fix: Run shellenv commands

### ❌ User is not an administrator
- Cause: Installing from non-admin account  
- Fix: Switch to admin account or grant permissions

---

## 🚀 Next Steps
- Install OpenClaw
- Build automation tools
- Continue documenting dev journey

---

## 📈 Goal
Build and document real-world development skills in AI, automation, and systems.



