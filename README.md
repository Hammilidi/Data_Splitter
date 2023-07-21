# Data_Splitter
Vous êtes chargé de développer un script Python qui permettra de diviser un fichier CSV contenant des données en trois parties : JSON, base de données et CSV.
Le script devra être en mesure de transférer 30% des données sous format JSON, 30% dans une base de données et le reste au format CSV.

Vous devez suivre les étapes suivantes pour compléter le challenge :

Chargement des données : Le script doit être capable de charger les données à partir d'un fichier CSV. Assurez-vous que le fichier CSV a une en-tête en première ligne.
Répartition des données : Vous devez mélanger les lignes du fichier CSV pour garantir une répartition aléatoire des données. Ensuite, calculez le nombre de lignes nécessaires pour chaque destination : 30% pour le fichier JSON, 30% pour la base de données et le reste pour le fichier CSV.
Création du fichier JSON : Sauvegardez la partie des données destinée au format JSON dans un fichier JSON. Chaque ligne du fichier JSON doit représenter une entrée des données du fichier CSV.
Création du fichier CSV : Sauvegardez la partie des données destinée au format CSV dans un fichier CSV. Assurez-vous de ne pas inclure l'en-tête dans ce fichier.
Transfert vers la base de données : Sauvegardez la partie des données destinée à la base de données dans une base de données. Utilisez le nom de table fourni comme argument dans le script.
Ajoutez la possibilité de spécifier un taux de répartition personnalisé (par exemple, 40% JSON, 25% base de données, 35% CSV).
Votre script devra être flexible et prendre les arguments nécessaires en entrée, tels que le nom du fichier CSV d'origine, le nom du fichier JSON de sortie, le nom de la base de données et le nom de la table de base de données.

N.B: Vous pouvez Testez le script sur n'importe quelle Dataset que vous désirer 
