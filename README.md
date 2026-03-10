# 📚 libft

## 🗣️ À propos
Ce projet est le tout premier du cursus de l'école 42. Il consiste à recoder plusieurs fonctions de la bibliothèque standard C, ainsi que d'autres fonctions utilitaires. Le but est de comprendre leur fonctionnement, d'apprendre à manipuler la mémoire et les chaînes de caractères.

Cette bibliothèque sera utilisée dans la plupart des projets futurs du cursus.

## 🛠️ Fonctions implémentées

### Fonctions de la libc
- `ft_isalpha` - vérifier si un caractère est alphabétique.
- `ft_isdigit` - vérifier si un caractère est un chiffre.
- `ft_isalnum` - vérifier si un caractère est un chiffre ou une lettre.
- `ft_isascii` - vérifier si un caractère fait partie de la table ASCII.
- `ft_isprint` - vérifier si un caractère est imprimable.
- `ft_strlen` - calculer la longueur d'une chaîne de caractères.
- `ft_memset` - remplir une zone mémoire avec un octet donné.
- `ft_bzero` - mettre à zéro une zone mémoire.
- `ft_memcpy` - copier une zone mémoire.
- `ft_memmove` - copier une zone mémoire (gère les chevauchements).
- `ft_strlcpy` - copier une chaîne de caractères (sécurisé).
- `ft_strlcat` - concaténer une chaîne de caractères (sécurisé).
- `ft_toupper` - convertir un caractère minuscule en majuscule.
- `ft_tolower` - convertir un caractère majuscule en minuscule.
- `ft_strchr` - localiser un caractère dans une chaîne.
- `ft_strrchr` - localiser un caractère depuis la fin d'une chaîne.
- `ft_strncmp` - comparer deux chaînes de caractères.
- `ft_memchr` - localiser un octet dans une zone mémoire.
- `ft_memcmp` - comparer deux zones mémoire.
- `ft_strnstr` - localiser une sous-chaîne dans une chaîne.
- `ft_atoi` - convertir une chaîne de caractères en entier.
- `ft_calloc` - allouer de la mémoire et l'initialiser à zéro.
- `ft_strdup` - dupliquer une chaîne de caractères.

### Fonctions supplémentaires
- `ft_substr` - extraire une sous-chaîne.
- `ft_strjoin` - concaténer deux chaînes pour en créer une nouvelle.
- `ft_strtrim` - supprimer les caractères spécifiés au début et à la fin d'une chaîne.
- `ft_split` - diviser une chaîne en un tableau de chaînes selon un caractère séparateur.
- `ft_itoa` - convertir un entier en chaîne de caractères.
- `ft_strmapi` - appliquer une fonction à chaque caractère d'une chaîne (crée une nouvelle chaîne).
- `ft_striteri` - appliquer une fonction à chaque caractère d'une chaîne (modif sur place).
- `ft_putchar_fd` - écrire un caractère sur un descripteur de fichier.
- `ft_putstr_fd` - écrire une chaîne sur un descripteur de fichier.
- `ft_putendl_fd` - écrire une chaîne suivie d'un retour à la ligne sur un descripteur de fichier.
- `ft_putnbr_fd` - écrire un entier sur un descripteur de fichier.

## 🚀 Utilisation

1. Cloner le dépôt :
```bash
git clone https://github.com/thaygoo/libft.git
cd libft
```

2. Compiler la bibliothèque :
```bash
make
```

3. Cela générera le fichier `libft.a`. Pour l'utiliser, incluez `libft.h` dans votre code C et compilez votre programme avec `libft.a`.

```c
#include "libft.h"
```

```bash
gcc main.c libft.a
```

## 🧹 Commandes Makefile

- `make` ou `make all` : compile les sources et génère `libft.a`.
- `make clean` : supprime les fichiers objets (`.o`).
- `make fclean` : exécute `clean` et supprime `libft.a`.
- `make re` : exécute `fclean` puis recommence la compilation.