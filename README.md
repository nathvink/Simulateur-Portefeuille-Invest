# Simulateur de portefeuille d'investissement

Application web autonome (un seul fichier : `simulateur-portefeuille.html`) pour simuler un portefeuille
d'investissement d'un particulier en France : backtest historique, projection Monte Carlo, indicateurs de
risque, tests de crise et fiscalité par enveloppe (PEA, compte-titres, assurance-vie).

**Utilisation :** ouvrez `simulateur-portefeuille.html` dans un navigateur. Aucun serveur ni clé d'API.
Une connexion internet est nécessaire uniquement pour charger Chart.js et la police Inter depuis un CDN.

**Personnalisation :** en haut du fichier, modifiez `PORTEFEUILLE_PAR_DEFAUT` (portefeuille chargé à
chaque ouverture), `PARAMETRES_FISCAUX` (taux à vérifier selon les lois de finances en vigueur) et
`HYPOTHESES` (frais, inflation). Les séries de marché sont dans `DONNEES_MARCHE`.

> Simulation à but éducatif, les performances passées ne préjugent pas des performances futures.
> Les données intégrées sont annuelles et en partie approximatives (voir l'onglet « Sources des données »).
