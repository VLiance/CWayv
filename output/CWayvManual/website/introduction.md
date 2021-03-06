## 1 Introduction

﻿
## 1.1  What is C·Wayv?

C·Wayv consists of a high-level programming language, inspired of Action Script & Haxe like language, usually symbolized with a "Wave arrow" (C↝) as title or simply with a tilde (C~) 

Based on C++, acting like an overlay, it's possible to mix C~/C++. You can also interact with GLSL and Javascript, in a single file, variables from different languages are inter-accessible.

C~, is strongly typed to have robust code and best performances. Main goal is to easily have a single code-base which compiles to multiple targets.

It use the powerful [Cwc](https://github.com/VLiance/Cwc) intelligent compiler, which achieve outstanding performances using highly optimized C++ compiler in backend. 

Also this provide the ability to generate any platform output binary since a multitude of backend toolchain can be selected.

Currently, there is the available [toolchains](https://github.com/VLianceTool) :
 

Toolchain  |  From  |  Target 
 --- | --- | ---
[LibRT](https://github.com/VLianceTool/LibRT)   | Windows  | Windows, Linux 
libRT(Debian)  | Linux  | Linux, Windows 
 

Haxe abstracts away many target differences, but sometimes it is important to interact with a target directly, which is the subject of target-details.
## 1.2 Getting Started

The following program in C~, prints "Hello World" after being compiled and run:

```haxe
class Main {
  public function Main():Void {
    Debug.fTrace("Hello World");
  }
}
```

This can be easily tested  by saving the above code to a file named `Main.cw` and invoking the Cwc Compiler
## 1.2.1 Required tools

Compilation process is greatly simplified, Cwc is the unique tool you need to build your code. 

Grab the last version of [Cwc compiler](https://github.com/VLiance/Cwc/releases)   

Unzip archive, and run Cwc
## 1.2.2 First use of Cwc

First Cwc ask for:

- Demos: Feel free to learn from example. 

See download section

- Setting the Cwc path to your environement. This is usefull when you need to access to Cwc from anywhere in Command-line


Previous section: [Introduction](introduction.md)

Next section: [Basic Types](types-basic-types.md)