# Examen final EDW2

## Identification

- Prénom : David
- Nom : Aubut
- Groupe : H26-EDW2

## Liens publics

- [Dépôt GitHub](URL_DU_DEPOT)
- [Site déployé sur N0C](URL_DU_SITE)

## Étapes réalisées

1. J’ai cloné le projet fourni avec Git grace a la commande "git clone <lien>".
    le projet a ete cloné dans home/tapir/examFinal sur la partie WSL/Linux de mon ordinateur.

2. J’ai modifié la page d’accueil pour ajouter mon nom a l'interieur de la  variable $nomEtudiant

3. J’ai créé un dépôt public sous le nom edw2-examen-final-david-aubut sur mon compte GitHub.
    https://github.com/Imatapir/edw2-examen-final-david-aubut.git

4. J’ai ajouté un nouveau remote nommé `rendu` a l'aide de la commande :
    git remote add rendu https://github.com/Imatapir/edw2-examen-final-david-aubut.git.
    J'ai verifier a l'aide de git remote -v et il affiche maintenant ceci:
    origin  https://github.com/Imatapir/edw2-examen-final-david-aubut.git (fetch)
    origin  https://github.com/Imatapir/edw2-examen-final-david-aubut.git (push)
    rendu   https://github.com/Imatapir/edw2-examen-final-david-aubut.git (fetch)
    rendu   https://github.com/Imatapir/edw2-examen-final-david-aubut.git (push)

5. J’ai envoyé mon projet vers mon dépôt GitHub.
6. Je me suis connecté à N0C.
7. J’ai récupéré mon dépôt sur N0C.
8. J’ai testé le site dans le navigateur.

## Commandes Git utilisées

| Commande     | Rôle                                              |
| ------------ | ------------------------------------------------- |
| `git clone`  | Récupérer une copie du projet sur mon ordinateur. |
| `git status` | Vérifier l’état des fichiers dans le dépôt.       |
| `git add`    | Préparer les fichiers pour le prochain commit.    |
| `git commit` | Enregistrer une version du projet.                |
| `git push`   | Envoyer les commits vers GitHub.                  |s

## Déploiement sur N0C

Je me suis connecté à N0C avec SSH. Ensuite, je me suis placé dans le dossier prévu pour mon site web. J’ai récupéré mon dépôt public GitHub avec `git clone`. Après le déploiement, j’ai ouvert le lien N0C dans le navigateur et j’ai vérifié que la page d’accueil affichait mon nom.

## Réponses théoriques

Question 1 — Client et serveur
Question 2 — Adresse IP, domaine et sous-domaine

## Difficultés rencontrées