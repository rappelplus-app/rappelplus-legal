# Politique de confidentialité de Rappel+

Dernière mise à jour : 19 novembre 2026

## Qui est responsable de vos données

Michael Alvarez, particulier, éditeur de Rappel+. Contact pour toute question sur vos données : rappelplussupport@gmail.com.

## Ce que fait Rappel+

Rappel+ vous prévient lorsqu'un produit que vous avez enregistré fait l'objet d'un rappel publié sur RappelConso, le
site public du gouvernement français.

## Données collectées

**Sans compte**, votre inventaire ne quitte pas votre téléphone : la liste de vos produits reste uniquement sur
l'appareil. La comparaison avec les rappels se fait sur le serveur, seulement si vous êtes connecté.

**Avec un compte**, nous conservons :

| Donnée | Pourquoi | Durée de conservation |
|---|---|---|
| Adresse e-mail et mot de passe (chiffré, jamais lisible) | Créer et sécuriser votre compte | Jusqu'à la suppression du compte |
| Codes-barres des produits enregistrés, avec le nom et la marque si vous les saisissez, et la date d'ajout | Comparer vos produits aux rappels | Jusqu'à ce que vous supprimiez le produit ou le compte |
| Alertes (produit concerné, rappel, date, lu ou non) | Vous montrer les rappels qui vous concernent | Jusqu'à la suppression du produit ou du compte |
| Identifiant de notification du téléphone (jeton Firebase Cloud Messaging, lié à un identifiant d'installation Firebase) | Vous envoyer les notifications d'alerte | Chez nous : jusqu'à la déconnexion, la suppression du compte, ou son invalidation par Google. Chez Google : selon [ses règles](https://firebase.google.com/support/privacy) |
| Journaux techniques du serveur (adresse IP, date, requête) | Sécurité et diagnostic | Durée fixée par l'hébergeur (Supabase), quelques jours au plus |

**Nous ne collectons pas** : photos (la caméra lit le code-barres sur le téléphone, aucune image n'est enregistrée ni
envoyée), localisation, contacts. Rappel+ n'utilise ni identifiant publicitaire, ni outil de mesure d'audience, ni publicité.

Les fiches de rappel affichées sont des données publiques issues de RappelConso. Elles ne vous concernent pas
personnellement.

## Base légale

Le traitement est nécessaire pour fournir le service que vous demandez en créant un compte (article 6.1.b du RGPD).
Les notifications ne sont envoyées que si vous les autorisez sur votre téléphone.

## Qui reçoit vos données

Aucune donnée n'est vendue ni partagée à des fins commerciales. Trois prestataires techniques les traitent pour notre compte :

- **Supabase** (hébergement de la base de données et des comptes). Région d'hébergement : Union européenne (Irlande).
- **Google Firebase Cloud Messaging** (acheminement des notifications). Le SDK Firebase installé dans l'application
  communique avec Google (identifiant d'installation, informations techniques sur l'appareil) pour délivrer les
  notifications. Une notification ne contient que des informations publiques sur le rappel (titre, marque), jamais
  votre inventaire.
- **Google ML Kit** (lecture des codes-barres, sur le téléphone). Aucune image n'est envoyée, mais ML Kit transmet à
  Google des informations techniques (modèle de l'appareil, version de l'application, performances de la lecture,
  identifiant d'installation) pour mesurer et améliorer son fonctionnement.

Les photos des produits rappelés sont chargées directement depuis les serveurs qui les hébergent (RappelConso ou les
sites indiqués dans la fiche de rappel). Comme pour toute page web, ces serveurs voient l'adresse IP de votre téléphone.
Ces images, publiques, sont gardées en cache sur le téléphone.

Supabase et Google sont des sociétés américaines. Les données sont stockées dans l'Union européenne, mais un accès
depuis les États-Unis reste possible (support, acheminement des notifications). Ces transferts sont encadrés par les
clauses contractuelles types de la Commission européenne prévues dans leurs contrats et, pour Google, par le Data
Privacy Framework UE–États-Unis.

## Sécurité

- Toutes les communications sont chiffrées (HTTPS).
- Chaque utilisateur n'a accès qu'à ses propres données (contrôle d'accès au niveau de la base).
- Sur le téléphone, la session est chiffrée avec une clé du Keystore Android. Elle est exclue des sauvegardes
  Android, tout comme la base locale.

## Vos droits

Vous pouvez accéder à vos données, les rectifier, les supprimer, en demander la portabilité, vous opposer à leur
traitement ou en demander la limitation.

- **Suppression** : dans l'application, *Paramètres → Supprimer mon compte*. Votre compte, vos produits, vos alertes
  et vos appareils sont supprimés du serveur, puis votre inventaire et votre session sont effacés du téléphone.
  Les sauvegardes techniques de l'hébergeur peuvent encore contenir ces données quelques jours (selon son offre) avant leur effacement
  automatique. Si vous avez désinstallé l'application, écrivez à rappelplussupport@gmail.com depuis l'adresse de votre
  compte : nous le supprimons sous 30 jours.
- **Rectification** : le nom et la marque d'un produit se modifient dans *Mes produits*.
- **Autres demandes** (accès, portabilité, questions) : rappelplussupport@gmail.com.

Si vous estimez que vos droits ne sont pas respectés, vous pouvez adresser une réclamation à la CNIL (www.cnil.fr).

## Modifications

Toute modification importante de cette politique sera signalée dans l'application.
