<h3 align="center">Pecunia - Budget App</h3>

<div align="center">

  [![Status](https://img.shields.io/badge/status-active-success.svg)]()

</div>

---

<p align="center"> Few lines describing your project.
    <br>
</p>

## 📝 Table of Contents

- [About](#about)
- [Guidelines](#guidelines)
- [Built Using](#built_using)
- [Authors](#authors)
- [Acknowledgments](#acknowledgement)

## 🧐 About <a name = "about"></a>

Pecunia is a budget management application designed to enable users to track and manager their personal finances in a simple and flexible way.

By enabling advanced customization of expenses categories. It aims to offer a tailor-made approach adapted for specific needs.
Unlike traditional banking applications or budget app that require you to link your bank accounts,
Pecunia allows users to management EVERYTHING by manually entering all their transactions.

This approach enables complete personalization and greater control over your personal finances.

## 📓 Guidelines

### Git Branch Strategy

### 📌 Naming Conventions

| Prefix | Usage |
| :-------: | :------:|
| **feat/** | New feature development |
| **fix/** | Bug fixes |
| **hotfix/** | Critical productions fixes |
| **docs/** | Documentation updates |
| **test/** | Testing-relating work |
| **refactor/** | Code refactoring |
| **chore/** | Maintenance and tooling |
| **poc/** | Proof of concept for feasibility testing |

#### 🔷 Examples

```git
feat/user-authentication
fix/navbar-alignment
docs/project-guidelines
chore/update-dependencies
```

#### 🔄 Workflow

##### 1. Main Branch

- `main: Production-ready code`
- `dev: Integration branch for new features`

##### 2. Feature workflow

- Create a branch : `git checkout -b feat/your-feature`
- Push and open a pull request to dev
- Merge or only after 2 approval review

##### 3. Proof of Concept (PoC) workflow

- Create a PoC branch : `git checkout -b poc/your-concept`
- Test feasibility before integrating into `feature/` branches
- if validated, merge into a feature branch or discard

### Commit Messages Conventions

#### Why use a structured commit format ?

A clear and consistent commit message format improves readability, history tracking and automation (e.g., changelogs, release notes, etc)

#### Conventionnal commit format

`<type>(<scope>): <message>`

##### 🔷 Types of commits

| Type | Usages |
| :------: | :-----:|
| **feat** | Introduces new feature |
| **fix** | Fixes a bug |
| **chore** | Maintenance or tooling updates |
| **docs** | Documentation changes |
| **test** | Adding or updating tests |
| **refactor** | Code improvement without changing behavior |
| **style** | Formatting changes (whitespace, linting) |
| **perf** | Performance improvements |
| **ci** | CI/CD related updates |

#### 📌 Examples

```git
feat(auth): add JWT authentication middlewares
fix(ui): resolve navbar rendering issue
chore(git): add logs to .gitgnore
docs(readme): update installation guide
```

## ⛏️ Built Using <a name = "built_using"></a>

- [MySQL](https://www.mysql.com/) - Database
- [SringBoot](https://spring.io/projects/spring-boot) - Server Framework
- [Angular](https://angular.dev/) - Web Framework

## ✍️ Authors <a name = "authors"></a>

- [@Alexia](https://github.com/AlexiaGu) - Fullstack Developper
- [@Daniel](https://github.com/danielgonzalez0) - Fullstack Developper
- [@Lenny](https://github.com/lenny-zanotelli) - Fullstack Developper
- [@Thomas](https://github.com/Thomas-Lunardo) - Fullstack Developper

## 🎉 Acknowledgements <a name = "acknowledgement"></a>

- Hat tip to anyone whose code was used
- Inspiration
- References
