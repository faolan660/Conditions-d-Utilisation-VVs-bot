# Conditions d'utilisation — VVs Bot

**Dernière mise à jour : [DATE À COMPLÉTER]**

> Ce document n'est pas un avis juridique professionnel. Il décrit de bonne foi le
> fonctionnement du bot et les règles d'usage. Si le bot est utilisé à grande échelle
> ou sert un public dans l'Union européenne, il est recommandé de le faire relire par
> un professionnel du droit.

## 1. Objet

Les présentes Conditions d'Utilisation (« CU ») régissent l'usage du bot Discord
**VVs Bot** (le « Bot »), développé et maintenu par **[TON NOM / PSEUDO]** (l'« Éditeur »),
ainsi que de son interface web associée (le « Dashboard ») et du site public listant les
membres bannis du groupe VRChat (le « Site des bannis »).

En ajoutant le Bot à un serveur Discord, en utilisant l'une de ses commandes, ou en
accédant au Dashboard, vous acceptez sans réserve les présentes CU. Si vous n'êtes pas
d'accord, n'utilisez pas le Bot.

## 2. Description du service

Le Bot propose, selon les serveurs sur lesquels il est installé :

- **Modération Discord** : kick, ban, timeout, avertissements, purge de messages,
  anti-spam et anti-raid automatiques.
- **Gestion de serveur** : création/suppression de salons, catégories et rôles.
- **Surveillance VRChat** : suivi des instances ouvertes d'un groupe VRChat, relais des
  annonces du groupe, détection et journalisation des kicks/avertissements/bannissements
  appliqués au sein de ce groupe.
- **Compte(s) VRChat lié(s)** : pour assurer cette surveillance, un ou plusieurs comptes
  VRChat doivent être connectés au Bot par un membre autorisé du serveur (voir section 4).
- **Système d'XP et de communauté** : gain de points par message/vocal, niveaux,
  récompenses de rôle, classement, commandes personnalisées, annonces planifiées,
  giveaways.
- **Fonctionnalité IA (`/ia`)** : réservée aux serveurs disposant d'un abonnement
  « premium », avec quota mensuel de requêtes et cooldown par utilisateur.
- **Dashboard web** : interface de contrôle et de statistiques accessible aux
  administrateurs du Bot.
- **Site des bannis** : page publique listant les membres actuellement bannis du groupe
  VRChat principal suivi par le Bot.

L'Éditeur se réserve le droit d'ajouter, modifier ou retirer tout ou partie de ces
fonctionnalités à tout moment, sans préavis.

## 3. Conditions d'accès

- L'usage du Bot est soumis aux [Conditions d'utilisation de Discord](https://discord.com/terms)
  et, pour les fonctionnalités VRChat, aux
  [Conditions d'utilisation de VRChat](https://hello.vrchat.com/legal).
- L'utilisateur doit avoir l'âge minimum requis par Discord (13 ans, ou l'âge minimum
  légal applicable dans son pays) pour utiliser le Bot.
- Certaines commandes sont réservées aux membres disposant d'un rôle de modérateur ou de
  la permission « Gérer le serveur » sur le serveur concerné. L'attribution de ces rôles
  relève de la seule responsabilité des administrateurs de chaque serveur, pas de
  l'Éditeur.
- L'accès au Dashboard est protégé par un identifiant/mot de passe défini par
  l'administrateur du Bot et ne doit pas être partagé avec des personnes non autorisées.

## 4. Comptes VRChat liés au Bot

En connectant un compte VRChat au Bot via la commande `/login`, l'utilisateur reconnaît
et accepte que :

- ses identifiants VRChat (nom d'utilisateur et mot de passe) sont transmis au Bot afin
  qu'il puisse s'authentifier auprès de l'API VRChat, y compris pour la validation d'un
  code de double authentification (2FA) si le compte en dispose ;
- le mot de passe et le cookie de session résultant sont **conservés par le Bot** tant
  que le compte reste enregistré, afin de permettre la reconnexion automatique en cas
  d'expiration de session (voir la Politique de confidentialité pour le détail) ;
- ce compte sera utilisé par le Bot pour effectuer, en son nom, des actions de
  modération au sein du groupe VRChat concerné (kick/ban/déban) lorsque celles-ci sont
  demandées par un modérateur autorisé sur Discord ;
- il ne doit connecter que des comptes VRChat dont il a le droit d'usage, et jamais un
  compte appartenant à un tiers sans son consentement explicite.

Il est fortement recommandé d'utiliser un compte VRChat dédié à la modération plutôt
qu'un compte personnel.

## 5. Utilisation acceptable

En utilisant le Bot, vous vous engagez à ne pas :

- tenter de contourner, perturber ou surcharger le Bot, le Dashboard ou l'API VRChat
  (spam de commandes, scripts automatisés, exploitation de failles) ;
- utiliser la fonctionnalité `/ia` pour produire du contenu illégal, haineux, violent,
  sexuel, harcelant, ou visant à contourner les protections mises en place par le
  fournisseur du modèle d'IA ;
- utiliser le Bot pour usurper l'identité d'un tiers, diffuser de fausses informations
  de modération, ou nuire délibérément à un membre de la communauté ;
- exploiter les identifiants du Dashboard, les jetons (tokens) ou toute donnée technique
  du Bot à des fins autres que celles prévues par ces CU ;
- utiliser le Bot d'une manière qui violerait les Conditions d'utilisation de Discord ou
  de VRChat.

Tout manquement peut entraîner, à la discrétion de l'Éditeur ou des modérateurs du
serveur concerné, une restriction ou suppression de l'accès aux fonctionnalités du Bot,
en plus des sanctions Discord/VRChat éventuellement applicables.

## 6. Fonctionnalité IA et abonnement « premium »

- L'accès à la commande `/ia` est conditionné à l'activation d'un statut « premium » ou
  « offert » pour le serveur concerné, décidé par l'Éditeur.
- Un quota mensuel de requêtes par serveur et un budget global peuvent limiter ou
  suspendre temporairement l'accès à cette fonctionnalité, sans que cela constitue un
  dysfonctionnement du Bot.
- Les réponses générées par l'IA sont produites par un modèle tiers et n'engagent ni
  l'exactitude, ni la responsabilité de l'Éditeur. Elles ne doivent pas être considérées
  comme un avis professionnel (juridique, médical, financier ou autre).
- L'abonnement premium, lorsqu'il est payant, est accordé selon les modalités
  communiquées séparément (durée, prix, modalités de paiement) par l'Éditeur ; ces CU ne
  couvrent pas les conditions commerciales spécifiques d'achat.

## 7. Site des bannis (publication publique)

Les membres bannis du groupe VRChat principal suivi par le Bot sont publiés sur une page
web publique (hébergée via GitHub Pages), incluant : pseudonyme VRChat, identifiant
VRChat, date du bannissement, raison indiquée par le modérateur, et pseudonyme du
modérateur ayant appliqué la sanction. Voir la Politique de confidentialité pour le
détail et les modalités de contestation.

## 8. Disponibilité du service

Le Bot est fourni « en l'état », sans garantie de disponibilité continue, d'absence
d'erreur ou de compatibilité avec toute version future de Discord ou de VRChat.
L'Éditeur peut interrompre, suspendre ou modifier le Bot à tout moment, notamment pour
maintenance, évolution technique, ou décision de VRChat/Discord affectant son
fonctionnement (changement d'API, suspension de compte, etc.).

## 9. Limitation de responsabilité

Dans la limite permise par la loi applicable, l'Éditeur ne pourra être tenu responsable :

- des sanctions VRChat ou Discord appliquées à un compte connecté au Bot ou à un serveur
  l'utilisant ;
- des pertes de données, interruptions de service, ou erreurs de fonctionnement du Bot ;
- des décisions de modération prises par les modérateurs d'un serveur via le Bot, ces
  décisions relevant de leur seule responsabilité ;
- du contenu généré par la fonctionnalité IA.

Ce Bot est un projet personnel/associatif fourni gratuitement pour les fonctionnalités
de base ; il n'est pas exploité dans le cadre d'une activité commerciale garantissant un
niveau de service.

## 10. Suppression de données et retrait

Tout utilisateur peut demander la suppression de ses données (compte VRChat lié,
historique de modération le concernant, statistiques d'XP) selon les modalités décrites
dans la Politique de confidentialité. Un modérateur peut à tout moment déconnecter un
compte VRChat du Bot via `/logout`.

## 11. Modifications des présentes CU

L'Éditeur peut modifier ces CU à tout moment. La version en vigueur est celle publiée
sur ce dépôt GitHub. En cas de modification substantielle, un effort raisonnable sera
fait pour en informer les administrateurs des serveurs utilisant le Bot.

## 12. Droit applicable

Les présentes CU sont soumises au droit français, sans préjudice des dispositions
impératives de protection des consommateurs ou des données personnelles qui pourraient
s'appliquer dans le pays de résidence de l'utilisateur.

## 13. Contact

Pour toute question relative à ces CU : **[TON EMAIL / CONTACT DISCORD]**

---

Voir également la [Politique de confidentialité](./POLITIQUE_CONFIDENTIALITE.md).
