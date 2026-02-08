```c
#include <stdio.h>

int main(void) {
    char username[9] = "decentcarp";
    char discorduser[9] = "r5900";
    char name[7] = "Eleanor";
    char country[14] = "United Kingdom";
    char codinglanguages[3][8] = {"C", "Bash", "Swift"};
    int age = 15;

    printf("Hi! I'm %s, also known as %s. (and on discord, %s.) I am a %d year old from the %s.\n", name, username, discorduser, age, country);
    printf("I am learning %s and I am learning a bit of %s. I have also started experimenting with %s\n", codinglanguages[0], codinglanguages[1], codinglanguages[2]);
    printf("Thanks for dropping by! :P");
  
    for (int i = 0; i < 10; i++) {
        printf("meow\n");
    }

    return 0;
}
```
