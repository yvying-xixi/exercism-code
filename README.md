# Exercism Code

My solutions and notes for programming exercises from [Exercism](https://exercism.org/).

## Git Commit Convention

This repository follows the [Conventional Commits](https://www.conventionalcommits.org/) style.

### Recommended Types

The following commit types are commonly used in this repository:

| Type       | Description                                |
| ---------- | ------------------------------------------ |
| `feat`     | Add a new exercise or feature              |
| `fix`      | Fix an incorrect solution or bug           |
| `refactor` | Refactor code without changing behavior    |
| `docs`     | Update documentation or notes              |
| `test`     | Add or update tests                        |
| `perf`     | Improve performance                        |
| `build`    | Update dependencies or build configuration |
| `ci`       | Update CI/CD configuration                 |
| `chore`    | Other repository maintenance               |

### Recommended Template

Use the following format:

```text
<type>(<scope>): <description>
```

For example:

```text
feat(java): add hello-world exercise
fix(python): fix leap year calculation
refactor(java): simplify string processing
docs(readme): update repository documentation
test(java): add tests for calculator
perf(java): optimize list traversal
build(java): update dependencies
ci: add GitHub Actions workflow
chore: update gitignore
```

For simple changes, `scope` can be omitted:

```text
feat: add hello-world exercise
fix: correct exercise solution
docs: update readme
chore: update repository configuration
```

### Guidelines

* Use a clear and concise description.
* Prefer one logical change per commit.
* Use the programming language as `scope` when adding or modifying an exercise.
* Use `docs` for learning notes and documentation changes.
* Avoid vague messages such as `update`, `fix bug`, or `some changes`.

For Exercism exercises, the recommended format is:

```text
feat(<language>): add <exercise-name> exercise
```

Example:

```text
feat(java): add hello-world exercise
feat(python): add two-fer exercise
feat(cpp): add raindrops exercise
```

