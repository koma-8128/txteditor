Project Goal
To simplify C# coding and easily convert scripts into executable (.exe) files.

Settings
You can switch between Japanese and English via 設定(Setting).

Important: File Dependencies
txteditor.exe requires launcher.exe to function. They must be kept in the same directory.

launcher.exe can be used as a standalone application (it does not require txteditor.exe to run).

How to Use
>>Option A: Using txteditor.exe (Recommended)
Add your C# code to the designated area.

Click RUN to test and generate the file.

Note: You do not need to run launcher.exe manually when using the editor.

Caution: The code.c file in the directory will be overwritten every time you click RUN.

>>Option B: Manual Method (Without txteditor.exe)
Rename your source file to code.c.

Place it in the same directory as launcher.exe.

Run launcher.exe.

<Common to both Option A and B>
Output
Output: If your code executes without errors, the program will run and "temp_run.exe" will be created simultaneously.

This is a standalone file that includes both the launcher and your code.

Reminder: Although the file extension is .c, the language used is C#.

Code Example
~~~
MessageBox.Show("Hello World");
~~~
