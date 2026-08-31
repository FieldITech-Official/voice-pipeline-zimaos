# 🎙️ Pipeline Vocal Local (Whisper & Piper) pour ZimaOS / Home Assistant

Ce dépôt fournit les fichiers de configuration **Docker Compose** nécessaires pour déployer un pipeline vocal 100% local sur votre **ZimaBoard** (ou tout autre serveur sous Docker/Portainer). Ce système permet d'alimenter votre assistant vocal intelligent via le **Protocole Wyoming** dans Home Assistant.

## 🛠️ Composants du Pipeline

* **Whisper (STT)** : Le moteur de reconnaissance vocale pour transformer vos paroles en texte.
* **Piper (TTS)** : Le moteur de synthèse vocale ultra-rapide pour faire parler votre assistant.

---

## 🚀 Instructions d'installation

1. Connectez-vous à votre interface **Portainer (ZimaOS)**.
2. Copiez les codes des fichiers `docker-compose.piper.yml` et `docker-compose.whisper.yml` dans **deux Stacks distincts**.
3. Lancez le déploiement des deux stacks.
4. Dans **Home Assistant**, assurez-vous d'utiliser l'intégration **Wyoming Protocol** pour lier vos conteneurs.

---

## 🔗 Liens & Ressources

* 🌐 **Site Web** : [fielditech.com](https://fielditech.com)
* ☕ **Soutenir le projet** : Si ce partage vous est utile et vous fait gagner du temps, vous pouvez m'offrir un café sur [Buy Me a Coffee](https://buymeacoffee.com/fielditech).

## 📄 Licence
Distribué sous licence MIT. Voir le fichier `LICENSE` pour plus de détails.
