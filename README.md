# H250assinment-tracker
Multi-class assignment &amp; practical file tracker for teachers with Firebase backend, real-time sync, and CSV export.
# 📚 Assignment & Practical Tracker

A lightweight web app for teachers to track assignment and practical file submissions across multiple classes, subjects, and semesters — from any device, without any install.

**Live Demo:** [https://RishitVashist.github.io/H250assinment-tracker/](https://RishitVashist.github.io/H250assinment-tracker/)

 
## The Problem**

As a B.Tech 2nd year class representative, I was manually tracking:

- **44+ students** per class
- **7 subjects** per semester
- **4 units** per subject
- Multiple classes (BTech 1st/2nd/3rd A/B, BCA 1st/3rd A/B, 1ST A/B)
- Both **practical files** and **assignments**

That's 2,000+ entries per year on paper. Records would get lost, mixed up between subjects, or never updated. No easy way to share with teachers or take backups. And if the register got damaged — everything gone.

## 💡 My Solution

A single-page web app that solves all of it:

- ✅ **Works offline** after first load — no server setup needed
- ✅ **Multi-class support** — each class has its own students and subject list
- ✅ **Multi-semester** — old data never deleted, switch any time from dropdown
- ✅ **Auto-saves** every click to Google Cloud (Firebase Firestore)
- ✅ **Real-time sync** — one teacher's change appears instantly on other devices
- ✅ **Teacher login** — only authorized users can access (no self-signup)
- ✅ **CSV export** — full backup and Excel-ready reports
- ✅ **Mobile-friendly** — add to home screen like a native app

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|-----------|
| **Frontend** | Vanilla HTML + CSS + JavaScript (no frameworks) |
| **Authentication** | Firebase Authentication (Email/Password) |
| **Database** | Firebase Firestore (Google Cloud, Mumbai region) |
| **Hosting** | GitHub Pages |
| **Cost** | ₹0 — all free tiers |

**Why no framework?** Kept it simple, fast, and zero-dependency. Loads instantly, works on slow networks.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| Multi-class support | BTech 1st/2nd/3rd, BCA, 1ST A/B — all in one app |
| Per-class subjects | Each class has its own subject list (BTech 3rd ≠ BTech 1st) |
| Multi-semester | 2026-ODD, 2027-EVEN, etc. — no data lost ever |
| Auto-date on mark | One click → today's date fills automatically |
| Auto-save | Every change saves to cloud within 1-2 seconds |
| Real-time sync | Two teachers see the same data live |
| Teacher login | Firebase auth — no self-signup, admin creates accounts |
| Per-sheet isolation | Each (semester + class + subject) has separate data |
| Roll editor | Update student roll numbers anytime |
| Subject editor | Add/remove subjects anytime |
| CSV export | Per-sheet, per-semester, or full backup |
| Print-friendly | Clean printable view with Ctrl+P |

---

## 🚀 How to Use

1. Open the [live link](https://RishitVashist.github.io/H250assinment-tracker/)
2. Login with teacher credentials (created by admin)
3. Select **Semester → Class → Subject** from dropdowns
4. Click **Mark** next to any student who submitted
5. Today's date fills automatically and saves to cloud
6. Switch between semesters/classes/subjects — data is preserved
7. Click **📦 Export All** weekly for backup

**For new teachers:** Admin adds them via Firebase Console (Authentication → Add user).

---

## 📊 Scale

- **Classes:** 7+
- **Students per class:** 44-60
- **Subjects per class:** 7
- **Semesters:** 2 per year
- **Total entries/year:** ~2,500

---

## 📸 Screenshots

*(Coming soon — add 2-3 screenshots of the login screen and main table)*

---

## 🔒 Security

- Only Firebase-authenticated users can read or write data
- Firestore security rules enforce `request.auth != null`
- No self-signup — only admin-created accounts work
- Passwords handled entirely by Firebase (SHA-256 hashed, never stored in plaintext)

---

## 📝 What I Learned

Building this taught me:

- **Problem-first thinking** — real classroom pain → real tool
- **Firebase** — Authentication, Firestore, real-time listeners
- **Vanilla JS** — DOM manipulation, event handling, async/await
- **Git & GitHub** — version control, deployment with GitHub Pages
- **Working with AI** — using AI as a pair programmer while understanding every line

---

## 🤝 Honest Note

I identified the problem (real classroom pain), designed the workflow, decided on features, and tested the app with teachers.

For JavaScript implementation, I used **AI assistance (Claude)** — I'm actively learning JS to extend and maintain this independently. Every feature, every iteration, and every bug fix was driven by real usage feedback.

---

## 📬 Contact

- **Rishit** — B.Tech 2nd year
- LinkedIn: [YOUR_LINKEDIN](https://linkedin.com/in/Rishit Vashis)
- Email:rishitvashist414@gmail.com

---

## 📄 License

MIT — free to use, modify, and share.
