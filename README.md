# github_exploration

A repository that explores all the features provided by GitHub

<!-- Insert Badges Here -->

## About

## Architecture

## Building

### Cloning

The recommended way to clone the repository is to **`Clone with SSH`** with the option `recurse-submodules`:
```bash
git clone --recurse-submodules git@github.com:ei06125/github_exploration.git
```
This will clone the base repository and all its submodules/dependencies but not the submodules' submodules.

### Configuration

The project uses CMake to configure the build system.

To configure cmake through the command line:

#### Terminal
```bash
## Windows (git-bash)
cmake -S <path-to-source> -B <path-to-build>
## Example running from the project's root dir:
cmake -S . -B build/Windows
```

#### Visual Studio Code

<!-- TODO: Add VS Code settings with images -->

#### Visual Studio

<!-- TODO: Add Visual Studio settings with images -->


### Compilation

### Execution

## ChangeLog

<!-- Should we move this ChangeLog to the top? Breaks -->

| Version |    Date    |                                             Comment |
| ------- |    ----    | --------------------------------------------------- |
| v0.0.1  | 2022/11/23 | Initial Commit |
| (next)  | YYYY/MM/DD | TBA |

## Contribution

### Code of Conduct

<!-- TODO: TBD -->

### Code Reviews

<!-- TODO: TBD -->

### Pull Requests

<!-- TODO: TBD -->

## License

Check the [LICENSE](LICENSE)

## References

## Tools

This section contains extra tools that can help you to manage this project's development environment.

### Visual Studio

### VS Code

#### Extensions

<!-- TODO: Check how to save the recommended extensions in a settings file in `.vscode/` and sync with git. -->

These are the recommended extensions for using VS Code:
- C/C++ from Microsoft
- CMake Tools from Microsoft
- CMake from twxs
- cmake-format from cheshirekow
