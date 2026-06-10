<div align="center">

# VoxActa

### La parole, transformée en document de référence.

**Capture · Transcription · Document certifié — 100 % sur votre poste.**

[⬇️ Télécharger la dernière version](https://github.com/gitbrain-ai/voxacta/releases/latest) ·
[Notes de version](https://github.com/gitbrain-ai/voxacta/releases)

</div>

---

## Qu'est-ce que VoxActa ?

VoxActa enregistre vos auditions, consultations et réunions, les transcrit **mot à mot avec attribution des locuteurs**, puis produit le document de référence de votre métier — procès-verbal, compte rendu, note de synthèse — prêt à relire, sceller et signer.

| | |
|---|---|
| 🎙️ **Capture** | Audio (micro + système) et vidéo d'écran, en un clic |
| ✍️ **Verbatim attribué** | Transcription locale, locuteurs identifiés et nommés |
| 📄 **Document métier** | PV d'audition, CR de consultation/réunion, selon votre secteur |
| 🔍 **Relecture karaoké** | Le texte suit l'audio ; chaque correction est historisée |
| 🔐 **Scellement & signature** | Empreinte SHA-256, signature électronique intégrée au PDF, journal d'audit |
| 🤖 **Assistant de dossier** | Interrogez l'ensemble d'un dossier en langage naturel, avec sources |

## Local-first, par conception

Vos enregistrements et vos documents **ne quittent jamais votre ordinateur**.
La transcription, l'identification des locuteurs et l'intelligence artificielle
fonctionnent sur votre poste. Aucun cloud requis, aucune donnée transmise.

> Conçu pour les professions où la confidentialité n'est pas une option :
> avocats, notaires, médecins, fonds d'investissement, directions.

## Installation

1. Téléchargez `VoxActa_x.y.z_x64-setup.exe` depuis la
   [dernière release](https://github.com/gitbrain-ai/voxacta/releases/latest)
2. Lancez l'installeur (Windows 10/11, 64 bits)
3. Au premier démarrage, l'assistant configure l'environnement
   (modèles de transcription et d'IA locale) et active votre licence

> **Note SmartScreen** : tant que l'installeur n'est pas signé par certificat,
> Windows peut afficher un avertissement. Cliquez sur « Informations
> complémentaires » → « Exécuter quand même ».

## Mises à jour

VoxActa vérifie ce dépôt à chaque démarrage. Quand une nouvelle version est
disponible, une bannière vous propose de **mettre à jour en un clic** —
téléchargement, vérification de la signature et installation sont automatiques.
Vos dossiers, documents et licence sont toujours préservés.

Chaque release publiée ici contient :

| Fichier | Rôle |
|---|---|
| `VoxActa_x.y.z_x64-setup.exe` | Installeur Windows (installation et mise à jour) |
| `VoxActa_x.y.z_x64-setup.exe.sig` | Signature minisign de l'installeur |
| `latest.json` | Manifeste lu par l'auto-updater |

L'application n'installe **que** des mises à jour dont la signature correspond
à la clé publique embarquée — un binaire altéré est refusé.

## Configuration minimale

| | Minimum | Recommandé |
|---|---|---|
| Système | Windows 10 64 bits | Windows 11 |
| Mémoire | 8 Go | 16 Go |
| Disque | 5 Go libres | 10 Go (modèles IA locale) |
| Processeur | 4 cœurs | 8 cœurs (transcription plus rapide) |

## Licence & support

VoxActa est un logiciel commercial sous licence. Pour toute question, demande de
licence ou support : contactez votre interlocuteur VoxActa.

---

<div align="center">
<sub>© VoxActa — Ce dépôt ne contient que les installeurs publiés. Le code source n'est pas public.</sub>
</div>
