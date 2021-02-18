# C++ Tutorial  
## Tools you may Require  
* MinGW Compiler  
* Visual Studio Community 2019  
* Notepad++  
* Visual Studio Code  
## Introduction  
C++ is a multipardigm procedural and object-oriented programming language. It is compiled and high-level even though it can do all low-level things C can do such as writing the kernel of an operating system and it is widely used in game development and Windows development. It executes all commnds very fast and we can allocat memory however we want.  
## Basic "Hello World"  

```C++
#include <iostream> // a c++ header file, available in C:/MinGW/lib/gcc/mingw32/6.3.0/include/c++ for mingw and C:/Program Files (x86)/Microsoft Visual Studio/2019/Community/VC/Tools/MSVC/14.28.29333/include on Visual Studio
using namespace std; // after using this there is no need to declare the std namespace if not used cout will become std::cout and end will become std::endl

int main() { //unlike C you can not use void main() here or else copiler shows error
    cout << "Hello World";
    return 0;
}
```  
If we use the exit code it will become like this.  
```C++
#include <iostream>
#include <conio.h>
using namespace std;

int main() {
    cout << "Hello World << endl; //endl means new line and flush together
    getch();
    return 0;
}
```
[Next](https://arin-torney.github.io/cppt/basics2.md "Next")
