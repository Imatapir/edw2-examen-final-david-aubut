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
    Mon depot se trouve bien sur github. confirmer de visu, tout s'y trouve, le dossier examen-final ainsi que le README.md (a l'exterieur du dossier examen-finale).

6. Je me suis connecté à N0C.
    Donc j'ai entré la commande ssh vqaskmunae@node39-ca.n0c.com -p 5022. 
    J'ai recuperer le port et le node39-ca.n0c.com a partir de n0c.
    Ca m'a demander un mot de passe. J'ai entrer le mauvais mots de passe, puis j'ai fait ctrl+C.
    A partir de la plus rien ne fonctionnait. Une recherche rapide en decrivant la situation a l'AI m'indique au'apparement j'ai bloqué mon adresse IP. Je suis donc en timeout.
7. J’ai récupéré mon dépôt sur N0C.
    Evidemment que non
8. J’ai testé le site dans le navigateur.
    Bye

## Commandes Git utilisées

| Commande     | Rôle                                              |
| ------------ | ------------------------------------------------- |
| `git clone <adresse>`  | Récupérer une copie du projet sur mon ordinateur. |
| `git status` | Vérifier l’état des fichiers dans le dépôt.       |
| `git add .`    | Préparer tous les fichiers pour le prochain commit.    |
| `git commit -am` | Enregistrer une version du projet avec un message.                |
| `git push`   | Envoyer les commits vers GitHub.                  |
| `git remote -v`   | Pour voir les remotes (main et rendu).                  |
| `git remote add rendu main`   | Pour ajouter le remote rendu a main.                  |



## Déploiement sur N0C

Pas pus - l'examen a visiblement pas ete prevu pour prevoir la possibilités de faire des erreurs.

## Réponses théoriques

Question 1 — Client et serveur
    Le client se trouve du cote utilisateur, c'est un logiciel qui fait une demande au serveur (cote en ligne)
    Le logiciel dans mon cas serait le navigateur Brave.

    Le serveur est un ordinateur reel ou virtuel auquel se connecte le navigateur lors d'une requete HTTP et retourne du contenu tel que du php ou du html

Question 2 — Adresse IP, domaine et sous-domaine
    Une addresse IP est une addresse attribuée a une machine sur un serveur. Il permet de l'identifier et est utile, par exemple, pour bloquer un etudiant qui fais un exam de son compte n0c.
    Ex: Mon ordi sur internet
    Un domaine est une representation d,un acces IP sans avoir a l'identifier grace a l'adresse. 
    Ex. Google au lieu de 8.8.8.8
    Un sous-domaine est une sous partie du domaine. 
    par exemple Goggle Drive serait un sous domaine de google

Question 3 — Ports réseau
Un port est une entree de connexion a une machine, le port a rapport a un service.

    | Port | Service associé | Utilité |
| ---: | --------------- | ------- |
|   22 | SSH                | connexion a distance a un serveur        |
|   80 | HTTP                | navigation web        |
|  443 | HTTPS                |  navigation web securisée       |

Question 4 — HTTP et HTTPS
    HTTP n'est pas securisé
    HTTPS comporte une securité qui chiffre ce qui est echangé entre les machines clientes et serveurs

Question 5 — SSH et N0C
    SSH permet (habituellement) de se connecter a distance a un serveur de facon securitaire
    On l'utilise pour deploiement sur N0C pour pouvoir travailler directement a partir de notre machine et exporté notre projet en ligne (habituellement, quand ca marche)

Question 6 — Dépôt GitHub public
    Pourrait pas dire que ca facilite grand chose vu le contexte.

## Difficultés rencontrées

Comme defini au point 6, je n'ai pas pus me connecté a N0C parce qu'une mauvaise manoeuvre de ma part m'a mis en timeout pendant la duree de l'examen, je n'ai donc pas pus completer cette partie.
Je suis toujours en timeout au moment d'ecrire ces lignes.