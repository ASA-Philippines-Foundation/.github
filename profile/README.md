# ASA Philippines

Welcome to the official GitHub repository for ASA Philippines! We are dedicated to empower underserved communities by providing access to financial services and opportunities for sustainable economic growth. Through microfinance and social development programs, we aim to uplift individuals and families out of poverty, fostering entrepreneurship and financial independence. Our organization is committed to creating a positive impact on society by promoting financial inclusion, education, and community development.


## About Us

ASA Philippines is a dynamic and socially-driven organization dedicated to empowering marginalized communities across the country. Our mission is to alleviate poverty by providing accessible and responsible financial services to individuals who lack access to traditional banking. Through our microfinance and social development programs, we strive to create pathways out of poverty, fostering entrepreneurship, and enabling sustainable livelihoods.

Our goals are centered around:
- Enabling financial inclusion for underserved populations.
- Empowering individuals through microloans and financial literacy.
- Facilitating community development and social impact initiatives.
- Cultivating a culture of entrepreneurship and self-reliance.

Guided by our core values of integrity, inclusivity, innovation, and social responsibility, we are committed to making a meaningful difference in the lives of our clients and the communities we serve. By providing financial tools, education, and support, we aim to create a brighter and more equitable future for all members of society.


## Repositories

Here are some of the key repositories in our organization:

- [Asa Web Application](https://github.com/ASA-Philippines-Foundation/asa-web): A Data Collection Sheet (DCS) Web Application.

# Development Guidelines

Welcome to [Your Organization/Project Name]! This document outlines the best practices and guidelines for development, including Git branch strategy, commit messages, and other important considerations.

## Git Branch Strategy

We follow a branching model that helps us manage code changes and collaborate effectively. Here are the key branches and their purposes:

- `main`: The main integration branch containing stable and tested code. No direct commits.
- `feature` : The feature branch where main branch is to merged here which is already reviewed by senior developers.
- `development`: The branch for ongoing development. Feature branches are typically merged here once tested by product owners.

### Feature Branches

- Prefix feature branch names with `feature/`.
- Example: `feature/user-registration`.

### Bug Fix Branches

- Prefix bug fix branch names with `bugfix/`.
- Example: `bugfix/login-issue`.

### Hotfix Branches

- Prefix hotfix branch names with `hotfix/`.
- Example: `hotfix/security-update`.

### Release Branches

- Prefix release branch names with `release/`.
- Example: `release/1.0.0`.

## Git Commit Messages

Clear and descriptive commit messages help us understand changes at a glance. Follow these guidelines:

- Use the imperative mood (e.g., "Add," "Fix," "Update") for the summary.
- Keep the summary line under 72 characters.
- Separate summary from description with a blank line.
- Provide context and details in the description.
- Reference relevant issues or JIRA IDs when applicable.

### Commit Types
- `feat` : a new feature is introduced with the changes
- `fix` : a bug fix has occurred
- `chore` : changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
- `refactor` : refactored code that neither fixes a bug nor adds a feature
- `docs` : updates to documentation such as a the README or other markdown files
- `style` : changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
- `test` : including new or correcting previous tests
- `perf` : performance improvements
- `ci` : continuous integration related
- `build` : changes that affect the build system or external dependencies
- `revert` : reverts a previous commit

### Examples

- `feat: Add user registration feature`
- `fix: Fix login validation edge case`

## Best Practices

- Write clean, modular, and well-documented code.
- Use meaningful variable and function names.
- Follow the coding style and conventions defined in our [Coding Standards](https://www.tatvasoft.com/blog/node-js-best-practices/).
- Write unit tests for your code and ensure they pass before submitting a pull request.
- Keep pull requests small and focused on a single task or feature.
- Review and test your code before submitting a pull request.
- Collaborate and communicate with team members using pull request comments and discussions.

## Additional Resources

- [Git Documentation](https://git-scm.com/doc)
- [How to Write a Git Commit Message](https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/)
- [GitHub Flow Guide](https://guides.github.com/introduction/flow/)

Remember, these guidelines are meant to facilitate collaboration and maintain a high code quality standard. Feel free to ask questions or suggest improvements at any time.

Happy coding!
