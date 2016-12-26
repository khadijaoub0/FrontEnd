Télécharger les ressources css et js et les déposer dans l'arborescence telle qu'elle est dans le site :

changer le lien des css : "/css/" devient "css/"
changer le lien des fichiers javascript : "/js/" devient "js/"

dans le fichier style.css, la ligne 1026 contient le css des contrôles input (champ de saisie) et textarea (champ texte long), qui se trouve dans une balise contenant propriété class nommée send_mail. j'ai ajouté dans la définition du même groupe la définition des select (liste de choix). 
Résultat : 
La ligne 1026, 	.send_mail input, .send_mail textarea {
devient, 		.send_mail input, .send_mail textarea, .send_mail select {
