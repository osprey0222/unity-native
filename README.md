# Unity Native Scripting

A library to allow writing Unity scripts in native code: C, C++, assembly.

## Purpose

This project aims to give you a viable alternative to C#. Scripting in C++ isn't right for all parts of every project, but now it's an option.

## Goals

* Make scripting in C++ as easy as C#
* Low performance overhead
* Easy integration with any Unity project
* Fast compile, build, and code generation times
* Don't lose support from Unity Technologies

# Reasons to Prefer C++ Over C# #

## Fast Device Build Times

Changing one line of C# code requires you to make a new build of the game. Typical Android build times tend to be at least 10 minutes because IL2CPP has to run and then a huge amount of C++ must be compiled.

By using C++, we can compile the game as a C++ plugin in about 1 second, swap the plugin into the APK, and then immediately install and run the game. That's a huge productivity boost!

