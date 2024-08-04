# [Librairie PyMuPDF](https://pypi.org/project/PyMuPDF/)

Cette librairie permet d'extraire du PDF.

À cela, il y a plusieurs possibilités :

- Soit extraire du texte pour obtenir une synthèse, pour traduire, ... : cette situation se fera au cas par cas
- Soit extraire des données chiffrées

Pour extraire les données chiffrées, on a 2 possibilités :

- Si la librairie ne reconnaît pas les tables dans le fichier -> recours au Power Query
- Si la librairie trouve des tables :
  - Soit l'extraction porte sur des données qu'on peut automatiser (exemple les liasses pour les recouper avec less données comptabless)
  - Soit l'extraction est effectuée de manière ponctuelle (donc pas d'automatisation d'extraction des données)

Date : 18/02/2024

Éditeur : Laurent REYNAUD
