# Fusion et nettoyage de fichiers CSV/Excel

Script Python qui fusionne plusieurs fichiers CSV/Excel en un seul,
après nettoyage automatique.

## Ce qu'il fait
- Lit tous les .csv et .xlsx d'un dossier
- Harmonise les noms de colonnes
- Supprime lignes vides, espaces parasites et doublons
- Convertit les dates
- Exporte un fichier `resultat.xlsx` + un résumé

## Utilisation
```bash
pip install -r requirements.txt
python fusion.py
```

## Exemple de résultat
<img width="635" height="410" alt="Capture d&#39;écran 2026-10-24 102304" src="https://github.com/user-attachments/assets/4f6fade0-3039-492d-9b9d-d27fe8c054b9" />
3 fichiers lus, 52 lignes -> 19 doublons supprimés -> 33 lignes finales

## Besoin d'un script sur mesure ?
Contactez-moi : Contactez-moi via mon profil GitHub



