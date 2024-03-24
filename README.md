<!-- ### Hi there 👋 -->

<!--
**ThibaultNGUYEN26/ThibaultNGUYEN26** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

# My student profile at 42 Nice

```
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

