# Les fonctions

Le but ici est d'aider à comprendre les fonctions en les rendant plus interactives, saisissables.

## Qu'est ce?

Pour moi une _fonction_ est une _façon de transformer_. Par exemple, si on prend une fonction qui pour __n__ donne sont __double__. Je me demande comment tansformer __n__ en son __double__?

En mathématiques, ils vont simplement écrire

    ƒ(n) = 2n, n ∈ ℕ

Mais comment le programmer?

## En python

Pour écrire la fonction ci-dessus, en python ça donne:

```python
def f(n):
    return 2 * n
```

On peut même lui donner l'air plus mathématique:

```python
f = lambda n: n*2
```

Maintenant que l'on a défini une fonction, comment s'en servir? Il suffit simplement de remplacer le `n` du `f(n)` par un ℕ(entier naturel). Dans le shell python ou l'on a défini les fontions il suffit de saisir:

```python
>>> f(12)
24
```

