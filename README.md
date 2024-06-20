# JavaUtilities

JavaUtilities is a command-line application that leverages built-in JavaScript tools/utilities to perform various tasks. This repository is designed to provide users with a list of tools to use (chewy-commands, pydebug, toolpackager [for JavaUtilities]) effectively in command-line applications.

## Features

- Parse and handle command-line arguments
- Write files
- Useful tools
- Ability to create your own tools (Note: Custom tools cannot be used in JavaUtilities yet)

## Requirements

- Node.js 14 or higher
- JavaScript Debugger (Nightly) if you're a VSCode user

## How to Use

### Installing

1. Download the official release from this GitHub repository.

### Running

- On Unix-based/like systems:
    ```sh
    bash ./JavaUtilities_Unix.sh [args]
    ```

- On Windows systems:
    ```sh
    JavaUtilities_Windows.bat [args]
    ```

### Accepted Command Line Arguments

- `-use-tool`
- `-built-in`
- `-get-version`

#### Tools

- `ToolPackager`
- `PyDebug`
- `chewy`
