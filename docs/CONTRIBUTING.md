# Devr.AI Contribution Guide

Thank you for your interest in contributing to **Devr.AI** – an AI-powered Developer Relations assistant designed to streamline onboarding and community management. This guide will help you get started quickly and efficiently.

---

## 1. Overview

Devr.AI is built to reduce maintainer workload and improve contributor engagement by:
- **Automating routine interactions**
- **Providing personalized onboarding support**
- **Delivering real-time project updates** across multiple platforms (Discord, Slack, GitHub, etc.)

**Key Value Propositions:**
- Enhanced contributor experience
- Actionable community analytics
- Robust workflow automation

---

## 2. Getting Started: Quick Start Guide

### Step 1: Fork and Clone the Repository

1. **Fork** the [Devr.AI repository](https://github.com/AOSSIE-Org/Devr.AI) to your GitHub account.
2. **Clone** your fork locally:
   ```bash
   git clone https://github.com/<your-username>/Devr.AI.git
   cd Devr.AI
   ```

### Step 2: Set Up Your Development Environment

Devr.AI uses **Poetry** for Python dependency management. Ensure you have Python installed (refer to the [.python-version](./.python-version) file).

1. **Install Poetry** (if not already installed):
   ```bash
   curl -sSL https://install.python-poetry.org | python3 -
   ```
2. **Install dependencies** by running:
   ```bash
   poetry install
   ```
3. **Activate the virtual environment**:
   ```bash
   poetry shell
   ```

### Step 3: Running the Application and Tests

- **Backend and Frontend:**
  - The **backend** code is located in the `/backend` folder.
  - The **frontend** code is in the `/frontend` folder.
- **Run Tests:**
  - Execute the test suite from the project root:
    ```bash
    poetry run pytest
    ```
  - Ensure all tests pass before submitting your changes.

---

## 3. Repository Structure

Understanding the layout of the project helps you know where to find and update code or documentation:

- **`/backend`** – Contains the FastAPI backend, which includes the API Gateway, authentication modules, core processing engine, and integrations.
- **`/frontend`** – Houses the React.js frontend, including the dashboard and analytics UI.
- **`/docs`** – Documentation for installation, system architecture, API references, and more.
- **`/tests`** – Unit and integration tests ensuring code quality.
- **`.github`** – Contains CI/CD workflows, issue and PR templates, and additional community files.
- **Configuration Files:**
  - **`pyproject.toml`** and **`poetry.lock`** – Manage Python dependencies.
  - **`setup.cfg`** – Additional configuration settings.
  - **`.python-version`** – Specifies the required Python version. 

## 4. Contribution Workflow

### Making Your Changes

1. **Create a Branch:**  
   Always create a new branch for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Commit Your Changes:**  
   Write clear, concise commit messages that explain the intent of your changes:
   ```bash
   git add .
   git commit -m "Describe your change briefly"
   ```

3. **Push and Create a Pull Request:**  
   Push your branch to your fork and open a Pull Request (PR) against the `main` branch of [AOSSIE-Org/Devr.AI](https://github.com/AOSSIE-Org/Devr.AI):
   ```bash
   git push -u origin feature/your-feature-name
   ```
   In your PR, reference any related issues and provide a clear explanation of your changes.

### Review and Feedback

- A project maintainer will review your PR and may request changes.
- Please address feedback promptly and update your PR accordingly.

---

## 5. Reporting Issues and Suggesting Enhancements

### Bug Reports

- **Before Reporting:**  
  - Check if the issue already exists in our [Issues](https://github.com/AOSSIE-Org/Devr.AI/issues) tracker.
  - Provide detailed reproduction steps, logs, and environment details.

- **How to Report:**  
  - Open a new issue with a clear title and detailed description.
  - Label your issue appropriately (e.g., bug, enhancement).

### Enhancement Suggestions

- **Before Suggesting:**  
  - Search for existing suggestions to avoid duplicates.
  - Ensure your idea aligns with the overall vision of Devr.AI.

- **How to Suggest:**  
  - Open a new issue with a clear and descriptive title.
  - Provide a step-by-step explanation and, if possible, include screenshots or examples.

---

*Thank you for contributing to Devr.AI! Every contribution helps us improve community engagement and developer relations. If you have any questions, feel free to reach out on Discord or post in GitHub Discussions.*
```
