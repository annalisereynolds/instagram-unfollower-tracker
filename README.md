# instagram-unfollower-tracker

A simple Python tool that compares Instagram followers vs following using your official Instagram data export.

---

## 🚀 Features
- No scraping or API usage
- Uses Instagram data export (JSON)
- Shows:
  - People who don’t follow you back
- Exports results as CSV

---

## 📥 How to use

### 1. Get your Instagram data
Go to Instagram:

Settings → Accounts Center → Your Information → Download Your Information

Choose:
- Format: JSON
- Include: Followers + Following

---

### 2. Put files here
data/followers.json
data/following.json

---

### 3. Run the script

```bash
python tracker.py
