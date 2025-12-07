---
title: Tableaux
order: 50
icon: lucide/table
---

## Tableaux : syntaxe de base

Les tableaux ont cette structure :

### 📄Code

```
| Janvier | Février | Mars |
|---------|---------|------|
| 100     | 200     | 300  |
| 400     | 500     | 600  |
```

Ou encore :

```
| Janvier | Février | Mars |
|-|-|-|
| 100 | 200 | 300 |
| 400 | 500 | 600 |
```

### ➡️Résultat

| Janvier | Février | Mars |
|---------|---------|------|
| 100     | 200     | 300  |
| 400     | 500     | 600  |

| Janvier | Février | Mars |
|-|-|-|
| 100 | 200 | 300 |
| 400 | 500 | 600 |


## Alignement des colonnes

Les colonnes peuvent être alignées à gauche, à droite, et centrées :

### 📄Code

```
| Gauche | Centré | Droite |
|:-------|:------:|-------:|
| 100    | 200    | 300    |
| 400    | 500    | 600    |
```

### ➡️Résultat

| Gauche | Centré | Droite |
|:-------|:------:|-------:|
| 100    | 200    | 300    |
| 400    | 500    | 600    |