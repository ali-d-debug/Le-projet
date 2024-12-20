# Documentation de my_module

## Description du module
Ce module Python effectue des opérations arithmétiques de base comme l'addition, la soustraction, la multiplication, la division, le modulo et la puissance.

## Fonctions

### `add(a: float, b: float) -> float`
Additionne deux nombres.

#### Paramètres
- `a`: Premier nombre.
- `b`: Deuxième nombre.

#### Retour
- Retourne la somme de `a` et `b`.

### `subtract(a: float, b: float) -> float`
Soustrait un nombre d'un autre.

#### Paramètres
- `a`: Premier nombre.
- `b`: Deuxième nombre.

#### Retour
- Retourne la différence entre `a` et `b`.

### `multiply(a: float, b: float) -> float`
Multiplie deux nombres.

#### Paramètres
- `a`: Premier nombre.
- `b`: Deuxième nombre.

#### Retour
- Retourne le produit de `a` et `b`.

### `divide(a: float, b: float) -> float`
Divise un nombre par un autre.

#### Paramètres
- `a`: Numérateur.
- `b`: Dénominateur.

#### Retour
- Retourne le quotient de `a` et `b.

#### Exceptions
- Lève une `ValueError` si `b` est zéro.

### `modulo(a: int, b: int) -> int`
Calcule le reste de la division entière de deux nombres.

#### Paramètres
- `a`: Dividende.
- `b`: Diviseur.

#### Retour
- Retourne le reste de la division de `a` par `b`.

#### Exceptions
- Lève une `ValueError` si `b` est zéro.

### `power(a: float, b: float) -> float`
Calcule la puissance d'un nombre.

#### Paramètres
- `a`: Base.
- `b`: Exposant.

#### Retour
- Retourne le résultat de `a` élevé à la puissance `b`.
