## Mon Docker Compose
Voilà ma config pour `docker-compose` pour ceux (ou celle), qui la souhaite.
C'est une config simple, seulement composé de NGINX, PHP5 (FPM) et MariaDB.

## Comen sa march ?
1. Il faut maîtriser Docker, je dirais même, `docker-machine` (Si vous maîtrisez pas, je vous invite à demander à [Google](https://google.fr/?q=Comen fair marcher Docker))
2. Installez [Docker Toolbox](https://www.docker.com/products/docker-toolbox)
3. Faites `docker-compose -v` pour voir si ca fonctionne
4. Clonez (ou téléchargez) ce dépôt
..* Changez toutes les châines de caractères entre `{...}` dans le fichier `docker-compose.yml`
5. Rendez-vous dans le dépôt cloné (ou téléchargé), puis faites `docker-compose up`, ca va tous installer
6. Allez à l'addresse `http://localhost`, et paf. Magie
