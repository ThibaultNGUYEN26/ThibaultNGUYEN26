#Welcome to My GitHub Profile! 👋
Hello! I'm Thibault NGUYEN, a Software Engineer passionate about coding and technology. Below is a small C++ program that represents a bit of what I do and my enthusiasm for programming. Feel free to explore my repositories and connect with me!

#🚀 About Me

```cpp
#include <iostream>
#include <vector>
#include <string>

class SoftwareEngineer {

private:
    std::string firstName;
    std::string name;
    std::string role;
    std::vector<std::string> languageSpoken;

public:
    SoftwareEngineer() {
        firstName = "Thibault";
        name = "NGUYEN";
        role = "Software Engineer";
        languageSpoken = {"fr_FR", "en_US"};
    }

    void sayHi() const {
        std::cout << "Hello ! My name is" << fisrtName << " " << name << "\nWelcome to my GitHub profile !" << std::endl;
    }

};

int main() {
    SoftwareEngineer me;
    me.sayHi();

    return 0;
}
```

