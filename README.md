#**GitHub Workshop Review Project**

This project is built by the **CSS Team** using **Django** to collect participant reviews for our Git and GitHub workshop.

Each participant will add their review by creating a **JSON file** in the repository.
The reviews are loaded dynamically and displayed through a Django web app.

---

**# 📄 JSON File Format**

Each participant must create a JSON file with the following structure:

```json
{
  "username": "your-github-username",
  "review": "your feedback about the workshop"
}
```

**Example:**

```json
{
  "username": "css-member",
  "review": "It was an amazing experience learning Git and GitHub!"
}
```

- The **filename** must be your **GitHub username** (example: `css-member.json`).
- Save it in the correct folder (`reviews/`).

---

**# 💻 Tech Stack**

- **Backend**: Django (Python)
- **Data Storage**: JSON files for participant reviews

---

**# 🛠️ Project Goals**

- Practice real-world Git and GitHub workflows.
- Understand the complete Git process: `git init`, `git add`, `git commit`, `git push`, and `git pull`.
- Learn how to fork a repository and clone it locally.
- Create branches and work independently.
- Submit changes through a **Pull Request (PR)**:
  - Fork the main repository.
  - Add your review.
  - Create a pull request to merge your contribution.
- Understand code collaboration and conflict resolution.
- Build a simple Django app.

**Pull Request Concept:**

A **Pull Request** (PR) is when you ask to merge your changes into a repository. It allows project maintainers to review, discuss, and approve changes before they are merged into the main codebase. It’s an essential part of teamwork and open-source contributions.

---

**# ❤️ Special Thanks**

Thanks to all **CSS Club** members and participants for making this event successful! 🚀

---

**# 📜 License**

This project is licensed under the **MIT License**.

You are free to use, modify, and distribute this project with proper attribution.&#x20;

