# proj2-fouine-tests
Un ensemble de tests, testés et approuvés pour fouine


Ce dépôt contient des tests automatisés pour la fouine de Projet 2.

Pour partager vos tests, mettez vos fichiers dans un répertoire à votre nom (ou
celui de votre binôme) et indiquez dans ce fichier les instructions à suivre
pour effectuer les tests.

Si vous voulez tester votre programme, lancez le set de quelqu'un en suivant
ses instructions.


## EdwigeMaxime

Les tests sont dans le dossier `tests/` , dans `auto_tests.sh` il est possible changer l'emplacement de fouine, qui est par défaut dans `bin/` qui est au même niveau que le dossier tests.
Le script effectue un diff sur la sortie de fouine et la sortie de ocaml en ajoutant à la volée la définition de prInt pour ocaml en début de code source.
