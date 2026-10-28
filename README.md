# Plume PDF

Lecteur et éditeur PDF pour Windows 10 et 11, léger, rapide et entièrement en français.

| Édition | Usage | Télécharger |
|---|---|---|
| **Plume PDF** | tout : lire, annoter, organiser les pages, remplir et créer des formulaires, modifier le contenu, convertir, protéger | [PlumePDF.exe](https://github.com/Gadjoffrey/PlumePDF/releases/latest/download/PlumePDF.exe) |
| **Plume PDF Lite** | pour les apprenants : lire, remplir les formulaires, annoter, dessiner, imprimer, sans toucher au contenu des documents | [PlumePDF-Lite.exe](https://github.com/Gadjoffrey/PlumePDF/releases/latest/download/PlumePDF-Lite.exe) |

Dernière version : **0.6.1** ([nouveautés et anciennes versions](https://github.com/Gadjoffrey/PlumePDF/releases)).

## Installation

Un double-clic sur l'exe installe l'application pour la session Windows, sans droits d'administrateur, avec son
raccourci dans le menu Démarrer. Les deux éditions peuvent être installées côte à côte.

Windows peut afficher « Windows a protégé votre ordinateur » pour un exe téléchargé depuis Internet : cliquer sur
« Informations complémentaires », puis « Exécuter quand même ». L'affichage s'appuie sur Microsoft Edge WebView2,
présent sur Windows 10 et 11 à jour.

## Mises à jour

L'application vérifie seule les nouvelles versions au démarrage. **Plume PDF** télécharge la nouvelle version en
arrière-plan puis propose de l'appliquer d'un clic, sans se fermer : les documents ouverts sont rouverts (réglage dans
Préférences, Général, « Mises à jour »). **Plume PDF Lite** l'applique sans rien demander au lancement suivant.

La mise à jour automatique ne télécharge que l'interface de l'application (pages, scripts et polices), signée par
l'auteur : un fichier modifié est refusé. Elle n'écrit ni ne lance jamais aucun programme, ce que les antivirus
d'entreprise bloquent. Quand une version demande un nouveau programme, l'application le signale avec le lien de
téléchargement : elle s'installe alors à la main, comme la première fois.

## Licence

Plume PDF s'appuie sur [MuPDF](https://mupdf.com) (© Artifex Software) et est distribué sous licence AGPL-3.0
(fichier [LICENSE](LICENSE)). Le code source complet de chaque version est joint à sa page de publication et fourni
avec l'application (À propos, « Code source »).

CREATED WITH ❤️ BY ALBERT J. ET UN PEU D'IA
