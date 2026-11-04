SERVE — prototype installable (PWA)

CE QUE CONTIENT CETTE VERSION
- Démonstration interactive des parcours demandeur et prestataire.
- Publication locale de demandes (données conservées uniquement dans la page ouverte).
- Parcours de démonstration des missions et de la commission.
- Installation possible sur l'écran d'accueil iPhone/Android après hébergement HTTPS.

LIMITES IMPORTANTES
Ce n'est pas encore une application de production :
- aucun compte ni base de données partagée entre téléphones ;
- aucun paiement réel (Apple Pay/carte/Bancontact désactivés) ;
- aucune vérification réelle de pièce d'identité/selfie ;
- aucune géolocalisation ni notification réellement connectée ;
- aucune mise en relation ou libération d'argent réelle.
Ne saisissez pas de vraie pièce d'identité ni de donnée bancaire dans cette démo.

MISE EN LIGNE RAPIDE (sans coder)
1. Ouvrir https://app.netlify.com/drop depuis un ordinateur.
2. Décompresser serve-pwa.zip.
3. Glisser le dossier serve-pwa décompressé dans la zone de dépôt Netlify.
4. Netlify fournit une adresse HTTPS publique.
5. Ouvrir cette adresse dans Safari sur l'iPhone.
6. Toucher Partager, puis "Sur l'écran d'accueil", puis Ajouter.

Pour mettre à jour le prototype, déposer à nouveau le dossier sur Netlify.

PROCHAINE ÉTAPE POUR UN VRAI MVP
Ajouter une API/base de données sécurisée, authentification email/téléphone, modération,
chat, géolocalisation, prestataire KYC, paiements marketplace (Stripe Connect) et règles
de litiges. Les paiements et le KYC doivent être testés et validés avant toute ouverture
au public. Faire valider le montage fiscal belge et l'agrément de plateforme avant lancement.
