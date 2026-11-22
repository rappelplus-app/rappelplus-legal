# Politique de confidentialité de Rappel+

Dernière mise à jour : 22 novembre 2026

## Qui est responsable de vos données

Michael Alvarez, particulier, éditeur de Rappel+. Contact pour toute question sur vos données : rappelplussupport@gmail.com.

## Ce que fait Rappel+

Rappel+ vous prévient lorsqu'un produit que vous avez enregistré fait l'objet d'un rappel publié sur RappelConso, le
site public du gouvernement français.

## Données collectées

Rappel+ fonctionne **sans compte**. Votre inventaire (codes-barres, noms et marques saisis, dates d'ajout et de péremption) et vos
alertes restent **uniquement sur votre téléphone** : ils ne sont jamais envoyés à notre serveur.

Pour savoir si vos produits sont concernés, l'application télécharge la liste publique des rappels (identifiant du
rappel, codes-barres et lots concernés) et la compare elle-même à vos produits, sur le téléphone. Quand un rappel vous
concerne, elle télécharge sa fiche complète. Cette demande ne contient que l'identifiant public du rappel, sans rien qui
vous identifie, mais elle passe par Internet : comme toute requête, elle est vue avec l'adresse IP de votre connexion.

Ce qui transite par nos prestataires :

| Donnée | Pourquoi | Durée de conservation |
|---|---|---|
| Journaux techniques du serveur (adresse IP, date, requête, dont l'identifiant d'un rappel demandé) | Sécurité et diagnostic | Durée fixée par l'hébergeur (Supabase), quelques jours au plus |
| Jeton de notification Firebase et identifiant d'installation Firebase, abonné au canal commun « nouveaux rappels » | Prévenir l'application qu'il y a de nouveaux rappels | Chez Google, selon [ses règles](https://firebase.google.com/support/privacy). Nous ne les recevons pas |

**Nous ne collectons pas** : adresse e-mail, inventaire, photos (la caméra lit le code-barres et la date de péremption sur le téléphone,
aucune image n'est enregistrée ni envoyée ; une photo choisie dans la galerie est seulement lue), localisation, contacts. Rappel+ n'utilise ni identifiant publicitaire, ni outil de
mesure d'audience, ni publicité.

Les fiches de rappel affichées sont des données publiques issues de RappelConso. Elles ne vous concernent pas
personnellement.

## Base légale

Les traitements décrits ci-dessus sont nécessaires pour fournir le service que vous utilisez (article 6.1.b du RGPD),
et, pour les journaux techniques, à la sécurité du service (intérêt légitime, article 6.1.f). Les notifications ne
s'affichent que si vous les autorisez sur votre téléphone.

## Qui reçoit vos données

Aucune donnée n'est vendue ni partagée à des fins commerciales. Quatre prestataires techniques interviennent :

- **Supabase** (hébergement de la liste publique des rappels). Région d'hébergement : Union européenne (Irlande).
- **Google Firebase Cloud Messaging** (signal « nouveaux rappels »). Le même message est envoyé à toutes les
  installations ; il ne contient aucune donnée. Le SDK Firebase installé dans l'application communique avec Google
  (identifiant d'installation, informations techniques sur l'appareil) pour délivrer ces messages. La notification que
  vous voyez est créée par l'application elle-même, sur le téléphone.
- **Google Play** (achat de Rappel+ Pro, facultatif). Le paiement est traité par Google selon ses propres règles ;
  l'application ne reçoit que la confirmation de l'achat, jamais vos coordonnées de paiement.
- **Google ML Kit** (lecture des codes-barres et des dates de péremption, sur le téléphone). Aucune image n'est envoyée, mais ML Kit transmet à
  Google des informations techniques (modèle de l'appareil, version de l'application, performances de la lecture,
  identifiant d'installation) pour mesurer et améliorer son fonctionnement.

Les photos des produits rappelés sont chargées directement depuis les serveurs qui les hébergent (RappelConso ou les
sites indiqués dans la fiche de rappel). Comme pour toute page web, ces serveurs voient l'adresse IP de votre téléphone.
Ces images, publiques, sont gardées en cache sur le téléphone.

Supabase et Google sont des sociétés américaines. Les données sont stockées dans l'Union européenne, mais un accès
depuis les États-Unis reste possible (support, acheminement des messages). Ces transferts sont encadrés par les
clauses contractuelles types de la Commission européenne prévues dans leurs contrats et, pour Google, par le Data
Privacy Framework UE–États-Unis.

## Sécurité

- Toutes les communications sont chiffrées (HTTPS).
- Le serveur ne contient que des données publiques : il n'y a rien sur vous à y protéger.
- Votre inventaire est inclus dans la sauvegarde Android de votre téléphone (si vous l'avez activée), pour le retrouver
  sur un nouvel appareil. Cette sauvegarde est gérée par Google, dans votre compte Google, selon ses règles.

## Vos droits

Vos données personnelles sont sur votre téléphone : vous en gardez la maîtrise.

- **Suppression** : supprimez un produit dans *Mes produits*, ou désinstallez l'application pour tout effacer.
- **Rectification** : le nom, la marque et la date de péremption d'un produit se modifient dans *Mes produits*.
- **Autres demandes** (questions, journaux techniques) : rappelplussupport@gmail.com. Comme nous ne pouvons pas relier
  ces journaux à une personne, nous pourrons vous demander des éléments (adresse IP, dates) pour les retrouver.

Si vous estimez que vos droits ne sont pas respectés, vous pouvez adresser une réclamation à la CNIL (www.cnil.fr).

## Modifications

Toute modification importante de cette politique sera signalée dans l'application.
