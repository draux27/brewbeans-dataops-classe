# Brew Beans — David Raux

## Objectif

Corriger la vente BB-041 de 40,00 € à 45,00 €.

## Données

43 transactions et un chiffre d’affaires de 453,20 €.

## Exécution

Avec Python et pandas, depuis la racine du dépôt.

```bash
python scripts/david-raux/preparer_ventes.py
```

## Vérifications

Contrôle BB-041 : montant corrigé à 45 EUR.

- Vérifier que BB-041 passe de 40 EUR à 45 EUR.
- Vérifier le total de 43 transactions et 453,20 EUR.

## Ressource

[pandas](https://pandas.pydata.org/docs/)
