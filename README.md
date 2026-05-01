<div align="center">

# Hi, I'm Mati Revollo! 👋

### 🎓 Student of Computer Engineering at Universidad Mayor de San Simón
### 📚 Teaching Assistant for Introduction to Programming

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FF5733&center=true&vCenter=true&width=435&lines=Java+Developer;Rubik's+Cube+Enthusiast;Swimming+is+life;Big+Pok%C3%A9mon+Fan" alt="Typing SVG" />

---

## 💻 About Me

</div>

```java

public class Mati {
    private int age;
    private String role;
    private String[] languages;
    private String[] favoriteIDEs;
    public Mati(int age, String role, String[] languages, String[] favoriteIDEs) {
        this.age = age;               
        this.role = role;             
        this.languages = languages;
        this.favoriteIDEs = favoriteIDEs;
    }
    public static void main(String[] args) {
        String[] myLanguages = {"Java", "Python", "C++", "JavaScript"};
        String[] myIDEs = {"BlueJ", "Thonny", "Notepad", "VS Code", "cmd", "CodeBlocks"};
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
