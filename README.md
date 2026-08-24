# Git & GitHub Workshop - Assignment

## 🎯 Your Task

It's time to put your Git and GitHub skills into practice!

You will create a **personal student card webpage**, host it using **GitHub Pages**, and submit your project through a Pull Request.

Your project should be hosted in **your own GitHub account**.

### Your final submission should contain:

* Your own GitHub repository
* Your student card webpage
* Your deployed GitHub Pages website
* A Pull Request containing the links to both

---

#  Step 1 — Create Your GitHub Repository

Create a **new public repository** on your GitHub account.

You can name it something like:

```text
student-card
```

or

```text
your-name-card
```

Example:

```text
arshpreet-student-card
```

Your repository should contain all the files required for your webpage.

---

#  Step 2 — Create Your Student Card

Create a simple **student profile card**.

Your card should include:

* **Name**
* **Profile picture**
* **Branch / Course**
* **College / University**
* **Short introduction**
* **Skills or technologies you're interested in**
* **GitHub profile link**

You are encouraged to make your card creative and visually appealing.

### Optional

You can also add:

* Social media links
* Portfolio link
* Projects
* Hobbies
* Interests
* GitHub stats
* Animations
* Dark mode
* Custom design

**Make it your own!**

---

# Step 3 — Deploy Using GitHub Pages

Your webpage must be publicly accessible using **GitHub Pages**.

Your final website should look something like:

```text
https://your-username.github.io/student-card/
```

Make sure the link works before submitting your PR.

---

# Step 4 — Submit Your Project

You **do not need to upload your project files to this workshop repository**.

Your project should remain in **your own GitHub repository**.

Instead, you only need to add your submission details to:

```text
NAMES.md
```

Add yourself using this format:

```md
- Your Name — [GitHub Repository](YOUR_REPOSITORY_LINK) — [Live Website](YOUR_GITHUB_PAGES_LINK)
```

### Example

```md
- Arshpreet Singh — [GitHub Repository](https://github.com/arshpreetsingh/student-card) — [Live Website](https://arshpreetsingh.github.io/student-card/)
```

---

# Step 5 — Create Your Pull Request

After adding your details to `NAMES.md`:

### 1. Create a new branch

```bash
git checkout -b student/<your-github-username>
```

Example:

```bash
git checkout -b student/arshpreetsingh
```

### 2. Commit your changes

```bash
git add NAMES.md
git commit -m "Add <your-github-username> submission"
```

### 3. Push your branch

```bash
git push -u origin student/<your-github-username>
```

### 4. Create a Pull Request

Create a PR from your branch to the **main branch of this workshop repository**.

---

# Pull Request Format

### PR Title

Use:

```text
Add <your-github-username> submission
```

Example:

```text
Add arshpreetsingh submission
```

### PR Description

You can use:

```md
## Submission

- GitHub Repository: https://github.com/your-username/your-repository
- Live Website: https://your-username.github.io/your-repository/
```

---

# ✅ Submission Checklist

Before creating your PR, make sure:

* [ ] My GitHub repository is **public**.
* [ ] My student card is complete.
* [ ] My repository contains my project.
* [ ] GitHub Pages is enabled.
* [ ] My deployed website works.
* [ ] I added my name to `NAMES.md`.
* [ ] I added my GitHub repository link.
* [ ] I added my deployed website link.
* [ ] I created a separate branch.
* [ ] I did not modify or delete another student's submission.
* [ ] I created a Pull Request to the workshop repository.

---

# ⚠️ Important Rules

### 1. One submission per student

Submit only your own project.

### 2. Use your own GitHub account

Your project must be hosted in your own GitHub repository.

### 3. Don't modify other students' entries

Only add or modify **your own line** in `NAMES.md`.

### 4. Don't push directly to `main`

Use a separate branch and create a Pull Request.

### 5. Make your repository public

The organizers must be able to view your repository and deployed website.

### 6. Test your links

Make sure both links work before submitting your PR.

---
This is your first step toward contributing to real-world projects and open-source repositories.

## Good luck!

**Build something you're proud of. 🚀**
