# Politique de Confidentialité de FroggAI

**Date d'entrée en vigueur :** 7 novembre 2025

Merci d'utiliser FroggAI ("l'extension"), un assistant IA sécurisé et local pour votre navigateur. Votre vie privée est notre priorité. Cette politique de confidentialité explique quelles données nous collectons, comment nous les utilisons, et pourquoi la conception de FroggAI est fondamentalement axée sur le respect de votre vie privée.

Le principe fondamental de FroggAI est que **le traitement de l'IA s'effectue localement sur votre appareil** via le modèle Gemini Nano intégré à Chrome. Le contenu des pages web que vous analysez et vos conversations avec l'IA ne quittent jamais votre ordinateur pour le traitement par l'IA.

### 1. Quelles données sont collectées et traitées ?

Nous distinguons clairement les données traitées localement et celles nécessaires pour les fonctionnalités optionnelles en ligne.

#### a) Données Traitées et Stockées Localement (sur votre ordinateur) :

Ces données ne sont jamais envoyées à nos serveurs.

*   **Contenu du site web :** Le texte que vous sélectionnez ou le contenu textuel d'une page web que vous soumettez pour analyse (résumé, extraction de points clés, etc.) est traité directement par le modèle d'IA local de votre navigateur.
*   **Historique des conversations :** Toutes vos interactions et conversations avec l'IA sont sauvegardées localement sur votre appareil en utilisant l'API `chrome.storage.local` pour que vous puissiez y accéder ultérieurement.
*   **Notes et Modèles de Prompts :** Les notes que vous sauvegardez et les modèles de prompts personnalisés que vous créez sont également stockés localement sur votre appareil.

#### b) Données Collectées pour les Fonctionnalités Premium (optionnelles) :

Pour utiliser nos fonctionnalités premium, nous proposons une connexion optionnelle via Google. Si vous choisissez de vous connecter, nous collectons les informations suivantes :

*   **Informations d'authentification :** Nous utilisons l'API `chrome.identity` pour obtenir un jeton d'authentification de Google de manière sécurisée. Nous utilisons ce jeton pour créer et gérer votre compte FroggAI via Firebase Authentication. Nous ne collectons ni ne stockons jamais votre mot de passe Google.
*   **Informations d'identification personnelle :** Lors de la connexion, nous collectons votre **adresse e-mail** et un **identifiant utilisateur unique (UID)** fourni par Firebase. Votre adresse e-mail est utilisée comme identifiant principal pour votre compte.
*   **Informations financières et de paiement :** Si vous souscrivez à un abonnement premium, le paiement est traité par notre partenaire tiers, **Stripe**. **Nous ne voyons, ne collectons et ne stockons jamais vos informations de carte de crédit.** Nous enregistrons uniquement le statut de votre abonnement (par exemple, "premium") dans notre base de données Firebase, lié à votre identifiant utilisateur, afin de vous donner accès aux fonctionnalités premium.

### 2. Comment nous utilisons vos données ?

*   **Pour fournir les fonctionnalités de base :** Les données locales sont utilisées pour faire fonctionner l'extension, conserver votre historique et personnaliser votre expérience.
*   **Pour gérer les comptes et les abonnements Premium :** Votre adresse e-mail et votre identifiant utilisateur sont utilisés pour gérer votre compte, vérifier le statut de votre abonnement et vous donner accès aux fonctionnalités payantes.
*   **Pour communiquer avec vous :** Nous pouvons utiliser votre adresse e-mail pour vous envoyer des informations importantes concernant votre compte, votre abonnement ou des mises à jour critiques de l'extension.

### 3. Partage de données avec des tiers

Nous ne vendons ni ne louons vos données personnelles. Nous partageons des informations uniquement avec les tiers de confiance suivants, qui sont essentiels au fonctionnement de nos services premium :

*   **Google / Firebase :** Utilisé pour l'authentification des utilisateurs et la gestion de la base de données (pour le statut des abonnements).
*   **Stripe :** Utilisé pour le traitement sécurisé des paiements pour les abonnements premium.
*   **Vercel :** Utilisé pour héberger notre backend sécurisé qui communique entre l'extension et Stripe pour créer les sessions de paiement.

### 4. Sécurité des données

Nous prenons la sécurité de vos données très au sérieux. La mesure de sécurité la plus importante est notre architecture locale : vos conversations et les données des pages web ne sont pas envoyées sur des serveurs externes pour analyse. Pour les données de compte stockées dans Firebase, nous nous appuyons sur l'infrastructure de sécurité robuste de Google.

### 5. Contrôle de vos données

*   **Données locales :** Vous pouvez supprimer votre historique de conversation, vos notes et vos modèles à tout moment depuis l'interface de l'extension. La désinstallation de l'extension supprimera toutes les données stockées localement.
*   **Données de compte :** Vous pouvez vous déconnecter de votre compte à tout moment. Pour demander la suppression définitive de votre compte et des données associées (adresse e--mail, statut d'abonnement), veuillez nous contacter à l'adresse ci-dessous.

### 6. Modifications de cette politique

Nous pouvons mettre à jour cette politique de confidentialité de temps à autre. Nous vous encourageons à la consulter régulièrement.

### 7. Nous contacter

Si vous avez des questions concernant cette politique de confidentialité, veuillez nous contacter à : **orion.extensions@gmail.com**
