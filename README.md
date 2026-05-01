<div align="center">

# Hi, I'm Mati! 👋

### 🎓 3rd Semester Computer Engineering Student at Universidad Mayor De San Simón
### 👨‍🏫 Teaching Assistant for Introduction to Programming
<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2500&pause=800&color=FF5733&center=true&vCenter=true&width=500&lines=Computer+Engineering+%40+UMSS+🎓;Teaching+Assistant+👨‍🏫;Competitive+Programmer+⚡;Rubik%27s+PB%3A+38.67s+🧩;Bulbasaur+fan+🌿;Cochabamba%2C+Bolivia+🇧🇴" alt="Typing SVG" />
---

## 💻 About Me

</div>
```
java
public class Mati {
    private int age;
    private String role;
    private String[] languages;
    private String[] favoriteIDEs;

    Mati(int age, String role, String[] languages, String[] favoriteIDEs) {
        this.age = age;               
        this.role = role;             
        this.languages = languages;
        this.favoriteIDEs = favoriteIDEs;
    }
    static void main(String[] args) {
        String[] myLanguages = {"Java", "Python", "C++", "JavaScript"};
        String[] myIDEs = {"BlueJ", "Thonny", "VS Code", "Terminal", "CodeBlocks"};
        
        Mati mati13752933 = new Mati(19, "Computer Engineering Student @ UMSS", 
                                      myLanguages, myIDEs);      
        mati13752933.printFavoritePokemon();
        mati13752933.printRubiksRecord();
    }
    void printFavoritePokemon() {
        System.out.println("Bulbasaur <3");
    }
    void printRubiksRecord() {
        System.out.println("0:38:67"); 
    }
    void getCity() {
        System.out.println("Cochabamba, Bolivia");
    }
}
