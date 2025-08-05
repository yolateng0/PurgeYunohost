# PurgeYunohost
Purge et clean Yunohost
fichier `.deb` prêt à être installé sur votre instance Yunohost :

👉 [Télécharger nettoyage-yunohost\_1.0\_all.deb](sandbox:/mnt/data/nettoyage-yunohost_1.0_all.deb)

### 📦 Pour l’installer sur votre serveur :

```bash
sudo dpkg -i nettoyage-yunohost_1.0_all.deb
```

Cela installera le script dans `/usr/local/bin/nettoyage-yunohost`.

### ▶️ Pour l'exécuter :

```bash
sudo nettoyage-yunohost
```

Souhaitez-vous une version automatisée avec suppression directe des paquets en `residual-config` ?
