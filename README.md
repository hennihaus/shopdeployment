# Hinweise
1. Da ich das Backend geändert habe als auch das MongoDB-Schema muss die App per docker-compose gestartet werden.
2. Für das Starten der App muss Docker und docker-compose installiert sein.
3. Die App läuft auf allen Betriebssystemen.

# App starten

1. Zip File shopdeployment entpacken
2. In den entpackten Ordner wechseln
3. Den Befehl 'docker-compose up' eingeben

# Wo läuft was?
1. Das Frontend läuft auf Port 4200.
2. Das Backend läuft auf Port 4201.
3. Die MongoDB läuft gekapselt im DockerNetwork und ist nach außen hin nicht erreichbar.
