# Funcy Syntax Highlighting Extension for Visual Studio Code

This extension provides syntax highlighting for the Funcy programming language. Funcy is a Python-inspired scripting language designed for simplicity, flexibility, and logical coding.

## Features

The syntax highlighting includes:
- Keywords
- Strings
- Comments
- Block Comments
- Numbers
- Variables
- Functions

![image](https://github.com/user-attachments/assets/c6a1031b-0bbf-4311-a682-8694adcd0923)


## Installing

You can either download the pre-packaged `.vsix` file and apply it in VSCode, or package the extension yourself using `vsce`. Follow the instructions below for your preferred method.

---

### Option 1: Installing the Pre-Packaged `.vsix` File

1. **Download the `.vsix` File**:
   - Obtain the `.vsix` file from the GitHub repository.

2. **Install the Extension in VSCode**:
   - Open Visual Studio Code.
   - Press `Ctrl+Shift+P` (or `Cmd+Shift+P` on macOS) to open the **Command Palette**.
   - Type `Extensions: Install from VSIX...` and select it from the dropdown.
   - Browse to the location of the `.vsix` file, select it, and click **Open**.
   - The extension will be installed, and you can start using it immediately.

---

### Option 2: Packaging the Extension Yourself

If you'd like to package the extension from source, follow these steps:

#### 1. Install `vsce`

`vsce` (Visual Studio Code Extensions) is a command-line tool for packaging and publishing extensions.

- Install `vsce` globally using npm:

    ```bash
    npm install -g vsce
    ```
    > Tip: If `npm` is not available, download and install [Node.js](https://nodejs.org/en), which includes `npm`.

#### 2. Package the Extension

1. Navigate to the root directory where the `package.json` is located.
2. Run the following command:
   ```bash
    vsce package
    ```
    The command will generate a `.vsix` file (e.g., `funcy-lang-0.0.x.vsix`) in the same directory.

#### 3. Install the Packaged Extension

1. Open Visual Studio Code
2. Press `Ctrl+Shift+P`  (or `Cmd+Shift+P` on macOS) to open the **Command Palette**
3. Type `Extensions: Install from VSIX...` and select it
4. Locate the `.vsix` file you generated and click **Open** to install the extension
