# azure2git-tools <!-- omit in TOC -->
Add branching and commit tools in dev azure

- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installing](#installing)
- [Samples](#samples)
  - [Branch names](#branch-names)
- [Commit message template](#commit-message-template)
  - [Default story commit message template](#default-story-commit-message-template)
  - [Default bug commit message template](#default-bug-commit-message-template)
- [Authors](#authors)
- [License](#license)

## Getting Started

- Install browser plugin [tampermonkey](https://www.tampermonkey.net/)
- Install azure2git-tools script from [openuserjs.org](https://openuserjs.org/scripts/va4ok/azure2git)
- Open azure board
- Open card ticket
- See new buttons and dropdowns

### Prerequisites

To work with azure2git-tools it is required browser plugin [tampermonkey](https://www.tampermonkey.net/) to be installed

### Installing

- open [OpenUserJS](https://openuserjs.org/scripts/va4ok/azure2git) page
- install azure2git-tools as full or minified script
- done

OR

- copy user script from [git page](https://github.com/va4ok/azure2git-tools/blob/main/dist/azure2git.user.js)
- open tampermonkey plugin settings page in your browser
- create new user script and paste copied script
- save script
- done

## Samples
### Branch names
```
feature/777888_create_azure2git-tools
bugfix/88997_dropdown_broken
```
## Commit message template
### Default story commit message template
```
feat(777888): What new has implemented

777888 Create azure2git-tools
https://dev.azure.com/////_workitems/edit/777888
``` 
### Default bug commit message template
```
fix(777888): What was fixed

777888 Dropdown broken
https://dev.azure.com/////_workitems/edit/777888
```

Other prefixes are available `build, chore, ci, docs, perf, refactor, revert, style, test` as options

## Authors

* **Oleg Vaka** - *Initial work* - [va4ok](https://github.com/va4ok)

## License

This project is licensed under the MIT License - see the [LICENSE](./LICENSE) file for details
