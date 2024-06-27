# -Ransomware-Memoire

## Description

Ce projet est un ransomware écrit en C, développé dans le cadre de mon projet de fin d'année de licence. Il est important de noter que ce projet a été réalisé seul et qu'il présente certaines lacunes et imperfections notamment lors de l'appel de fonction, et surtout un manque cruel d'optimisation.

## Fonctionnalités

- Chiffrement des fichiers avec l'algorithme AES-256 utilisant la bibliothèque Tiny-AES.
- Génération locale de la clé de chiffrement.
- Envoi de la clé de chiffrement à un serveur avec une adresse IP en clair.

## Détails techniques

- **Chiffrement**: Utilisation de l'AES-256 pour chiffrer les fichiers. La bibliothèque [Tiny-AES](https://github.com/kokke/tiny-AES-c) a été utilisée pour implémenter l'algorithme de chiffrement.
- **Génération de la clé**: La clé de chiffrement est générée localement sur la machine infectée.
- **Communication**: La clé de chiffrement est envoyée à un serveur dont l'adresse IP est codée en clair dans le programme.

## Remarques

- Initialement, ce projet exploitait la vulnérabilité EternalBlue, mais cette fonctionnalité a été retirée pour être mis en conformité avec les politiques de GitHub. Pour integrer dans votre code Eternal Blue, je recommande les travaux de BHassani, qui vous donne les outils necessaires pour intégrer cette faille. 
- Ce projet est à but éducatif et ne doit en aucun cas être utilisé à des fins malveillantes.

## Disclaimer

L'utilisation de ce code est strictement à vos propres risques. Je décline toute responsabilité quant à l'utilisation malveillante ou inappropriée de ce code. Ce projet a été développé uniquement dans un but éducatif pour comprendre le fonctionnement des ransomwares et ne doit pas être utilisé pour des activités illégales ou nuisibles.

## Avertissement

Ce projet est un exemple de code malveillant et doit être traité avec précaution. Ne l'exécutez pas sur des systèmes de production ou des systèmes qui contiennent des données sensibles.

