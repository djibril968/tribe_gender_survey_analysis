# Contributing Guide

Thank you for considering contributing to our project! We welcome contributions of all kinds, including bug fixes, new features, and improvements to our documentation. Please follow the guidelines below to ensure a smooth contribution process.

- [Contributing Guide](#contributing-guide)
  - [Getting Started](#getting-started)
    - [Working with Data](#working-with-data)
    - [1. Fork the Repository](#1-fork-the-repository)
    - [2. Clone Your Fork](#2-clone-your-fork)
    - [3. Create a Branch](#3-create-a-branch)
  - [Setting Up the Development Environment](#setting-up-the-development-environment)
      - [Linux/Mac](#linuxmac)
      - [Windows](#windows)
    - [2. Install Dependencies](#2-install-dependencies)
    - [3. Run JupyterLab](#3-run-jupyterlab)
  - [Making Changes](#making-changes)
  - [Submitting a Pull Request](#submitting-a-pull-request)
  - [Community Engagement](#community-engagement)
  - [Reporting Issues](#reporting-issues)


## Getting Started

### Working with Data

All data files should be placed in the data directory. This directory is protected by .gitignore to prevent accidental commits of potentially large or sensitive data files.

- Data Directory: Place your data files in the data directory.
- Data Management: Treat all data with care. Ensure data privacy and security practices are followed.
- Data Backup: Regularly back up your data to avoid any loss during development.

### 1. Fork the Repository
Fork the repository on GitHub to your own account.

### 2. Clone Your Fork
Clone your fork to your local machine:
```sh
git clone https://github.com/TribeDataTeam/tribe_gender_survey_analysis.git
cd tribe_gender_survey_analysis
```

### 3. Create a Branch
Create a new branch for your work:
```sh
git checkout -b feature-or-bugfix-name
```

## Setting Up the Development Environment

1. Create and Activate a Virtual Environment

#### Linux/Mac
```sh
python3 -m venv env
source env/bin/activate
```

#### Windows
```sh
python -m venv env
.\env\Scripts\activate
```

### 2. Install Dependencies
Install the project dependencies:
```sh
pip install -r requirements.txt
```

### 3. Run JupyterLab
Start JupyterLab to begin your analysis and development:
```sh
jupyter lab
```

## Making Changes

1. **Code Style**: Please adhere to the existing coding style and conventions used in the project.
2. **Testing**: Ensure that your code passes all existing tests and add new tests for your changes.
3. **Commit Messages**: Write clear and concise commit messages. Follow the convention:
   ```
   Short summary of the commit
   ```
4. **Push Changes**: Push your changes to your forked repository:
   ```sh
   git push origin feature-or-bugfix-name
   ```

## Submitting a Pull Request

1. Go to the repository on GitHub.
2. Click on the "Compare & pull request" button.
3. Provide a clear description of your changes and any related issue numbers.
4. Submit the pull request.

## Community Engagement

- **Respect**: Treat everyone with respect. Be considerate of differing viewpoints and experiences.
- **Collaboration**: Work together to improve the project. Offer and seek help when needed.
- **Communication**: Be clear and concise in your communications. Use GitHub issues and pull requests for project-related discussions.

## Reporting Issues

If you encounter any issues, please report them using the [GitHub Issues](https://github.com/your-username/project-name/issues) feature. Provide as much detail as possible to help us understand and resolve the issue.
