<h1>OPEN SSL</h1>

- `pem to p12:` openssl pkcs12 -export -out spiderman.p12 -in spiderman.pem

<h1>Suche</h1>

- `Auflistung aller Dateien innerhalb eines Ordners:` find <PATH> -type f -exec ls -l {} \;
- `Suche nach bestimmten Ordner (und irgnoriere 'Permission denied'-Meldung):` find / -type d -name "<FOLDER_NAME>" 2>/dev/null
