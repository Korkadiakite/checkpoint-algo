# Checkpoint : Introduction aux algorithmes

## Objectif

Écrire un algorithme qui lit une phrase caractère par caractère afin de déterminer :

- La longueur de la phrase.
- Le nombre de mots.
- Le nombre de voyelles.

## Algorithme
ALGORITHME AnalysePhrase

DEBUT

    longueur ← 0
    mots ← 1
    voyelles ← 0

    Lire caractere

    TANT QUE caractere ≠ "."

        longueur ← longueur + 1

        SI caractere = " " ALORS
            mots ← mots + 1
        FIN SI

        SI caractere est une voyelle ALORS
            voyelles ← voyelles + 1
        FIN SI

        Lire caractere

    FIN TANT QUE

    longueur ← longueur + 1

    Afficher longueur
    Afficher mots
    Afficher voyelles

FIN

## Exemple de vérification

**Phrase utilisée :** Je suis une programmeuse.

**Résultats attendus :**
- Longueur : 25 caractères.
- Nombre de mots : 4.
- Nombre de voyelles : 10.