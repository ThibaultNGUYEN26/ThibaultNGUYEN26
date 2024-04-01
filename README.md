![banner](https://github.com/ThibaultNGUYEN26/ThibaultNGUYEN26/blob/main/githubBanner.png)

# Welcome to My GitHub Profile! 👋
Hello! I'm Thibault NGUYEN, a student at 42 Nice passionate about coding and technology. Feel free to explore my repositories and connect with me!

## 🚀 About Me

```cpp
#include <iostream>
#include <vector>
#include <string>

class SoftwareEngineer {

private:
    std::string name;
    std::string role;
    std::vector<std::string> languageSpoken;

public:
    SoftwareEngineer() : name("Thibault NGUYEN"), role("Software Engineer"), languageSpoken({"fr_FR", "en_US"}) {}

    void sayHi() const {
        std::cout << "Hello ! My name is" << name << "\nWelcome to my GitHub profile !" << std::endl;
    }

};

int main() {
    SoftwareEngineer me;
    me.sayHi();

    return 0;
}
```

