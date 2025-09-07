Permissions Linux
Ce que j’ai appris
Chaque fichier et dossier sur Linux a des permissions spécifiques qui déterminent qui peut faire quoi :

l'utilisateur (u)
le groupe (g)
les autres (o)
Exemple avec ls -l
cogner

-rw-r--r-- 1 user user 1234 sep 7 notes.txt
Voici ce que cela signifie :

rw- : L’utilisateur peut lire et écrire.
r-- : Le groupe peut uniquement lire.
r-- : Les autres utilisateurs peuvent également lire.
Modifier les permissions
chmod 755 script.sh → Rend le script exécutable par tous, tout en permettant au propriétaire de le modifier.
chown alice:dev fichier.txt → Change le propriétaire du fichier en Alice et le groupe en dev.
Mon ressenti
J'ai compris que la gestion des permissions est cruciale pour la sécurité sous Linux. Il est essentiel de rester vigilant et de ne pas donner trop de droits, afin de protéger les données et les ressources.