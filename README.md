# Bienvenue

Programme C++ qui affiche "Bienvenue le monde !" en utilisant la fonction `afficherBienvenue()`.

## Compilation
```sh
$ make rebuild
Fabrication du programme : bienvenue
rm -f *.o
g++ -c -Wall -std=c++11 bienvenue.cpp
g++ -c -Wall -std=c++11 fonction-bienvenue.cpp
g++ -o bienvenue bienvenue.o fonction-bienvenue.o
```

## Exécution
```sh
$ ./bienvenue
Bienvenue le monde !
```
## Code source

### fonction-bienvenue.h
```cpp
#ifndef FONCTION_BIENVENUE_H
#define FONCTION_BIENVENUE_H

void afficherBienvenue();

#endif // FONCTION_BIENVENUE_H
```
Mise à jour pour la version 1.2

