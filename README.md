# Assistant accessibilité réseaux sociaux

Page web qui vérifie une publication Instagram ou Facebook avant sa mise en ligne et dit quoi corriger.

**Ouvrir l'outil :** https://tahitiancoverlandia.github.io/assistant-accessibilite/

## Utilisation (aucun compte nécessaire)

1. Glisser le visuel (image, carrousel ou vidéo).
2. Coller la légende.
3. Écrire la description de l'image (texte alternatif).

Le résultat s'affiche à droite : **à corriger** (avec la marche à suivre), **à vérifier soi-même** (à cocher), **c'est bon**.

Dès qu'une image est déposée, la **lecture automatique des textes** se lance (gratuite, dans le navigateur) : elle lit les textes du visuel, mesure leur contraste et leur taille, cherche le -18 et le message de prévention, et vérifie que les montants et les dates sont aussi dans la légende.

## Analyse complète par une IA (optionnel)

Pour obtenir en plus une description proposée et le contrôle des couleurs, ouvrir « Analyse complète par une IA » et coller une clé personnelle :

- **Gemini (Google), gratuit dans la limite d'un quota :** aller sur https://aistudio.google.com/apikey, se connecter avec un compte Google, cliquer sur « Create API key », copier la clé et la coller dans l'outil.
- **ChatGPT (OpenAI)** ou **Claude (Anthropic)** : payant, quelques centimes par analyse.

La clé reste enregistrée dans le navigateur de la personne, nulle part ailleurs. Les images sont alors envoyées au service choisi : avec une clé gratuite, il peut s'en servir pour améliorer ses produits. À éviter pour des visuels confidentiels pas encore sortis.

## Confidentialité

Sans IA, rien n'est envoyé : tout se passe dans le navigateur. Un seul fichier, `index.html`.
