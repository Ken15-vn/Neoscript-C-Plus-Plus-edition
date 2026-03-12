🌍 NeoScript C++ Edition

NeoScript C++ Edition is a branch of [NeoScript Stable Release v1.0](https://github.com/Ken15-vn/Neoscript-stable-release-v1.0) rewritten in C++

📜 Current Commands:

- write "message": Output text or variable values to the console.
- input "variable": Prompt user for numeric input.
- input_str "variable": Prompt user for string/text input.
- set "name" value: Initialize a numeric or string variable.
- add "name" value/variable: Add a value or another variable to a variable.
- sub "name" value/variable: Subtract a value or another variable from a variable.
- wait X: Pause program execution for X seconds.
- clear: Clear the entire console window for a fresh workspace.
- color "name": Change the text color (e.g., color "cyan", "green", "red").
- note "message": Add non-executable notes/comments to your script.

🛠️ System Requirements:

- Windows 10/11 (64-bit recommended).
- Microsoft Visual C++ Redistributable (Required to run the compiled executable).
- Internet connection (Only for initial setup and downloading tools).

💡 Recommendation:

For the best development experience, we recommend using the following tools:
- [Visual Studio Code](https://code.visualstudio.com/) (Lightweight & Powerful)
- [Visual Studio 2026 Community](https://visualstudio.microsoft.com/) (Full IDE features - Used for this version)

🚀 How to Use (4 Steps):

1: Download: Download the latest release package and extract it to your project folder.

2: Environment: Ensure you have the Microsoft Visual C++ Redistributable installed (usually included with Windows or game launchers).

3: Code: Open ide.ns with any text editor (like Notepad or VS Code) and write your NeoScript commands.

4: Run: Double-click run.bat (which now calls the compiled executable) to see your code in action.

📜 File Structure:

Neoscript.exe: The high-speed compiled interpreter (Written in C++).

ide.ns: Your script file where you write your NeoScript code.

run.bat: The quick-launch file for easy execution.

src/ (Optional): Folder containing the C++ source code (main.cpp, etc.) for those who want to build it themselves.


Open Source Project
