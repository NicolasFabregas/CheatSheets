## SUFFIXES
- u, U =unsigned
- f, F=floatting
- l, L=long int, long double
- ll, LL=long long int

## PREFIXES
- 0b=binary
- 0=octal
- 0x=hexadecimal

## Bit par défaut
- goodbit : 1
- failbit : 0
- badbit : 0

## Read input
- std::cin -> std::cin.good(), std::cin.fail(), std::cin.bad()
- std::cin.ignore()
- std::getline
- std::ws

## Symbole de calcul de dev
- arithmétiques : + - / %
- booléens : ! && || (par ordre de priorité ! puis && puis ||)
- comparaison : < <= == != >= >
- divers : += -= *= /= %= ++ --
- result=data++ //result <- 0 ; data + 1
- result=data++ // data + 1 ; result <- 1

## paramètres de méthodes
- var : passage par copie
- &var : passage par reference
- [=] : tout est passé par copie
- [&] : tout est passé par référence
- [&a, b] :a par reference, b par copie
- [&, b] : tout par reference, sauf b par copie
- [=, &b] : tout par copie, sauf b par reference
- mutable : permet de modifier les veriables
- noexcept : permet de ne pas déclencher d'exception
