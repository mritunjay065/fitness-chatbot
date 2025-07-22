# Contributing to the GSSoC'25 Simple Fitness Chatbot 🤖

Welcome, aspiring open-source contributors! We're thrilled you're interested in making the Simple Fitness Chatbot even better as part of **GSSoC'25** and beyond. Your contributions are highly valued!

This guide will help you get started with contributing to this project.

## 🚀 Get Started (Local Setup)

To get the Fitness Chatbot running on your local machine:

1.  **Prerequisites:**
    * Ensure you have **Python 3.x** installed on your system. You can download it from [python.org](https://www.python.org/downloads/).
2.  **Fork the Repository:** Click the "Fork" button at the top right of the GitHub repository page. This creates a copy of the project in your GitHub account.
3.  **Clone Your Fork:** Open your terminal or command prompt and clone your forked repository to your local machine:
    ```bash
    git clone [https://github.com/Akki-jaiswal/fitness-chatbot.git](https://github.com/Akki-jaiswal/fitness-chatbot.git)
    ```
4.  **Navigate to the Project Directory:**
    ```bash
    cd fitness-chatbot
    ```
5.  **Run the Chatbot:**
    Navigate to the directory containing `chatbot.py` in your terminal and execute:
    ```bash
    python chatbot.py
    ```
    You can then interact with the chatbot directly in your terminal.

## 🎯 Finding Tasks & Issues

We use GitHub Issues to track tasks, bugs, and features.

1.  **Check the Issues Tab:** Go to the `Issues` tab on our GitHub repository: [https://github.com/Akki-jaiswal/fitness-chatbot/issues](https://github.com/Akki-jaiswal/fitness-chatbot/issues)
2.  **Look for Labels:** We use labels to categorize issues and indicate their difficulty:
    * `gssoc25`: All issues eligible for GSSoC'25 contributions.
    * `good first issue` / `beginner-friendly`: Great starting points for new contributors.
    * `difficulty:easy`, `difficulty:medium`, `difficulty:hard`: Indicates the complexity.
    * `bug`, `feature`, `documentation`, `enhancement`, `refactor`, `nlp`: Describes the type of work.
3.  **Choose an Issue:** Select an issue that interests you and matches your skill level.

## 🤝 Contribution Workflow

Once you've chosen an issue:

1.  **Claim the Issue:**
    * **Comment on the issue** you've chosen, stating clearly: "I'd like to work on this issue."
    * This helps prevent multiple people from working on the same task.
2.  **Create a New Branch:**
    * Before making any changes, create a new branch from the `main` branch. Use a descriptive name for your branch (e.g., `fix/bug-description`, `feat/new-response`).
    ```bash
    git checkout main
    git pull origin main # Ensure your main branch is up-to-date
    git checkout -b your-branch-name
    ```
3.  **Make Your Changes:**
    * Implement your solution in your new branch.
    * Write clean, readable, and well-commented Python code.
    * Follow the existing code style of the project.
4.  **Test Your Changes:**
    * Ensure your changes work as expected. Test the chatbot thoroughly with various inputs related to your changes.
5.  **Commit Your Changes:**
    * Write clear and concise commit messages.
    ```bash
    git add .
    git commit -m "feat: Add new response for sleep queries" # Example commit message
    ```
6.  **Push Your Branch:**
    ```bash
    git push origin your-branch-name
    ```
7.  **Create a Pull Request (PR):**
    * Go to your forked repository on GitHub. You'll see a prompt to create a Pull Request.
    * **Ensure you are creating a PR from your branch to the `main` branch of the *original* repository.**
    * **Write a clear PR description:**
        * Reference the issue number it closes (e.g., `Closes #123`).
        * Explain what changes you made and why.
        * Provide examples of how to test your changes (e.g., "To test, run `python chatbot.py` and type 'how much protein?").

## 📏 Code Style & Guidelines

* **Python:** Adhere to [PEP 8](https://www.python.org/dev/peps/pep-0008/) guidelines for code style.
* **Comments:** Add comments where the code logic might not be immediately obvious, especially for complex regex patterns or context management.
* **Modularity:** Try to keep changes focused within relevant functions or logical blocks.

## ❓ Getting Help & Communication

We encourage open communication! If you have any questions, get stuck, or want to discuss an idea:

* **Join our Discord Channel:** This is our primary communication hub for real-time discussions and support.
    ➡️ **[Join our Discord Server!](https://discord.gg/4m6JuQ8S)**
* **Comment on Issues:** You can also ask questions directly on the relevant GitHub issue.

We're here to help you succeed! Happy coding, and we look forward to your contributions to the Simple Fitness Chatbot for **GSSoC'25**!
