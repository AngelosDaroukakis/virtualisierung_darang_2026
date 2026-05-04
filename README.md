# virtualisierung_darang_2026
## Spuren des hello-world Containers löschen
### 1. Alle Container anzeigen
docker ps -a
### 2. Container löschen.
docker rm ID des Containers(mann muss nicht alles eingeben die ersten Zeichen reichen bei kleinen Systemen wie jetzt Lokal.)
### 3. Image finden
docker images
### 4. Image löschen
docker rmi ID des Image (wie oben beim Container gleich machen.)
### 5. Kontrolle
nochmals docker ps -a und docker images es sollten die gelöschten Elemente nicht mehr angezeigt werden.

## Docker Hub Image
Das Docker Image zu diesem Projekt wurde auf Docker Hub veröffentlicht.
Link zum Docker Hub Repository:
https://hub.docker.com/repository/docker/senseibu/pythonwebserver/general
Das Image kann mit folgendem Befehl heruntergeladen werden:
```bash
docker pull senseibu/pythonwebserver:latest
```
## Container Performance
```docker stats``` um die Performance anzuzeigen
```docker stats ID``` um bestmmte Container anzuzeigen

