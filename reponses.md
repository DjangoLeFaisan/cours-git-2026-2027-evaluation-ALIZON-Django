## Questions de cours

- Identifiant court du premier commit : 81b824
- Commit correspondant à l'ajout de la page contact : 1da2a0
- Nombre de commits à l'heure actuelle : 5
- Commande pour afficher l'historique en mode graphique : git log --graph
- Commande pour examiner un commit : git show [hash du commit]
- Commande choisie pour annuler les modifications : git reset --hard [hash du commit auquel il faut revenir]
- Commande utilisée pour sélectionner un seul commit d'une branche expérimentale à appliquer : git cherry-pick [hash du commit à garder] (dans mon cas "9553912")
- Explication des différents chiffres dans une numérotation de version sous forme "X.X.X" : le premier chiffre exprime la version actuelle du logiciel (comme pour Windows 7, 10, 11), le deuxième exprime les différentes mises à jour importantes, et le dernier exprime les fixes mineurs.

## Questions finales

- Les modifications de la zone de travail ne sont pas enregistrés. Dans la zone de staging, ils sont enregistrés et prêt à être push. Dans l'historique, ils sont conservés afin de pouvoir être consultés et potentiellement récupérés.
- Il est préférable de réaliser une fonctionnalité sur une branche séparée pour ne pas gêner les collègues et éviter d'introduire des bugs/conflits.
- Aucune idée
- Il est utile de mettre ses modifications de côté dans le cas où on doit travailler en urgence sur une autre branche sans abandonner les modifications actuelles.
- Il est utile de récupérer uniquement un commit plutôt que de fusionner une branche car on peut cibler quoi garder dans les modifications.
- Le HEAD représente le commit le plus récent.
- Le HEAD~2 représente le 2ème commit en dessus du plus récent.
- Un tag git peut servir à donner des informations supplémentaires à un point donné dans l'avancement d'un projet (par exemple donner la version du projet sur un commit).
- Les commit petits et précis facilitent la maintenance d'un projet car il est plus facile de s'y retrouver, et de les manipuler.
- Certains fichiers ne doivent pas être versionnés car ils pourraient contenir des informations non prévues pour être publiques (comme le .env).
