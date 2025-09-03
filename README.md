# Delulu Social Media — Developer Documentation

Welcome to the official developer documentation for **Delulu Social Media**.  
This repository is part of our commitment to **transparency** we want developers, contributors, and users to understand how the app is built and how data is handled.

---

## 📑 Table of Contents
- [About This Repository](#-about-this-repository)
- [Firebase Rules](#-firebase-rules)
- [Terms](#-terms)
- [Contact](#-contact)

---

## 📖 About This Repository
- Provides insight into the technical foundation of Delulu Social Media.
- Shares our Firebase security rules and data access policies.
- Outlines how we prioritize **user privacy** and **data security**.

---

## 🔒 Firebase Rules
Delulu Social Media uses **strict Firebase Realtime Database security rules** to protect user data.  

- By default, the database is **locked down** (`.read` and `.write` set to `false` at root).  
- Each authenticated user can **only access their own data** under `/users/{uid}`.  
- This prevents unauthorized access and ensures **isolation** between users.  

📂 The full rules are defined in [`rules.json`](./rules.json) at the project root.  

---

## 📜 Terms
We are working on clear, community driven **Terms & Policies** that reflect our values of transparency and fairness.  

🕒 **Coming soon...**

---

## 🌐 Contact
- Website: [www.delulu.media](https://www.delulu.media)  
- Email: [info@delulu.media](mailto:info@delulu.media)
