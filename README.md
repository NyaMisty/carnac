# Carnac the Magnificent Keyboard Utility & Mouse Highlighter*

[![Build status](https://github.com/NyaMisty/carnac/actions/workflows/ci.yml/badge.svg)](https://github.com/NyaMisty/carnac/actions)

## (TL;DR) This is a unifying fork for https://github.com/Code52/carnac and other forks

**This repo has these EXTRA features**:

- Mouse Support (@bfritscher from https://github.com/bfritscher/carnac)
- Support Customizing Various Spacing (@NyaMisty)
- Fixed & Better Regex: (@kasajian, @DNIStream)
    - Resolved Code52#232 Fixed issue with RegEx process nmae filtering not… (from https://github.com/DNIStream/carnac/commit/47e3333d7708e6620c66564b3ec81fbd0e2503c0)
    - Adds support for filtering on sub-processes (from https://github.com/kasajian/carnac)
- Add GitHub Build CI

## Installation

- Method1: (Suggested) Using Scoop
    ```
    scoop bucket add nyamisty https://github.com/NyaMisty/scoop_bucket_misty.git
    scoop install carnac-misty
    ```

- Method2: Grab a Release from https://github.com/NyaMisty/carnac/releases

## Usage

**Enabling silent mode**

If you want to stop `Carnac` from recording certain key strokes, you can enter _silent mode_ by pressing `Ctrl+Alt+P`. To exit _silent mode_ you simply press `Ctrl+Alt+P` again.

## How to build

Either open sln Visual Studio 2022, or Run:

```
powershell .\build.ps1
```

## TODO

- Add more forks:
    - [ ] https://github.com/fshif/carnac