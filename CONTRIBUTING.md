# 🤝 Contributing to Commit Quest

Thank you for your interest in contributing to **Commit Quest**!

Commit Quest is a game-inspired developer dashboard designed to transform personal coding goals into quests, XP, activity streaks, and achievements.

Contributions are welcome, whether you want to improve the interface, introduce new features, fix issues, or suggest improvements.

This guide explains how to contribute to the project.

---

## 📋 Table of Contents

- [Getting Started](#-getting-started)
- [Development Setup](#-development-setup)
- [Project Structure](#-project-structure)
- [Ways to Contribute](#-ways-to-contribute)
- [Code Guidelines](#-code-guidelines)
- [GitHub API Guidelines](#-github-api-guidelines)
- [Testing](#-testing)
- [Reporting Bugs](#-reporting-bugs)
- [Suggesting Features](#-suggesting-features)
- [Pull Request Process](#-pull-request-process)
- [Commit Message Guidelines](#-commit-message-guidelines)
- [Code of Conduct](#-code-of-conduct)

---

## 🚀 Getting Started

Before contributing, make sure you have:

- Basic knowledge of HTML, CSS, and JavaScript.
- Visual Studio Code or another code editor.
- Git installed on your computer.
- A modern web browser.
- A GitHub account.
- Familiarity with GitHub repositories and pull requests.

No backend setup, package installation, or API configuration is required for the current version.

---

## 💻 Development Setup

**1. Fork the repository**

Visit the Commit Quest GitHub repository and click the **Fork** button.

**2. Clone your fork**

Replace `YOUR-USERNAME` with your GitHub username.

```bash
git clone https://github.com/YOUR-USERNAME/CommitQuest.git
```

**3. Navigate to the project directory**

```bash
cd CommitQuest
```

**4. Open the project in VS Code**

```bash
code .
```

**5. Start the application**

Open `index.html` using the Live Server extension.

You can also open the file directly in your browser.

**6. Create a new branch**

```bash
git checkout -b feature/your-feature-name
```

---

## 📂 Project Structure

```text
CommitQuest/
│
├── index.html
├── styles.css
├── app.js
├── README.md
├── CONTRIBUTING.md
├── LICENSE
├── .gitignore
│
└── images/
    ├── Home.PNG
    ├── Quest Map.PNG
    ├── Activity.PNG
    └── Milestone.PNG
```

### Main File Responsibilities

- `index.html` - Application structure, sections, and navigation.
- `styles.css` - Visual design, responsive layouts, and animations.
- `app.js` - Quest logic, XP calculations, GitHub requests, and interactions.
- `images/` - Screenshots and visual assets.
- `README.md` - Main project documentation.
- `CONTRIBUTING.md` - Contribution guidelines.
- `LICENSE` - Project licensing information.

Keep the code organized and avoid placing unrelated features in a single file.

---

## 🛠️ Ways to Contribute

### 1. Report Bugs

Help identify and resolve problems involving:

- Incorrect quest behavior.
- Broken buttons or navigation.
- Incorrect XP calculations.
- Progress-saving issues.
- Achievement tracking problems.
- GitHub API request errors.
- Visual glitches and layout problems.
- Browser compatibility issues.

### 2. Improve the User Interface

Suggestions include:

- Better dashboard layouts.
- Improved quest cards.
- More interactive progress indicators.
- Additional animations and transitions.
- Better responsive layouts.
- Improved accessibility.
- Additional customization options.

Maintain the existing Commit Quest visual identity when introducing new designs.

### 3. Improve Quest Mechanics

Possible improvements include:

- New quest categories.
- Recurring quests.
- Quest deadlines.
- Additional XP rewards.
- Daily and weekly challenges.
- More developer ranks.
- New achievements and milestones.
- Quest difficulty levels.

### 4. Improve GitHub Integration

Contributors may suggest improvements involving:

- Public repository information.
- GitHub activity visualization.
- Repository language statistics.
- Better API error handling.
- Improved loading states.
- API request optimization.

Only request the information necessary for the feature being implemented.

### 5. Improve Documentation

You can also contribute by:

- Correcting documentation errors.
- Improving installation instructions.
- Adding screenshots.
- Updating project descriptions.
- Providing clearer explanations.

---

## 📝 Code Guidelines

### HTML

- Use semantic HTML elements whenever possible.
- Keep the document structure organized.
- Use descriptive class and ID names.
- Maintain accessibility with appropriate labels and attributes.
- Avoid unnecessary elements.

### CSS

- Use consistent naming conventions.
- Keep styles organized.
- Prefer reusable classes.
- Maintain responsive behavior.
- Avoid unnecessary animations that negatively affect usability.
- Respect reduced-motion preferences.
- Preserve the existing design consistency.

### JavaScript

- Use clear and descriptive variable names.
- Prefer `const` and `let` over `var`.
- Use functions to separate application features.
- Avoid unnecessary global variables.
- Validate user inputs.
- Handle unexpected values and errors.
- Keep localStorage operations organized.
- Use appropriate error handling for API requests.
- Avoid unnecessary dependencies.

### General Guidelines

- Write readable and maintainable code.
- Remove unused code.
- Avoid introducing unnecessary dependencies.
- Do not include API keys, passwords, or private credentials.
- Preserve existing functionality when modifying features.
- Update documentation when necessary.

---

## 🔌 GitHub API Guidelines

Commit Quest uses the public GitHub REST API.

When modifying GitHub integration:

- Follow the official GitHub REST API documentation.
- Handle unsuccessful requests appropriately.
- Include loading and error feedback.
- Respect API rate limits.
- Avoid unnecessary repeated requests.
- Do not request private credentials for public information.
- Do not assume that public events represent complete contribution history.

Official documentation:

https://docs.github.com/en/rest

---

## 🧪 Testing

Before submitting a contribution, test your changes.

### Functional Testing

- Verify that buttons and navigation work.
- Test quest creation and completion.
- Check XP calculations.
- Verify rank progression.
- Test achievement conditions.
- Confirm that progress-saving features work.
- Test GitHub profile lookup.
- Check API error handling.

### Interface Testing

- Test the application on desktop and mobile screens.
- Check hover and active states.
- Verify animations and transitions.
- Ensure text remains readable.
- Check that interface elements do not overlap.
- Confirm that the layout remains consistent.

### Browser Testing

Test using modern versions of:

- Google Chrome
- Microsoft Edge
- Mozilla Firefox

Also check the browser developer console for JavaScript errors.

---

## 🐛 Reporting Bugs

If you discover a problem, create a GitHub Issue.

Include:

- A clear issue title.
- A description of the problem.
- Steps to reproduce the issue.
- Expected behavior.
- Actual behavior.
- Browser and operating system.
- Screenshots or recordings, if applicable.

### Suggested Bug Report Format

**Title:** [BUG] Brief description of the issue

**Description:**

Explain what happened.

**Steps to Reproduce:**

1. Open Commit Quest.
2. Navigate to the affected feature.
3. Perform the action.
4. Observe the problem.

**Expected Result:**

Describe what should happen.

**Actual Result:**

Describe what happened instead.

---

## 💡 Suggesting Features

Feature suggestions are welcome!

When submitting a suggestion, include:

- Feature name.
- Description.
- Purpose and expected benefits.
- How it could work.
- Optional screenshots or references.

Examples:

- New quest categories.
- Additional developer ranks.
- Recurring development goals.
- Customizable profiles.
- More achievement systems.
- Improved GitHub activity tracking.
- Cloud-based progress synchronization.

---

## 🔀 Pull Request Process

1. Fork the repository.
2. Clone your fork.
3. Create a new branch.
4. Make your changes.
5. Test the application.
6. Commit your changes with a clear message.
7. Push your branch to your fork.
8. Open a Pull Request.
9. Explain what you changed and why.
10. Wait for review and address feedback.

### Pull Request Checklist

Before submitting, make sure:

- [ ] The changes have been tested.
- [ ] Existing features still work.
- [ ] The code follows the project's guidelines.
- [ ] No unnecessary files or dependencies were added.
- [ ] No API keys or private information are included.
- [ ] Documentation has been updated when necessary.
- [ ] Screenshots are provided for significant UI changes.

---

## 📝 Commit Message Guidelines

Use short and descriptive commit messages.

Recommended prefixes:

| Prefix | Purpose |
|---|---|
| `feat:` | New feature |
| `fix:` | Bug fix |
| `style:` | UI or styling changes |
| `docs:` | Documentation updates |
| `refactor:` | Code restructuring |
| `test:` | Testing-related changes |
| `perf:` | Performance improvements |

### Examples

```bash
git commit -m "feat: add recurring quests"
git commit -m "fix: correct XP calculation"
git commit -m "style: improve dashboard layout"
git commit -m "docs: update README"
```

---

## 🤝 Code of Conduct

All contributors are expected to:

- Be respectful and professional.
- Provide constructive feedback.
- Respect other contributors' work.
- Avoid discriminatory or inappropriate behavior.
- Focus on improving the project.
- Help maintain a welcoming learning environment.

---

## 📬 Questions and Support

For questions, suggestions, or project-related concerns, you may open a GitHub Issue or contact the project developer through GitHub.

**GitHub:** [@rheillunio2-byte](https://github.com/rheillunio2-byte)

---

Thank you for helping improve **Commit Quest**!

Every contribution helps make developer productivity more interactive, engaging, and enjoyable.

**Small commits. Big quests. Keep building.** ✦