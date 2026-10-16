---
title: Politique de confidentialité de Focus Isle
lang: fr
---

# Politique de confidentialité de Focus Isle

*Ceci est une traduction. En cas de divergence avec la [version anglaise](../privacy), la version anglaise prévaut.*

Date d'entrée en vigueur : 2026-10-16

La présente politique explique comment Focus Isle (l'« App »), créée par Stanislau Malchanau (« nous »), traite vos informations. En bref : **nous ne collectons, ne vendons ni ne partageons vos données personnelles. Vos données restent sur votre appareil et dans votre propre compte iCloud.**

## 1. Données stockées par l'App

L'App stocke les éléments suivants sur votre appareil : vos sessions de concentration (début, fin, activité et résultat), vos activités, les tâches du jour et les objectifs, vos réglages, les îles que vous avez atteintes, les trouvailles que vous avez collectées, le grade de votre capitaine et l'apparence de votre bateau.

Nous n'exploitons aucun serveur qui reçoit ces données, et nous n'y avons pas accès. Les exceptions sont le calendrier d'une activité en direct en cours (section 6) et les signaux d'utilisation anonymes (section 9).

## 2. Synchronisation iCloud

Si vous êtes connecté à iCloud, l'App synchronise vos données via CloudKit d'Apple, dans la base de données privée de votre propre compte iCloud. Ces données sont stockées et protégées par Apple conformément à l'Engagement de confidentialité d'Apple (https://www.apple.com/legal/privacy/). Nous ne pouvons ni les voir, ni les lire, ni les exporter. Vous pouvez désactiver la synchronisation dans iOS, sous Réglages > [votre nom] > iCloud.

## 3. Localisation et météo

Pour afficher la météo réelle et la lumière du jour au-dessus de l'île, l'App demande votre position approximative, uniquement lorsqu'elle est ouverte et uniquement si vous l'autorisez. La position est arrondie à environ un kilomètre et envoyée au service WeatherKit d'Apple afin d'obtenir la météo actuelle ainsi que les heures de lever et de coucher du soleil. Nous ne recevons jamais votre position. L'App conserve la dernière réponse météo sur votre appareil. Sans autorisation, l'App se base à la place sur l'horloge de votre téléphone. Vous pouvez modifier ce choix à tout moment dans iOS, sous Réglages > Confidentialité et sécurité > Service de localisation > Focus Isle. Les données météorologiques sont fournies par Apple Weather.

## 4. Mouvements des écouteurs et son spatial

Avec des AirPods ou d'autres écouteurs compatibles, l'App peut utiliser les mouvements de votre tête pour maintenir les sons de l'île à leur place lorsque vous vous tournez. Ces données de mouvement sont traitées sur votre appareil en temps réel, ne sont jamais stockées et ne quittent jamais votre appareil.

## 5. Mode strict et Temps d'écran

Si vous activez le mode strict, l'App utilise la technologie Temps d'écran d'Apple pour bloquer les apps que vous choisissez pendant une session de concentration. Apple ne fournit à l'App que des jetons opaques pour ces apps, qui restent sur votre appareil ; nous ne pouvons pas voir quelles apps vous avez choisies ni comment vous les utilisez.

## 6. Notifications et activité en direct

Les rappels, comme celui qui précède la fin d'un essai gratuit, sont créés sur votre appareil.

Pendant une session de concentration, l'App peut afficher une activité en direct sur l'écran verrouillé et dans la Dynamic Island. Pour qu'elle continue d'avancer pendant que l'App est en veille, l'App envoie à notre petit serveur relais le jeton de notification push de l'activité en direct fourni par Apple ainsi que le calendrier de la session : le début et la fin de chaque voyage et de chaque repos, le numéro de l'île, la couleur de l'activité et le décompte d'aujourd'hui par rapport à votre objectif du jour. Aucun nom, aucune adresse e-mail, aucune activité ni aucun identifiant de compte ou d'appareil n'est envoyé. À chaque moment du calendrier, le serveur demande au service de notifications push d'Apple de mettre à jour l'activité en direct, et il supprime tout dès que l'activité en direct se termine. Le serveur fonctionne sur Cloudflare Workers ; comme tout service Internet, Cloudflare voit l'adresse IP de la requête pendant son acheminement, et nous ne la conservons pas. Si vous désactivez les activités en direct pour l'App dans iOS, sous Réglages, rien n'est envoyé.

## 7. Game Center

Si vous êtes connecté à Game Center, vos succès sont transmis à Game Center d'Apple et traités conformément à l'Engagement de confidentialité d'Apple. Nous ne recevons pas votre identité Game Center.

## 8. Achats

Les abonnements sont vendus et traités par Apple via l'App Store. Nous ne recevons pas vos informations de paiement. Apple indique uniquement à l'App si votre abonnement est actif.

## 9. Analyse d'utilisation et rapports de plantage

Pour savoir quelles fonctionnalités sont utiles et où l'App vous gêne, l'App envoie des signaux d'utilisation anonymes à TelemetryDeck, un service d'analyse de TelemetryDeck GmbH (Augsbourg, Allemagne) dont les serveurs sont situés dans l'UE. Un signal désigne une action dans l'App : par exemple, qu'une session de concentration a commencé, s'est terminée ou a été abandonnée, avec sa durée et son mode ; que l'objectif du jour a été atteint ou modifié ; que le mode strict a été activé ; que l'écran d'abonnement a été affiché ou qu'un abonnement a commencé ; ou que la synchronisation iCloud a échoué. Il est accompagné d'un horodatage arrondi à l'heure et d'informations techniques générales : les versions de l'App et d'iOS, le modèle de l'appareil, la langue, la région et le fuseau horaire, ainsi que les réglages d'affichage et d'accessibilité, comme le mode sombre ou la taille du texte.

Un signal ne contient jamais vos activités, vos tâches ou tout autre texte que vous saisissez, ni votre nom, votre adresse e-mail, votre Compte Apple ou votre position. Votre installation n'est identifiée que par un identifiant aléatoire que l'App sale puis hache avant l'envoi, de sorte que les signaux ne permettent pas de remonter jusqu'à vous et ne peuvent pas être suivis d'une app à l'autre. TelemetryDeck ne stocke aucune adresse IP et n'utilise aucun cookie. Nous n'examinons ces signaux que sous forme de statistiques, pour améliorer l'App ; nous ne les vendons pas, ne les partageons pas avec des annonceurs et ne les utilisons pas pour vous suivre. L'App ne contient aucun code de publicité ou de suivi, et elle ne vous suit pas à travers d'autres apps ou sites web.

Par ailleurs, si vous choisissez de partager des données d'analyse avec les développeurs d'apps dans iOS, sous Réglages > Confidentialité et sécurité > Analyse et améliorations, Apple peut nous fournir des statistiques d'utilisation agrégées et anonymes ainsi que des rapports de plantage. Ces données ne permettent pas de vous identifier.

## 10. Enfants

L'App convient à tous les âges et ne collecte sciemment aucune information personnelle auprès de quiconque, y compris auprès des enfants de moins de 13 ans (ou de l'âge équivalent dans votre pays).

## 11. Conservation et suppression des données

Les données sont conservées aussi longtemps que vous les gardez. Vous pouvez les supprimer à tout moment en supprimant l'App et, pour les données synchronisées, dans iOS, sous Réglages > [votre nom] > iCloud > Gérer le stockage du compte > Focus Isle. Comme nous n'en détenons aucune copie, nous n'avons rien d'autre à supprimer. Le serveur relais ne conserve le calendrier d'une activité en direct que jusqu'à la fin de cette activité en direct. Les signaux d'utilisation sont anonymes et ne peuvent pas être rattachés à vous ; il n'existe donc aucun enregistrement personnel les concernant à consulter ou à supprimer.

## 12. Vos droits

Selon votre lieu de résidence (par exemple en vertu du GDPR dans l'UE, du UK GDPR, du CCPA/CPRA en Californie, de l'APPI au Japon, du PIPA en Corée ou de la LGPD au Brésil), vous pouvez avoir le droit d'accéder à vos données personnelles, de les rectifier, de les effacer ou d'en obtenir la portabilité, ainsi que de vous opposer à leur traitement ou d'en demander la limitation. Comme nous ne détenons pas vos données, vous pouvez exercer ces droits directement sur votre appareil et dans iCloud, comme décrit ci-dessus. Vous pouvez également nous contacter pour toute demande ou question, et vous pouvez introduire une réclamation auprès de votre autorité locale de protection des données.

Nous ne vendons ni ne partageons d'informations personnelles au sens du CCPA/CPRA.

## 13. Modifications

Si la présente politique change, nous mettrons à jour la date d'entrée en vigueur ci-dessus et, en cas de modification substantielle, nous vous en informerons dans l'App.

## 14. Contact

Stanislau Malchanau, Bélarus
E-mail : 7tam.official@gmail.com
