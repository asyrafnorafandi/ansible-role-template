# Contributing to [Ansible Role Name]

First off, thank you for considering contributing to our Ansible role! Your contributions help make this project better for everyone.

The following is a set of guidelines for contributing to this repository. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

## Table of Contents

1. [How to Contribute](#how-to-contribute)
2. [Reporting Bugs](#reporting-bugs)
3. [Suggesting Enhancements](#suggesting-enhancements)
4. [Submitting a Pull Request](#submitting-a-pull-request)
5. [Code Style Guidelines](#code-style-guidelines)
6. [License](#license)

## How to Contribute

### Reporting Bugs

If you find a bug, please report it by opening an issue on GitHub. Provide as much detail as possible, including steps to reproduce the bug, the environment in which the bug occurs, and any relevant error messages.

### Suggesting Enhancements

If you have an idea for an enhancement or a new feature, please open an issue on GitHub with the suggestion. Describe your proposed enhancement in detail, including any specific use cases or examples.

### Submitting a Pull Request

1. **Fork the repository** and create a new branch for your feature or bugfix. It's best to create a branch with a descriptive name (e.g., `feature/add-logging-support` or `bugfix/fix-issue-42`).

2. **Write your code** with clear and descriptive commit messages.

3. **Test your changes** to ensure they work as expected and do not break any existing functionality. If applicable, add tests to verify the behavior of your code.

4. **Update the documentation** as needed, especially if your changes affect how users interact with the role.

5. **Create a pull request** on GitHub. In the pull request description, explain the changes you made and why they are necessary. Reference any related issues if applicable.

6. **Collaborate with reviewers** by addressing feedback and making any necessary revisions to your pull request. Be responsive and open to discussions to help improve the contribution.

### Code Style Guidelines

- **Ansible Best Practices**: Follow [Ansible Best Practices](https://docs.ansible.com/ansible/latest/user_guide/playbooks_best_practices.html) for structuring your playbooks, tasks, and roles.

- **YAML Syntax**: Use consistent indentation (2 spaces) and avoid trailing whitespaces. Keep YAML syntax clear and concise.

- **Documentation**: Ensure that any variables, defaults, or tasks are well-documented in the role's `README.md` or within the relevant files.

- **Idempotency**: Ensure that tasks are idempotent, meaning that running the role multiple times should not change the system's state if it has already been applied.

- **Testing**: If possible, add or update tests using a tool like [Molecule](https://molecule.readthedocs.io/) to verify the role's functionality. Tests help catch regressions and ensure that contributions work as expected.

### License

By contributing to this repository, you agree that your contributions will be licensed under the repository's [MIT License](./LICENSE).

## Thank You!

Thank you for your interest in contributing to our project! We value your time and effort, and we appreciate your help in making this Ansible role better for the community.
