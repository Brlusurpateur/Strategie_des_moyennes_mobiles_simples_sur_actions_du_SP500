# Trading Strategy Using Moving Averages

### Description
Ce projet implémente une stratégie de trading basée sur les moyennes mobiles (SMA) pour les actions du S&P 500. Il utilise des bibliothèques Python telles que pandas, yfinance, statsmodels, et matplotlib pour récupérer les données boursières, calculer les moyennes mobiles, générer des signaux d'achat et de vente, et visualiser les résultats.

### Prérequis
Assurez-vous d'avoir Python installé sur votre système. Vous aurez également besoin des bibliothèques suivantes :
- pandas
- pandas_datareader
- yfinance
- statsmodels
- matplotlib
- pandas_ta
- scikit-learn
- numpy
- ssl (inclus avec Python)

Vous pouvez installer les bibliothèques nécessaires avec pip :
pip install pandas pandas_datareader yfinance statsmodels matplotlib pandas-ta scikit-learn

## Fonctionnalités
- Téléchargement des données : Récupère les données des actions S&P 500 depuis Yahoo Finance.
- Calcul des moyennes mobiles : Calcule les moyennes mobiles de 50 et 200 jours des prix de clôture des actions.
- Application de la stratégie de trading : Génère des signaux d'achat et de vente basés sur les croisements des moyennes mobiles.
- Visualisation : Affiche les signaux de trading et les moyennes mobiles sur un graphique pour une action spécifique.

## Notes
- Les avertissements sont ignorés pour éviter des messages inutiles dans la console.
- La vérification SSL est désactivée pour éviter les erreurs de certificat, mais cela n'est pas recommandé pour une utilisation en production.

## Auteurs
Brandon Moncoucut