# ClodeX : publications

Ce dépôt ne contient que les versions publiées de ClodeX pour Windows x64 (onglet **Releases**). Le code est dans un dépôt séparé.

L'installateur n'est pas signé : Windows peut afficher un avertissement SmartScreen. Avant de l'installer, compare son empreinte SHA-256 à celle indiquée dans les notes de la version :

```powershell
Get-FileHash .\ClodeX-Setup-0.1.0-x64.exe -Algorithm SHA256
```

Désinstaller ClodeX conserve le dossier de données.
