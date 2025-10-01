# Projet : Manipulation de listes chaînées en C

## Description
Ce projet regroupe plusieurs programmes en langage **C** qui traitent de la manipulation des **listes chaînées** (simples, doubles, circulaires).  
Chaque fichier source correspond à une fonctionnalité bien définie : suppression, insertion dans une liste triée, insertion en tête et en queue.

---

## Contenu du projet

### 1. Suppression d’occurrences dans une liste simplement chaînée
- **Fichier :** `supprimer_occurrences.c`  
- **Fonctionnalité :** Lire un élément et supprimer **toutes ses occurrences** dans une liste simplement chaînée.

### 2. Insertion dans une liste simplement chaînée triée
- **Fichier :** `insertion_simple_triee.c`  
- **Fonctionnalité :** Insérer un élément dans une **liste simplement chaînée** en maintenant l’ordre trié.

### 3. Insertion dans une liste doublement chaînée triée
- **Fichier :** `insertion_double_triee.c`  
- **Fonctionnalité :** Insérer un élément dans une **liste doublement chaînée** triée.

### 4. Insertion en tête et en queue dans une liste simplement chaînée circulaire
- **Fichier :** `insertion_simple_circulaire.c`  
- **Fonctionnalité :** Insérer un élément **au début** et **à la fin** d’une **liste simplement chaînée circulaire**.

### 5. Insertion en tête et en queue dans une liste doublement chaînée circulaire
- **Fichier :** `insertion_double_circulaire.c`  
- **Fonctionnalité :** Insérer un élément **au début** et **à la fin** d’une **liste doublement chaînée circulaire**.

---

## 🚀 Compilation et exécution

Chaque fichier peut être compilé indépendamment avec **gcc** :  

```bash
# Compilation
gcc supprimer_occurrences.c -o supprimer_occurrences
gcc insertion_simple_triee.c -o insertion_simple_triee
gcc insertion_double_triee.c -o insertion_double_triee
gcc insertion_simple_circulaire.c -o insertion_simple_circulaire
gcc insertion_double_circulaire.c -o insertion_double_circulaire

# Exécution
./supprimer_occurrences
./insertion_simple_triee
./insertion_double_triee
./insertion_simple_circulaire
./insertion_double_circulaire# Tp2
