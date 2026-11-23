# ClodeX · Publications

Ce dépôt distribue les versions de ClodeX pour Windows et Linux x64. Le code source est maintenu dans un dépôt séparé.

[Dernière version stable](https://github.com/KevinPiriou/ClodeX---Releases/releases/latest) · [ClodeX 0.3.6](https://github.com/KevinPiriou/ClodeX---Releases/releases/tag/v0.3.6)

## Windows x64

Télécharge l’installateur et son fichier `.sha256` dans la release. L’installateur est distribué sans signature. Windows peut afficher un avertissement SmartScreen.

```powershell
Get-FileHash .\ClodeX-Setup-0.3.6-x64.exe -Algorithm SHA256
```

Compare le résultat à l’empreinte fournie. La désinstallation conserve le dossier de données.

## Linux x64

Télécharge le ZIP et son fichier `.sha256`, compare l’empreinte, puis extrais l’archive sur Linux. Lance `./linux-unpacked/clodex` depuis une session graphique.

```sh
sha256sum ClodeX-0.3.6-linux-x64.zip
```
