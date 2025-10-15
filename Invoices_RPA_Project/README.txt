Invoice RPA Project - Séquentiel
Développé par : R4ayen Mabrouki

Structure :
- Input/ : contient les factures PDF à traiter.
- Output/ : dossier où seront enregistrés les résultats et logs.
- Templates/ : fichier Excel modèle Factures_Traitées.xlsx.
- Docs/ : document Business_Case.pdf.

Étapes d'exécution :
1. Ouvrir UiPath Studio et créer un projet séquentiel.
2. Configurer le chemin du dossier Input et Output.
3. Lire chaque fichier PDF et extraire les champs par regex.
4. Écrire les résultats dans l'Excel.
5. Déplacer les fichiers traités vers Archive/.
