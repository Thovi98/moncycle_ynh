<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Moncycle pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/moncycle.svg)](https://dash.yunohost.org/appci/app/moncycle) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/moncycle.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/moncycle.maintain.svg)

[![Installer Moncycle avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=moncycle)

*[Read this readme in english.](./README.md)*

> *Ce package vous permet d’installer Moncycle rapidement et simplement sur un serveur YunoHost.
Si vous n’avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Rendre facile le suivi des cycles menstruels et l’application des méthodes naturelles.
Billings . Symptothermie . FertilityCare

### Caractéristiques

👩 un tableau de suivi du cycle menstruel
🌳 dédiée aux méthodes naturelles
🤏 suivi de l'évolution de la glaire cervicale
🌡️ suivi de la température corporelle (optionnel)
🔠 notation FertilityCare (optionnel)
📱 simple sur téléphone comme sur PC
✨ visuel esthétique avec mode sombre
📖 code open source
🤪 pas de pseudo intelligence prédictive
📊 export PDF/CSV pour vos moniteurs/instructrices
🔢 fini Excel ou Google Sheets
💑 un même compte sur plusieurs appareils
✉️ envoi par mail automatique des cycles
🔒 pas de vente de données / pas de publicité
🇫🇷 hébergée et développée en France

### Les méthodes naturelles

Les méthodes naturelles ? «Ce sont des méthodes basées sur la connaissance des signes de fertilité du cycle féminin. Le couple peut ainsi connaitre avec précision les périodes fertiles ou infertiles qu'il traverse, et en fonction de son projet d'enfant, connaitre le meilleur moment pour transmettre la vie, ou les périodes infertiles lorsqu'il souhaite espacer ou limiter les naissances.» Source: methodes-naturelles.fr

Il existe plusieurs méthodes proposées par différentes associations. Voici une liste non exhaustive:

[Méthode Billings](https://www.methode-billings.com/)
👉 méthode compatible avec moncycle.app

[Symptothermie (Cyclamen)](http://www.methodes-naturelles.fr/les_methodes_naturelles/la-methode-dauto-observation)
👉 méthode compatible avec moncycle.app

[Symptothermie (SensiPlan)](https://symptothermie.info/)
👉 méthode compatible avec moncycle.app

[FertilityCare (NaProTechnologie)](https://www.fertilitycare.fr/)
👉 méthode compatible avec moncycle.app

🧠 moncycle.app n'a pas pour objectif de prédire ou de contrôler la bonne application des méthodes (ni de remplacer vos moniteurs) mais seulement de proposer un support numérique. Vous restez le cerveau derrière votre tableau. Si vous ne connaissez pas les méthodes naturelles ou si vous avez des questions sur les règles de celles-ci, rapprochez-vous d'un moniteur de l'une des associations ci-dessus.

**Version incluse :** 7.0~ynh4

**Démo :** https://tableau.moncycle.app/connexion.php?email1=demo@moncycle.app&mdp=demo

## Captures d’écran

![Capture d’écran de Moncycle](./doc/screenshots/moncycle_app.png)

## Avertissements / informations importantes

* No LDAP integration
* After installing, you can create your own user using the form
* Once done, you can (if you want) set the account creation to false in `/var/www/moncycle_app/config.php`
* If you want to use the app in PWA mode, be sure to be connected to your account first

## Documentations et ressources

* Site officiel de l’app : <https://moncycle.app>
* Dépôt de code officiel de l’app : <https://github.com/jean-io/moncycle.app>
* Documentation YunoHost pour cette app : <https://yunohost.org/app_moncycle>
* Signaler un bug : <https://github.com/YunoHost-Apps/moncycle_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/moncycle_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/moncycle_ynh/tree/testing --debug
ou
sudo yunohost app upgrade moncycle -u https://github.com/YunoHost-Apps/moncycle_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>