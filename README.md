<h1 align="center">Hi 👋,</h1>

```c
#include <stdio.h>
#include <string.h>

struct Student {
    char name[42];
    char alias[42];
    char school[42];
    char completed_projects[5][42];
};

void initializeStudent(struct Student *student) {
    strcpy(student->name, "Anthony Graille");
    strcpy(student->alias, "Lyricall");
    strcpy(student->school, "42 Lyon");
    strcpy(student->completed_projects[0], "Libft");
    strcpy(student->completed_projects[1], "Printf");
    strcpy(student->completed_projects[2], "Born2beroot");
    strcpy(student->completed_projects[3], "Get_Next_Line");
    strcpy(student->completed_projects[4], "Push Swap");
}

void introduceStudent(const struct Student *student) {
    printf("I ! I'm %s, alias %s.\n", student->name, student->alias);
    printf("Actually student at %s.\n", student->school);
    printf("Here are some projects I have completed :\n");
    for (int i = 0; i < 5; i++) {
        printf("- %s\n", student->completed_projects[i]);
    }
    printf("Thank you for visiting my profile, I hope you find my work interesting !");
}

int main(void) {
    struct Student me;
    initializeStudent(&me);
    introduceStudent(&me);

    return 0;
}
```
## 🔧 Technologies & Tools

<div align="left">

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=lyricallll&layout=compact)

# Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/anthony-graille-594385329/)
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:lachariotte30@gmail.com)



