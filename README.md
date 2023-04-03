> Création d'un formulaire d'upload de fichier sécurisé

# Créer le formulaire en Html

-   Créer un formulaire avec la méthode POST et enctype="multipart/form-data"

# Créer la partie script Php (dans le même fichier)

-   Créer le code Php permettant d'uploader le fichier directement

# Lister et coder les contrôles nécessaires sur le fichier uploadé

-   Type MIME du fichier (faire des recherches sur le type MIME d'un fichier)
    Vérifier que le type appartient à la liste des types que l'on souhaite accepter
-   Taille maximale d'un fichier : vérifier que la limite n'est pas dépassée
-   Génération de noms uniques : pour ne pas avoir plusieurs noms de fichiers identiques
-   Emplacement de stockage des fichiers
-   Upload du fichier

# Accéder aux fichiers du répertoire d'upload

-   Parcourir le dossier
-   Créer un lien vers un script permettant de télécharger (download) le fichier.
-   Créer le script de téléchargement
    - Récupérer l'emplacement des fichiers
    - Si le fichier existe, définir les entête de téléchargement
    - Créer les liens des fichiers

