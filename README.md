# Not Another Simple Static String Implementation
## Introduction
This is a simple implementation of a c++ static string class that strongly relies on the standard library.

## Usage 
The lib is implemented as a very basic header only library. To use it, simply include the header file in your project and you are good to go.

# Code Examples

Creating a static string is as easy as :
```cpp
auto str = "hello"_ss;
```

You can easily use it with a switch statement:
```cpp
switch(str)
{
    case "hello"_ss:
        std::cout << "Hello World" << std::endl;
        break;
    default:
        std::cout << "Default" << std::endl;
        break;
}
```

# Collaborating
Don't hesitate to open an issue or a pull request if you find a bug or want to add a feature to this project.

# License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE) file for details

# Mentions 
The hashing methods I used are based on this stack overflow thread
