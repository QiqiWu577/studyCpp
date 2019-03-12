In this second blog, I am going to share what I got during these days after studying c++ as a beginner. At the beginning stage, I thought learning c++ should be easy since the programming concepts behind it are so similar to Java, but when I am learning more detail about it I realized that it would take me a while to get used to the way that how to run a c++ program. However, it is good to keep learning new things as a developer. Now, let me introduce 3 important things you must to know about c++ as a beginner!

## General idea of C++
[C++](https://en.wikipedia.org/wiki/C%2B%2B) is a general purpose middle level using object-oriented programming language. Even though it was developed in 1979, it is still one of the most popular programming languages in the IT industry. One reason is that this language can have a control on direct manipulation of hardware so that it can increase the performance of the program, like allocate the memory resources and after the data structure is not going to use the programmer can deallocate the resouces. Another important reason is that there are still hundreds of thousands of programmers using C++ to develop a lot of interesting and cool programs, which drives C++ keeping moving forward to accomadate the change of Information Technology. For example, when you sereach C++ in Github, there are 137,935 repository results you can see. Also, this is a good news because it means there are lots of resources we can utilize to explore more about C++.

## How to use library of C++
How to use library in C++ program is the first problem coming out when I try to get closer to it. At some points, the concept of its library is very similar to Java. C++ has a standard library which is a reference for C++ programmer to use different useful functions to complete their project's features. Since I am more familiar with Java, I will use Java examples to compare with C++. 

Here is the simple example how to use functions in the Java [API](https://en.wikipedia.org/wiki/Application_programming_interface)
```markdown
import java.io.*;
private void saveFile() throws IOException {
		
		PrintWriter outputFile = new PrintWriter("res/database.txt");
}
```
In Java, programmers firstly `import` what kind of classes they want from the library and then in order to use the function defined in that class, programmers just need to instantiate the object of that class in the proper way.

Here is the example code for C++
```markdown
#include <iostream>
using namespace std;

int main( int argc, char * argv[] )
{
    cout << "Hello World!" << endl;
    return 0;
}
```
In C++, it use `#include` instead of `import` but has the same meaning. `using namespace` is telling the compiler that the subsequent code is making use of names in the specified namespace, which simply means it is calling what method inside of the class included. The main difference bewteen Java and C++ in terms of the use of library is that the programmer can have clear idea that what kind of object they are instantiating and where they come from because programmers have to specified the object before they can use it. In contrast, C++ does not require that, which is good for saving coding time, but for the programmer that is not very familiar with the objects of the C++ libary using this style of coding would be painful for the beginners as they do not know what `cout` used for. As a beginner, it is very important to know the basic point.

## Pointer in C++


## How to use memory management


## Summary
