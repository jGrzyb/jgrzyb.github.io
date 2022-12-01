---
layout: default
---


[mój profil]([./another-page.html](https://github.com/jGrzyb)).

# README.md

## Witam na mojej stronie!

Jest to projekt zrobioy w ramach przedmiotu Narzedzia Informatyczne na Krakowskiej uczelni AGH

### A tutaj kawałek mojego kodu:

```cpp

#include <windows.h>
#include <cstdio>
#include <conio.h>

using namespace std;

string board[21][21], board1[21];
void place();

int main()
{
    place();
    for(int i=0; i<21; i++)
    for(int j=0; j<21; j++)
    cout << i << ":" << j << " " << board[i][j] << "     ";
    return 0;
}

void place()
{
    for(int i=0; i<21; i++)
    {
        board[i][0]="| ";
        board[20][i]="__";
}
```
Mój team:

| Imie     | Nazwisko       | 
|:-------------|:------------------|
| Jakub | Grzyb |
| Gilbert | Guszcza |
| Jan | Gurgul |
| Tuko |  |

