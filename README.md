# Détection d'Anomalies sur Séries Temporelles Industrielles

Ce projet présente deux approches complémentaires pour la surveillance de données de capteurs.

1. **Détection par Point (Z-Score Glissant)** : 
   - Surveillance en temps réel des pics et anomalies soudaines.
   - Utilisation d'une fenêtre glissante pour s'adapter à la dérive du signal.

2. **Détection par Forme (Profile Monitoring)** :
   - Analyse globale de la courbe.
   - Calcul de la distance MSE (Mean Squared Error) par rapport à un profil moyen de référence.

## Librairies utilisées
- **Pandas / NumPy** : Manipulation des séries temporelles.
- **Matplotlib** : Visualisation des alertes.

## Résultats
Le notebook génère des visualisations permettant de distinguer les cycles de production conformes des anomalies.
