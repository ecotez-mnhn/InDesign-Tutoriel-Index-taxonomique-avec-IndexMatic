# InDesign Tutoriel : Créer un index taxonomique en utilisant IndexMatic
Ce tutoriel décrit la manière de transformer une liste de taxons (espèces, genres, familles) en liste de requêtes IndexMatic (en français) en utilisant les fonctionnalités de rechercher/replacer GREP d'InDesign.

Le dossier contient :
– Un document PDF décrivant la méthode à suivre pour transformer une liste de taxons en série de requêtes IndexMatic ;
– Un document Word contenant la liste initiale transmise pour indexation ;
– Un fichier PDF montrant le résultat final obtenu ;
– Une série de fichiers InDesign cités dans le tutoriel.

Cette procédure permet de générer en une seule fois, avec possibilité de conservation des formatages, une liste de taxons fournis pour un auteur. La liste de taxons doit être la plus complète possible. Les champs sont traités de la manière suivante :

Transformations appliquées :

Espèce binomiale :

lugubris, Acanthopterus OU Acanthopterus lugubris
-> 
/A(canthopterus|\.)( cf\.)?( aff\.)? lugubris/ => lugubris, Acanthopterus

Genre (non suivi des espèces du genre) :

Acanthopterus
->
/Acanthopterus(?! bidens| inermis| lugubris| tristis| velatus)/ => Acanthopterus @

Famille (terme unique) :

Hyrcaninae
->
/Hyrcaninae/ => Hyrcaninae

Une partie du tutoriel est dédiée à la gestion des requêtes de plus de 172 caractères dans IndexMatic.
