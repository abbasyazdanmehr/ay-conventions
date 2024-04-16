# My Conventions

This show some basic conventions as default for me.

# Comment Tags

- `TODO`: general notes for modifying later.
- `DEBUG` ... `ENDDEBUG`: instructions used to debug program.
- `TEST` ... `ENDTEST`: instructions used to test program.
- `BOOKMARK`: easy navigating between important lines of code.

# Git

## Commmit Template

commit template: `<type>(<scope>): <description>`.

- `(project)` is the name of root scope.

|       type        |           function             |                   example                 |
| :---------------- | -----------------------------  | :---------------------------------------- |
| `feat` | adding new feature. | `feat(components): add color box component.` |
| `modifeat` | change feature for improvements, new environments and ... . | `modifeat(services): change default ip address.` |
| `fix` | fixing bug. | `fix: prevent from multiple assignment.` |
| `test` | adding tests for features. | `test: add node field data change test.` |
| `docs` | modifying documents. | `docs: add git conventions document.` |
| `clean` | refactoring, do conventions, removing redundants and ... . | `clean(project): remove old screenshots.` |
| `chore` | miscellaneous commits. | `chore: modify .gitignore file.` |

# README

root scope `README.md` items:
- **Name**
  - **important notes and links**
    - **link to docs and references**
  - table of contents
- **Purpose**
  - **main idea and end user target**
  - **main views screenshots**
  - project lifetime
- **Dependencies**
  - os
  - **major languages and frameworks versions and details**
  - **packages versions and details**
  - [tool softwares]
- **Usage and Run Protocols and Notes**
- [Tests and Results]
- [Contribution Conventions]
- Contacts
- [Thanks]
