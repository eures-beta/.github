<!-- Rédiger la description en français et remplir les sections pertinentes, y compris pour une PR créée par un agent. Remplacer les textes d'aide par des informations propres à cette PR. -->

## :busts_in_silhouette: Qui ?

> _À qui s'adresse le changement ? Nommez les rôles concernés (candidat, employeur, conseiller, équipe technique…) et qui réalise les actions._

## :sparkles: Quoi ?

> _Quel comportement est ajouté ou modifié ? Précisez les termes ambigus : transmission de quoi, par qui et à qui ?_

## :thinking: Pourquoi ?

> _Expliquez le problème ou besoin et le bénéfice attendu, sans répéter les fonctionnalités. Pas d'historique de branches, de rebase ou d'incident de recette : les détails techniques vont dans les sections dédiées ci-dessous._

## :cake: Comment ? <!-- optionnel -->

> _Expliquez le parcours et le fonctionnement dans un langage accessible : qui fait quoi, dans quel ordre, avec quelles limites. Réservez les détails de schéma et de migration aux sections modèles._

## :computer: Aperçu des changements visuels

> _Pour un changement visuel (page, composant, e-mail…), montrez en priorité un avant/après avec les mêmes données et un cadrage comparable. Choisissez quelques exemples représentatifs : six images maximum au total, avant et après compris. Ajoutez une vue mobile et/ou ordinateur seulement si elle apporte une information utile._

> _Présentez « Avant » puis « Après » verticalement, une image par ligne occupant toute la largeur disponible. Pas de tableau ni de colonnes côte à côte, pas de largeur HTML réduite. Recadrez les marges vides et l’interface extérieure inutiles en préservant le contexte nécessaire, les libellés et l’état comparé. Utilisez un cadrage identique avant/après. Générez une résolution suffisante pour lire le texte directement dans la description (viser au moins 1 400 pixels de large pour un écran ordinateur ; conserver la largeur native d’un vrai écran mobile). Ne grossissez pas artificiellement une petite image : régénérez-la à la source. Vérifiez la lisibilité dans la description GitHub sans devoir ouvrir un nouvel onglet._

> _Insérez les images directement dans cette description avec des liens GitHub accessibles aux relecteurs, pour qu'elles s'affichent sans ouvrir un fichier local. Légendez chaque exemple et identifiez clairement « Avant » et « Après »._

> _Pour les captures destinées uniquement à la relecture, utilisez les pièces jointes de l’éditeur GitHub : coller, glisser-déposer ou sélectionner le fichier, puis réutiliser le lien `https://github.com/user-attachments/...` généré dans la description. Vérifiez que l’envoi est terminé et que les images s’affichent avec les droits des relecteurs._

> _Ne commitez pas ces captures dans le dépôt et ne créez pas de branche, de commit ou de PR uniquement pour héberger les images. Cette règle ne concerne pas les véritables ressources du produit ou d’une documentation durable lorsqu’elles font partie du changement demandé. Si l’outil ne permet pas de joindre une image, utilisez l’interface GitHub ou signalez la limite ; ne contournez pas cette limite en ajoutant les captures au code._

> _Utilisez des données fictives et masquez les informations personnelles, secrets et liens de connexion réels. Précisez s'il s'agit d'un aperçu local ou d'un rendu dans l'application ou le client e-mail réel._

> _Si aucune capture n'apporte d'information utile, indiquez « Sans objet »._

## :seedling: Quels modèles Django sont créés ?

> _Listez les nouveaux modèles, leur rôle, les champs, relations et contraintes importants et les migrations nécessaires. Indiquez « Aucun » ou « Sans objet » pour un dépôt sans Django._

## :hammer_and_wrench: Quels modèles Django sont modifiés ?

> _Listez les modèles existants modifiés, renommés ou supprimés, leurs champs, relations et contraintes concernés. Précisez les migrations, la compatibilité avec les anciennes bases et la conservation des données. Indiquez « Aucun » ou « Sans objet » si approprié._

## :floppy_disk: Quelles nouvelles données sont sauvegardées en base de données ?

> _Décrivez les informations nouvellement enregistrées, dans quelles tables ou quels modèles, à quel moment et pour quelle durée. Incluez les brouillons et sessions, même sans nouveau modèle métier. Signalez les données personnelles, les modifications ou suppressions de données existantes et, si aucune nouvelle donnée n’est enregistrée, indiquez-le explicitement._

## :new: Quelles applications Django sont créées ?

> _Listez les nouvelles applications et leur rôle. Distinguez une application Django d'un simple paquet Python. Indiquez « Aucune » ou « Sans objet » si approprié._

## :jigsaw: Quelles applications Django sont modifiées ?

> _Listez les applications existantes modifiées et les changements de chacune. Signalez aussi les applications renommées ou supprimées. Indiquez « Aucune » ou « Sans objet » si approprié._

## :rotating_light: À vérifier

- [ ] Signaler les éventuels changements incompatibles, migrations ou changements de configuration.
- [ ] Ajouter les étiquettes pertinentes à la PR.

## :desert_island: Comment tester ?

> _Les instructions pour reproduire le problème, les profils de test, le parcours spécifique à utiliser, etc. Si vous disposez d'une recette jetable, mettre l'URL pour tester dans cette partie._

