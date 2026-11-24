# Heurêka — Mes heures / Mijn uren

Compteur d'heures personnel, bilingue FR/NL : fichier unique index.html, données stockées uniquement dans le navigateur du téléphone (clé `mesheures.v1`, inchangée).

- Langue : détectée automatiquement (nl → néerlandais, sinon français), bouton FR/NL en haut à droite et dans les Réglages. Les textes sont dans l'objet `T` au début du script.
- Types de jour : Dispo gradé, Opération, Congé (demi-jour possible), Z (demi-jour possible), EX
- Fériés légaux belges automatiques + fériés du service ajoutés dans les Réglages
- Férié travaillé : +1 jour de congé, heures prestées en heures sup
- Heures sup par période de 2 mois (payées, converties en jours, reportées)
- Quota de congés par année, avec archive
- Sauvegarde / restauration par fichier

Version 0.10 : nom Heurêka, structure bilingue FR/NL. Traductions néerlandaises à relire par un collègue néerlandophone.
