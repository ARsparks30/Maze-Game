# Maze-Game

Maze Game Exe using C++

CLI command to create the .exe file to play the game:
'g++ cgv_project.cpp glut32.lib -lopengl32 -lglu32'

How to resolve GL/glut.h no such file or directory?

1. After installation of MinGW., Add the Path to the path enviornment variable
2. Add 'glut.h' to C:\MinGW\Include\GL
3. Add glut32.dll to C:\Windows\SysWOW64
4. Add glut32.lib to the project folder
5. Compile with 'g++ cgv_project.cpp glut32.lib -lopengl32 -lglu32'

Find the glut-3.7.6-bin.zip for all the lib files for Glut.
