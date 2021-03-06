# Note de cadrage

## Versionnage

| Numéro | Date | responsable | descriptif |
| :--- | :--- | :--- | :--- |
| 1.0.0 | 16/10/18 | B. Ragot | Création du document , Versionning, Contexte et problématiques |
| 1.0.1 | 16/10/18 | S. Le Cann | Objectifs, intervenant |
| 1.0.1 | 18/10/18 | B. Ragot | Contraintes, Dates importantes |

## Contexte et problématiques

### Contexte

La société MégaProduction souhaite mettre en place un point de rencontre entre professionnels et artistes dans le cadre de la recherche de casting. Afin de répondre à ce souhait, ils veulent mettre en place une plateforme complète comprenant un backoffice de gestion des annonces, un site internet multi-support de consultation professionnel et digne de confiance et la mise à disposition d'un flux de casting.

Les équipes de MegaCastings effectue des recherches de casting au près d'un réseau de partenaire. Les professionnels souhaitant publier des annonces de casting seront contactés par les équipes de MegaCastings pour vérifier la véracité des informations fournies. Différentes formules tarifaires seront proposés sous la forme de pack de x Castings.

Les artistes souhaitant voir les annonces le feront via le site internet et contacteront les professionnel en direct. Les annonces seront crées par les équipes de MegaCastings à l'aide d'un client lourd. Un professionnel pourra récupérer des annonces à travers un flux de casting.

### Problématiques

* Mises à disposition des annonces sur un site internet multi-plateforme
  * Mises en places d'un moteur de recherche.
* Mises à disposition d'un flux de casting pour les partenaires
  * Sécurisation de l'accès au flux par authentification.
* Gestion des castings à l'aide d'un client lourd
  * Afficher, ajouter, éditer, supprimer les clients, les partenaires de diffusion et les offres de castings d'une interface simple et intuitive
* Mises en place d'une base de donnée pour stocker
  * Des clients \(organisations à la recherche d'artiste\)
  * Des partenaires de diffusion
  * Des offres de casting
  * Des listes de référentiel\(types de contrats, domaines de métiers, métiers\)
* Importance du lien permanent entre les partenaires et megacasting quant à la diffusion des annonces.
* Traitement interne non-automatisé des annonces.
* Gestion des ressources \(contenu éditorial\).

## Objectifs

* Mettre en place un client lourd accessible uniquement par les employés de l'équipe de MegaCasting et doit être simple et disponible sur tous les postes de la société.
* Les solutions doivent être ergonomique.
* Le site doit être seulement en consultation.
* Mise en place d'une API RestFull pour les partenaires.

## Intervenants

* Client: Dorian Hiron
* Prestataires: Benjamin Ragot, Sven Le Cann
* Expert technique: Dorian Hiron, Tawfiq Cadi Tazi
* Expert gestion de projets: Jeremy Perouault

## Contraintes

* Client lourd
  * Doit être accessible de tout les postes de l'entreprise.
  * Permettre de retrouver facilement une annonce, de l'éditer ou d'en créer de nouvelle, de créer facilement des partenaires de diffusions et des clients.
  * Interface simple, ergonomique et intuitive
  * Gestion des ressources \(contenu éditorial\)
* Client léger \(site internet\)
  * Site dynamique exploitant la base de données centralisée.
  * Multi-support
  * Moteur de recherche dynamique
  * Visualiser les ressources \(contenu éditorial\)
* API rest full
  * gérer l'autorisation des utilisateurs pour contacter l'API.
  * gérer l'accès publique/privée à certaines données.
* Base de donnée
  * Gérer les différents utilisateurs pour cloisonner les accès et gérer précisément les accès de chaques utilisateurs.
  * Installation sur un serveur dédié.
  * Gérer le système d'information de megacasting en respectant les standards.
  * Stocker les ressources \(contenu éditorial\)

## Dates importantes

| Tâche | Date | Détails |
| :--- | :--- | :--- |
| Cahier des charges | 24/10/18 | V1 à faire |
| Analyse détaillé |  |  |
| Plannification |  |  |
| Lotissement/évaluation des risques |  |  |
| Création de l'infrastructure |  |  |
| Création de la base de donnée |  |  |
| Dev. API |  |  |
| Dev. Client léger |  |  |
| Dev. Client Lourds |  |  |
| Rédaction et réalisation des jeux de test |  |  |
| Rédaction des documentations utilisateurs et techniques |  |  |

## Coûts/Budget

