<div align="center">
  <img src="https://raw.githubusercontent.com/SamyakMishra072/SamyakMishra072/main/assets/matrix.gif" alt="Matrix" width="100%">
</div>

<h1 align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=40&duration=3000&pause=1000&color=00FF00&center=true&vCenter=true&width=800&height=100&lines=Welcome+to+the+Digital+Realm;I'm+Samyak+Mishra;Aspiring+SDE+%7C+Code+Alchemist" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://raw.githubusercontent.com/SamyakMishra072/SamyakMishra072/main/assets/hacker.gif" width="200px">
  <br>
  <samp>
    「 Aspiring Software Development Engineer from India 」
    <br>
    「 Transforming caffeine into code since 2019 」
    <br>
    <br>
  </samp>
</p>

<div align="center">
  <img src="https://komarev.com/ghpvc/?username=SamyakMishra072&label=Profile%20Views&color=brightgreen&style=flat-square" alt="Profile Views">
</div>

<details align="center">
<summary><samp>&#9776; Connect with Me</samp></summary>

<p align="center">
  <p align="center">
    <a href="https://linkedin.com/in/samyak072" target="_blank">
      <img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">
    </a>
    <a href="https://www.instagram.com/samyak_072/" target="_blank">
      <img alt="Instagram" src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white">
    </a>
    <a href="mailto:samyakmishra072@gmail.com" target="_blank">
      <img alt="Gmail" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white">
    </a>
  </p>
</p>
</details>

<details align="center">
<summary><samp>&#9776; About Me</samp></summary>

```cpp
#include <iostream>
#include <vector>
using namespace std;

class CodeAlchemist {
private:
    string name = "Samyak Mishra";
    string role = "Aspiring Software Development Engineer";
    vector<string> skills = {"C++", "Java", "Python", "Machine Learning", "DSA", "OS Concepts"};
    vector<string> passions = {"Open-source", "Knowledge sharing", "Systems programming"};

public:
    void introduce() {
        cout << "Hello, World! I'm " << name << ", " << role << "." << endl;
    }

    void displaySkills() {
        cout << "Skills:" << endl;
        for (const auto& skill : skills) {
            cout << "  ⚡ " << skill << endl;
        }
    }

    void showPassions() {
        cout << "Passions:" << endl;
        for (const auto& passion : passions) {
            cout << "  🔥 " << passion << endl;
        }
    }

    void funFact() {
        cout << "Fun Fact: I dream of crafting my custom OS while diving into hacker-level coding adventures! 🖥️" << endl;
    }
};

int main() {
    CodeAlchemist me;
    me.introduce();
    me.displaySkills();
    me.showPassions();
    me.funFact();
    return 0;
}
