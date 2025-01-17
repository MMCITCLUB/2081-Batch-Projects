## Steps to Contribute 🚀

### 1. Fork the Repository 🍴

- Click the **Fork** button at the top-right corner of the repository page to create a copy of this repository under your GitHub account.

---

### 2. Clone the Forked Repository 💻

- Clone the forked repository to your local system using the following command:

  ```bash
  git clone https://github.com/<your-username>/<repository-name>.git
  cd <repository-name>
  ```

---

### 3. Set Upstream for Synchronizing Changes 🔄

- Set the upstream remote to the original repository to keep your fork in sync:

  ```bash
  git remote add upstream https://github.com/<original-owner>/<repository-name>.git
  ```

- Verify the remotes:

  ```bash
  git remote -v
  ```

---

### 4. Create a New Branch 🌿

- Create a branch to work on your changes:

  ```bash
  git checkout -b <branch-name>
  ```

---

### 5. Make Your Changes ✏️

- Make the necessary changes or add your project. Follow the format and coding standards defined in the repository.
- If you are adding a project, update the appropriate file (e.g., `README.md`) with the following format:

  ```markdown
  | [Project Title](project-url) | <Short Description> | [@username](github-profile-url) |
  ```

  **Example:**

  ```markdown
  | [Weather App](https://github.com/username/weather-app) | A React-based weather forecasting app | [@username](https://github.com/username) |
  ```

- Add your changes:

  ```bash
  git add .
  ```

- Commit your changes with a descriptive message:

  ```bash
  git commit -m "<commit-message>"
  ```

---

### 6. Sync with the Upstream Repository 🔄

- Before pushing your changes, ensure your fork is up-to-date:

  ```bash
  git fetch upstream
  git merge upstream/main
  ```

---

### 7. Push Your Changes 🚀

- Push your branch to your forked repository:

  ```bash
  git push -u origin <branch-name>
  ```

---

### 8. Create a Pull Request ✅

- Go to your forked repository on GitHub.
- Switch to the branch you worked on.
- Click **Contribute** → **Open Pull Request**.
- Fill in the details, including a descriptive title and information about your changes.
- Submit the pull request.

---

We look forward to your contributions! 😊
