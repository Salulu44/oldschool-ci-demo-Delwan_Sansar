1. Was macht das Dockerfile?
- Er holt sich die letzte alpine version
- dann kopiert das shellskript zum docker-container
- Dann wird den script Ausführungsrechte gegeben
- Dann startet der Container das app.sh
2. Was ist der Zweck der Pipeline?
  Nach jeden push wird ein Container gestartet, dieser automatisiert dann alles
3. Was war das schwierigste?
  Die yaml Datei zu schreiben war schwer, weil ich phyton konvention noch nicht drauf habe und ich musste mir von der AI helfen.  
