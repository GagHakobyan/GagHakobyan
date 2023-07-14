/* - 👋 Hi, I’m @GagHakobyan
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ... */
//leap year (nahanj tari)
#include <stdio.h>
 int main() {
    int year;

    printf("Enter a year: ");
    scanf("%d", &year);

    if (year % 4 == 0) {
        if (year % 100 == 0) {
          if (year % 400 == 0) {
             printf("%d is a leap year\n", year);
       } else {
         printf("%d is not a leap year\n", year);
      }
   } else {
            printf("%d is a leap year\n", year);
    }
    } else {
        printf("%d is not a leap year\n", year);
    }

    return 0;
}


<!---
GagHakobyan/GagHakobyan is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
